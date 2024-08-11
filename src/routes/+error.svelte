<script>
   import { page } from "$app/stores";
   import { Button } from "$lib/components/ui/button/index";
</script>

<head>
   <title>Error: {$page.status} {$page.error.message}</title>
</head>

<section class="flex flex-col items-center justify-center min-h-screen h-screen bg-black">
   <img 
      src={"https://http.cat/${$page.status}"} 
      alt={"HTTP Cat ${$page.status}"} 
      class="w-full max-w-xs md:max-w-sm lg:max-w-md h-auto object-cover rounded-lg shadow-lg"
   />
   <Button variant="outline" class="mt-6 w-full max-w-xs md:max-w-sm" href="/">
      Go back home
   </Button>
</section>


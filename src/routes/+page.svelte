<script>
   import { BackgroundBeams } from '$lib/components/ui/BackgroundBeams/BackgroundBeams';
</script>

<div
   class="relative flex h-screen w-screen flex-col items-center justify-center rounded-md bg-neutral-950 px-0 antialiased"
>
   <div class="mx-auto max-w-2xl p-4">
      <h1
         class="relative z-10 bg-clip-text text-center font-sans text-lg font-bold text-transparent w-full mask-fade md:text-7xl bg-gradient-to-b from-gray-300 to-gray-700"
      >
         Coming Soon™
      </h1>
      <div class="h-1"></div>
      <p class="relative z-10 mx-auto my-2 max-w-lg text-center text-lg text-neutral-500 font-sans">
         You'll just have to wait and see &#59;&#41;
      </p>
   </div>
   <BackgroundBeams />
</div>

<style>
   .mask-fade {
      padding-bottom: 0.1em;
   }

   @media (max-width: 768px) {
      h1 {
         font-size: 2rem;
      }
   }
</style>

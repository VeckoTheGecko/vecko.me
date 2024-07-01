<script>
  import VeckoWritten from "./VeckoWritten.svelte";
</script>

<svelte:head>
  <title>Vecko</title>
  <meta name="description" content="Svelte demo app" />
</svelte:head>

<div class="flex justify-center">
  <div
    class="justify-center flex flex-col items-center text-center gap-4 w-2/5 py-4"
  >
    <div class="text-4xl font-medium">Welcome to the home of</div>
    <div class="max-w-1/2 h-auto">
      <VeckoWritten />
    </div>
    <div class="text-l">
      a site of maths, data science, and computational exploration <span
        class="opacity-20">†</span
      >
    </div>
    <p class="opacity-20 text-xs text-center">
      † as well as a whole lot of other stuff, pretty which can pretty much be
      classified as "whatever I want to put on this site". Of course, that would
      a significantly less catchy tagline.
    </p>
    <div></div>
  </div>
</div>

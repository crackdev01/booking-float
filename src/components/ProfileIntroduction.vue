<template>
  <div class="flex flex-col my-8">
    <h1 class="text-4xl font-bold">Liyas Thomas</h1>
    <p class="mt-4 text-xl">
      Founder & CEO of
      <a
        class="app-link"
        href="https://hoppscotch.io"
        target="_blank"
        rel="noopener"
        >Hoppscotch</a
      >
    </p>
  </div>
</template>

<style scoped>
.app-link {
  @apply px-2;
  @apply py-1;
  @apply rounded-lg;
  @apply text-pink-700;
  @apply focus:outline-none;
  @apply focus-within:(ring ring-lime-400);
  @apply hover:text-pink-800;
  @apply dark:(text-lime-400 focus-within:ring-pink-700 hover:text-lime-200);
  @apply transition-all;
}
</style>

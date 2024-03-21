<script setup lang="ts"></script>

<template>
  <aside class="px-5 py-9 bg-sidebar h-full w-full relative">
    <NuxtLink
      to="/"
      class="mb-10 block"
    >
      <NuxtImg
        class="mx-auto"
        src="/logo.svg"
        alt="LOGO"
        width="120"
      />
    </NuxtLink>
    <button
      class="absolute top-1 right-2 transitions-colors hover:text-primary"
    >
      <Icon
        name="line-md:log-out"
        size="20"
      />
    </button>
    <LayoutMenu />
  </aside>
</template>

<style scoped></style>

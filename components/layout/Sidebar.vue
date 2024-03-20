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
        width="100"
      />
    </NuxtLink>
    <button
      class="absolute top-2 right-5 transitions-colors hover:text-primary"
    >
      <Icon
        name="line-md:log-out"
        size="20"
      />
    </button>
  </aside>
</template>

<style scoped></style>

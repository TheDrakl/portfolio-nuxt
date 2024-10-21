<template>
  <NuxtLayout />
  <section>
    <h1 class="text-4lx">Opps {{ error.statuscode }}</h1>
    <h2 class="text-xl text-gray-500 dark:text-gray-400">
      {{ error.statusMessage }}
    </h2>
  </section>
</template>

<script setup>
defineProps({ error: Object });
</script>

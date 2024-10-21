<template>
  <nav class="font-mono">
    <ul class="flex flex-col md:flex-row md:space-x-4">
      <li>
        <NuxtLink to="/" class="p-1 hover:bg-gray-200 dark:hover:bg-gray-800"
          >Main</NuxtLink
        >
      </li>
      <li>
        <NuxtLink
          to="/about"
          class="p-1 hover:bg-gray-200 dark:hover:bg-gray-800"
          >About</NuxtLink
        >
      </li>
      <li>
        <NuxtLink
          to="/projects"
          class="p-1 hover:bg-gray-200 dark:hover:bg-gray-800"
          >Projects</NuxtLink
        >
      </li>
      <li>
        <NuxtLink
          to="/blog"
          class="p-1 hover:bg-gray-200 dark:hover:bg-gray-800"
          >Blog</NuxtLink
        >
      </li>
    </ul>
  </nav>
</template>

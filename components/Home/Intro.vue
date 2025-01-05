<template>
  <div class="space-y-6">
    <NuxtImg src="/avatar.png" 
    alt="Fayaz Ahmed"
    
      class="ring-2 border ring-gray-200 border-gray-300 dark:ring-white/10 dark:border-gray-800 hover:ring-4 transition-all duration-300 bg-gray-200 dark:bg-gray-900 rounded-full h-16 w-16 sm:h-24 sm:w-24 object-cover"
      sizes="64px sm:96px" placeholder format="webp" />
    <h1 class="text-xl font-bold tracking-tight text-gray-800 dark:text-gray-100">
      Hello!
    </h1>
    <p class="text-gray-900 dark:text-gray-400">
      I'm Mikhailo Kryvoruchko (Michael Gitart), front-end developer (mostly). A bit open source contributor. I'm passionate about building software that solves problems and helps people.
    </p>
    <p class="text-gray-900 dark:text-gray-400">
      More about me and my experience can be found on my <a href="https://www.linkedin.com/in/michaelgitart/" target="_blank" class="underline">LinkedIn</a> profile. More links to my social profiles can be found below.
    </p>
  </div>
</template>

<script setup>
useSeoMeta({
  title: "Mykhailo Kryvoruchko",
  description:
    "I'm Mikhailo Kryvoruchko (Michael Gitart), front-end developer (mostly). A bit open source contributor. I'm passionate about building software that solves problems and helps people.",
});
</script>

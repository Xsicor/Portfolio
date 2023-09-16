<script setup>
import About from "./components/About.vue"
import Experience from "./components/Experience.vue"
import Projects from "./components/Projects.vue"
import StaticInformation from "./components/StaticInformation.vue"
</script>

<template>
  <div
    class="mx-auto min-h-screen max-w-screen-xl px-6 py-12 font-sans md:px-12 md:py-20 lg:px-24 lg:py-0">
    <div class="lg:flex lg:justify-between lg:gap-4">
      <StaticInformation />
      <div class="pt-24 lg:w-1/2 lg:py-24">
        <About />
        <Experience />
        <Projects />
      </div>
    </div>
  </div>
</template>

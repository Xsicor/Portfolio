<script setup>
import InformationIcon from "./icons/InformationIcon.vue";
</script>

<template>
  <div id="about" class="mb-16 scroll-mt-16 md:mb-24 lg:mb-36 lg:scroll-mt-24">
    <div
      class="flex sticky top-0 z-20 -mx-6 mb-4 w-screen bg-base-200/75 px-6 py-5 backdrop-blur md:-mx-12 md:px-12 lg:sr-only lg:relative lg:top-auto lg:mx-auto lg:w-full lg:px-0 lg:py-0 lg:opacity-0"
    >
      <InformationIcon class="mr-2 fill-slate-300" />
      <h2
        class="text-sm font-bold uppercase tracking-widest text-slate-200 lg:sr-only"
      >
        About
      </h2>
    </div>
    <div>
      <p>
        Full stack developer with a focus on the front-end based in London, UK.
        I have developed many types of front-ends from games to Hotel booking
        platforms.
      </p>
      <br />
      <p>
        Currently, I am employed at G2 Travel, where I am dedicated to creating
        an intuitive and responsive platform tailored for Travel Agents. During
        my free time, I've launched various projects to showcase my skills
      </p>
    </div>
  </div>
</template>

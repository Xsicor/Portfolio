<script setup>
import ProjectCard from "./ProjectCard.vue";
import image1 from "../assets/LondonTrainTracker.png";
import image2 from "../assets/WebTetris.png";
import image3 from "../assets/Diceware.png";
import LightBulbIcon from "./icons/LightBulbIcon.vue";
</script>

<template>
  <div id="projects" class="scroll-mt-16 lg:scroll-mt-24">
    <div
      class="flex sticky top-0 z-20 -mx-6 mb-4 w-screen bg-base-200/75 px-6 py-5 backdrop-blur md:-mx-12 md:px-12 lg:sr-only lg:relative lg:top-auto lg:mx-auto lg:w-full lg:px-0 lg:py-0 lg:opacity-0"
    >
      <LightBulbIcon class="mr-2 fill-slate-300" />
      <h2
        class="text-sm font-bold uppercase tracking-widest text-slate-200 lg:sr-only"
      >
        Projects
      </h2>
    </div>
    <ProjectCard
      code-link="https://github.com/Xsicor/London-Underground-Tracker"
      demo-link="https://www.youtube.com/watch?v=ivAo_4HLPi4"
      :image-file="image1"
      title="London Underground Tracker"
      description="Web app showcasing live London Underground train locations, using TFL API data for real-time
        arrivals, displaying train movements on an interactive map with animated icons"
      :technologies="['Django', 'Mapbox', 'TFL API', 'Python', 'Javascript']"
    />
    <ProjectCard
      code-link="https://github.com/Xsicor/Web-Tetris"
      demo-link="https://xsicor.github.io/Web-Tetris/"
      :image-file="image2"
      title="Tetris: Block Style Editor"
      description="Tetris with a touch of customisation. This project allows you to customize block styles, developed using pure vanilla JavaScript, HTML, and CSS"
      :technologies="['Javascript', 'HTML', 'CSS']"
    />
    <ProjectCard
      code-link="https://github.com/Xsicor/Diceware"
      demo-link="https://xsicor.github.io/Diceware/"
      :image-file="image3"
      title="Diceware: Password Generator"
      description="Create strong passwords using the Diceware method."
      :technologies="['React', 'Javascript', 'HTML', 'CSS']"
    />
  </div>
</template>

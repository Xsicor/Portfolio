<script setup>
import GithubIcon from "./icons/GithubIcon.vue";
import LinkedInIcon from "./icons/LinkedInIcon.vue";
import EmailIcon from "./icons/EmailIcon.vue";
import InformationIcon from "./icons/InformationIcon.vue";
import WorkIcon from "./icons/WorkIcon.vue";
import LightBulbIcon from "./icons/LightBulbIcon.vue";
</script>

<template>
  <div
    class="lg:sticky lg:top-0 lg:flex lg:max-h-screen lg:w-1/2 lg:flex-col lg:justify-between lg:py-24"
  >
    <div>
      <h1 class="text-4xl font-bold">Vara Uswaransigul</h1>
      <h2 class="mt-4 text-lg font-bold">Software Developer at G2 Travel</h2>
      <p class="mt-4 max-w-xs">
        Full-stack developer with a focus on the front end, crafting responsive
        websites that work seamlessly on any device
      </p>
      <div class="mt-16 hidden lg:block">
        <ul class="menu rounded-box w-56 bg-base-200">
          <li>
            <a href="#about" class="fill-slate-300 text-base">
              <InformationIcon />
              About
            </a>
          </li>
          <li>
            <a href="#experience" class="fill-slate-300 text-base">
              <WorkIcon />
              Experience
            </a>
          </li>
          <li>
            <a href="#projects" class="fill-slate-300 text-base">
              <LightBulbIcon />
              Projects
            </a>
          </li>
        </ul>
      </div>
    </div>
    <ul class="mt-5 flex">
      <li class="mr-3">
        <a
          href="https://github.com/Xsicor"
          target="_blank"
          class="fill-slate-400 hover:fill-slate-50"
        >
          <GithubIcon />
        </a>
      </li>
      <li class="mr-3">
        <a
          href="https://www.linkedin.com/in/vara-u-410475244/"
          target="_blank"
          class="fill-slate-400 hover:fill-slate-50"
        >
          <LinkedInIcon />
        </a>
      </li>
      <li class="mr-3">
        <a
          href="mailto: vara21458@gmail.com"
          class="fill-slate-400 hover:fill-slate-50"
        >
          <EmailIcon />
        </a>
      </li>
    </ul>
  </div>
</template>

<script setup>
import WorkIcon from "./icons/WorkIcon.vue";
</script>

<template>
  <div
    id="experience"
    class="mb-16 scroll-mt-16 md:mb-24 lg:mb-36 lg:scroll-mt-24"
  >
    <div
      class="flex sticky top-0 z-20 -mx-6 mb-4 w-screen bg-base-200/75 px-6 py-5 backdrop-blur md:-mx-12 md:px-12 lg:sr-only lg:relative lg:top-auto lg:mx-auto lg:w-full lg:px-0 lg:py-0 lg:opacity-0"
    >
      <WorkIcon class="mr-2 fill-slate-300" />
      <h2
        class="text-sm font-bold uppercase tracking-widest text-slate-200 lg:sr-only"
      >
        Experience
      </h2>
    </div>
    <div class="group card">
      <div class="card-body p-0">
        <a
          class="card-title group-hover:text-teal-300"
          href="https://www.g2-travel.com/fit-agent-website/"
          target="_blank"
        >
          Software Developer - G2 Travel
          <span
            class="absolute -inset-x-4 -inset-y-2.5 hidden rounded group-hover:bg-neutral-600/10 md:-inset-x-6 md:-inset-y-4 lg:block"
          ></span>
        </a>
        <p class="leading-none text-gray-500">2022 - Present</p>
        <p>
          I've been responsible for developing and maintaining robust production
          code across a range of projects, including image upload and
          processing. Additionally, I've collaborated closely with fellow
          developers to create a B2B Travel Agent Hotel booking website.
        </p>
        <ul class="flex flex-wrap">
          <li><div class="badge badge-accent badge-lg my-2 mr-2">Vue</div></li>
          <li>
            <div class="badge badge-accent badge-lg my-2 mr-2">Bootstrap</div>
          </li>
          <li>
            <div class="badge badge-accent badge-lg my-2 mr-2">Micronaut</div>
          </li>
          <li>
            <div class="badge badge-accent badge-lg my-2 mr-2">
              Microservices
            </div>
          </li>
          <li>
            <div class="badge badge-accent badge-lg my-2 mr-2">Javascript</div>
          </li>
          <li><div class="badge badge-accent badge-lg my-2 mr-2">Java</div></li>
        </ul>
      </div>
    </div>
  </div>
</template>

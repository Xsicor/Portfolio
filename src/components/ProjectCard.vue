<script setup>
const props = defineProps({
  demoLink: {
    type: String,
    required: true
  },
  codeLink: {
    type: String,
    required: true
  },
  imageFile: {
    type: String,
    required: true
  },
  title: {
    type: String,
    required: true
  },
  description: {
    type: String,
    required: true
  },
  technologies: {
    type: Array,
    required: true
  }
})
</script>

<template>
  <div class="card mb-12">
    <div class="card-body p-0">
      <div class="flex">
        <img :src="`../src/assets/${imageFile}`" class="h-40 rounded object-contain" />
        <ul class="ml-4 flex flex-col justify-between py-5">
          <li>
            <a class="group flex items-center py-3" :href="demoLink" target="_blank">
              <span
                class="mr-4 h-px w-8 bg-slate-600 transition-all group-hover:w-16 group-hover:bg-slate-200 group-focus-visible:w-16 group-focus-visible:bg-slate-200 motion-reduce:transition-none"></span>
              <span
                class="font-bold tracking-widest text-slate-500 group-hover:text-slate-200 group-focus-visible:text-slate-200">
                Demo
              </span>
            </a>
          </li>
          <li>
            <a class="group flex items-center py-3" :href="codeLink" target="_blank">
              <span
                class="mr-4 h-px w-8 bg-slate-600 transition-all group-hover:w-16 group-hover:bg-slate-200 group-focus-visible:w-16 group-focus-visible:bg-slate-200 motion-reduce:transition-none"></span>
              <span
                class="font-bold tracking-widest text-slate-500 group-hover:text-slate-200 group-focus-visible:text-slate-200">
                Code
              </span>
            </a>
          </li>
        </ul>
      </div>
      <p class="card-title">{{ title }}</p>
      <p>
        {{ description }}
      </p>
      <ul class="flex flex-wrap">
        <li v-for="technology in technologies" :key="technology">
          <div class="badge badge-accent badge-lg my-2 mr-2">{{ technology }}</div>
        </li>
      </ul>
    </div>
  </div>
</template>

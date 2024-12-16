<script setup>
import SkillsButton from "@/components/SkillsButton.vue";

const titles = [
  "Frontend",
  "Mobile",
  "Web",
  "HTML & CSS",
  "Vue JS",
  "Javascript",
  "TailwindCSS",
  "Flutter/Dart",
];
</script>

<template>
  <section class="hero container px-4 pt-10 mx-auto" id="hero">
    <div>
      <h1 class="text-3xl md:text-5xl font-medium mb-3">
        Achufusi Ifeanyichukwu
      </h1>
      <!-- the text -->
      <div class="flex flex-col lg:flex-row md:justify-between items-center">
        <p class="text-gray-500 text-base mb-5 md:max-w-2xl">
          A passionate software developer and creative problem-solver with a
          knack for building innovative solutions. Gaining knowledge in using
          Frontend tools and techniques to bring ideas and solutions to life.
        </p>
        <p class="font-medium">Frontend Developer, Nigeria</p>
      </div>
      <!-- the image -->
      <div class="flex justify-between items-center gap-20">
        <div class="h-[336px] w-[336px] mt-12 lg:hidden">
          <img
            src="../assets/picture.jpg"
            alt="face"
            class="h-full w-full object-contain md:object-fill"
          />
        </div>
        <div class="hidden w-[336px] mt-14 lg:h-[400px] lg:w-3/4 lg:block">
          <img
            src="../assets/image-1.jpg"
            alt="giving a talk"
            class="h-full w-[68%]"
            width="336"
            height="400"
          />
        </div>
      </div>
      <!-- the text of the image -->
      <h2
        class="text-gray-500 font-medium mt-8 md:text-4xl lg:text-5xl lg:max-w-[800px]"
      >
        Interested in emerging
        <span class="text-black">technology, </span>
        passionate about
        <span class="text-black">frontend </span>development and loves
        <span class="text-black">cartoons😄</span>
      </h2>
      <!-- the skills and all -->
      <div
        class="flex flex-wrap space-x-3 mt-10 md:mt-14 lg:flex-nowrap lg:justify-end"
      >
        <SkillsButton v-for="title in titles" :title="title" />
      </div>
      <!-- the horizontal lines -->
      <div class="bg-gray-900 h-0.5 mt-8 rounded"></div>
    </div>
  </section>
</template>

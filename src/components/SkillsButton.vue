<script setup>
const { title } = defineProps(['title']);

</script>

<template>
  <div class="py-2 px-3 rounded-3xl border text-center mt-2 lg:mt-0">
    <p class="text-sm">{{ title }}</p>
  </div>
</template>

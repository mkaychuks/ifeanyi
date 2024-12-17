<script setup>
import { RouterView } from "vue-router";
import HeaderView from "@/components/HeaderView.vue";
</script>

<template>
  <HeaderView />
  <RouterView />
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400..700;1,400..700&display=swap");
* {
  font-family: "Lora", serif;
}
</style>

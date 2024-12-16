<script setup>
import {
  PhEnvelopeSimple,
  PhLinkedinLogo,
  PhWhatsappLogo,
  PhGithubLogo,
} from "@phosphor-icons/vue";
</script>
<template>
  <footer class="footer container mx-auto my-4 px-4" id="footer">
    <div
      class="flex flex-col-reverse justify-center gap-4 items-center md:flex-row md:justify-between"
    >
      <p class="text-gray-500 text-xs">2025 &copy; Achufusi Ifeanyichukwu</p>
      <!-- the social icons -->
      <div class="flex space-x-4">
        <a href="mailto:sachufusi@gmail.com" target="_blank">
          <PhEnvelopeSimple size="22" />
        </a>
        <a href="https://wa.me/2348139460953" target="_blank">
          <PhWhatsappLogo size="22" />
        </a>
        <a href="https://github.com/mkaychuks" target="_blank">
          <PhGithubLogo size="22" />
        </a>
        <a href="https://www.linkedin.com/in/ifeanyichukwu-achufusi" target="_blank">
          <PhLinkedinLogo size="22" />
        </a>
      </div>
    </div>
  </footer>
</template>

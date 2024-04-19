<template>
  <div class="cover-page">
    <slot />
    <div class="contact-item fixed bottom-0 left-0 right-0 bg-blue-950 p-4 flex justify-around">
      <div class="flex items-center text-white">
        <FontAwesomeIcon :icon="faEnvelope" class="fa-xl mr-2" />
        <a href="mailto:safaawassim01@gmail.com">safaawassim01@gmail.com</a>
      </div>
      <div class="flex items-center text-white">
        <FontAwesomeIcon :icon="faLinkedin" class="fa-xl mr-2" />
        <a href="https://www.linkedin.com/in/wassim-safaa-8380b426a/" class="text-white">linkedin.com/wassimsafaa</a>
      </div>
      <div class="flex items-center text-white">
        <FontAwesomeIcon :icon="faPhone" class="fa-lg mr-2" />
        <p class="text-white">+33 07 66 81 53 71</p>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";
import {faEnvelope, faPhone} from "@fortawesome/free-solid-svg-icons";
import {faLinkedin} from "@fortawesome/free-brands-svg-icons";
</script>

<style>
.cover-page {
  background-size: cover;
  background: linear-gradient(to bottom, black, #061a3c, #000033) repeat center;
  scroll-behavior: smooth;
  position: relative;
  min-height: 100vh;
}

.contact-item {
  display: flex;
  align-items: center;
  justify-content: space-around;
  padding: 10px;
}

.contact-item img {
  margin-right: 10px;
}

.contact-item p {
  margin: 0;
}
</style>

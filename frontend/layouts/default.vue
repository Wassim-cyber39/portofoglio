<template>
  <div class="cover-page">
    <slot />
    <div class="footer-content">
      <!-- Ajout de votre nom à gauche -->
      <div>
        <p class="text-white font-bold">&lt;WASSIM SAFAA /&gt;</p>
      </div>
      <!-- Réseaux sociaux au milieu -->
      <div class="contact-item ">
        <!-- Logo du mail -->
        <div class="contact-item">
          <p>📧</p>
          <p class="text-white">safaawassim01@gmail.com</p>
        </div>
        <!-- Logo LinkedIn -->
        <div class="contact-item">
          <img src="../assets/linkedin.webp" alt="LinkedIn" width="50px">
          <a class="text-white" href="https://www.linkedin.com/in/wassim-safaa-8380b426a/">linkedin.com/wassimsafaa</a>
        </div>
        <!-- Logo du numéro de téléphone -->
        <div class="contact-item">
          <p>📞</p>
          <p class="text-white">+33 0766815371</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.cover-page {
  background-color: black;
  background-size: cover;
  background-repeat: repeat;
  background-position: center;
  scroll-behavior: smooth;
}

.footer-content {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-right: 20px;
  margin-left: 20px;
}

.contact-item {
  display: flex;
  align-items: center;
  justify-content: center; /* Centrage horizontal */
  padding: 10px;
}

.contact-item img {
  margin-right: 10px;
}

.contact-item p {
  margin: 0;
}
</style>

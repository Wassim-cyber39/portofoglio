<template>
  <div class="main-container">
    <div class="navbar">
      <div class="profile">

      </div>
      <div class="links">
        <a href="#home" class="link">Home</a>
        <a href="#about" class="link">About</a>
        <a href="#skills" class="link">Skills</a>
        <a href="#contact" class="link">Contact</a>
      </div>
    </div>
    <div class="content">
      <slot />
    </div>
  </div>
</template>

<style>
.main-container {
  background-color: #233831; /* Couleur de fond principale */
}

.navbar {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 80px; /* Ajustez la hauteur de la barre de navigation */
  justify-content: space-between;
  display: flex;
  color: white; /* Texte en blanc */
  background: linear-gradient(rgba(35, 56, 49, 0), rgba(35, 56, 49, 0.5)); /* Dégradé transparent */
  z-index: 1000; /* Assurez-vous que la barre de navigation soit au-dessus du contenu */
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Ajout d'une ombre */
}



.profile {
  display: flex;
  align-items: center;
  margin-left: 20px; /* Ajouter une marge à gauche pour l'espace */
}

.profile-picture {
  width: 40px; /* Ajustez la taille de votre photo */
  height: 40px; /* Ajustez la taille de votre photo */
  border-radius: 50%;
  margin-right: 10px;
}

.profile-name {
  margin-right: 20px; /* Ajouter une marge à droite pour l'espace */
}



.links {
  display: flex;
  gap: 40px;
  padding: 10px;
  align-items: center;
  margin-right: 50px;
}

.link {
  text-decoration: none;
  cursor: pointer;
}

</style>
<script setup lang="ts">
</script>
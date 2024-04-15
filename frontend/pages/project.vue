<template>
  <div class="nav-container flex justify-between items-center  p-4">
    <div>
      <h1 class="text-2xl font-bold text-white">&lt;Wassim Safaa/&gt;</h1>
    </div>
    <nav class="flex-grow flex justify-center text-white">
      <a class="text-white mx-4" href="/">Home</a>
      <a class="text-white mx-4" href="#experience">Experience</a>
      <a class="text-white mx-4" href="#about">About me</a>
      <a class="text-white mx-4" href="#skills">Skills</a>
    </nav>
    <div>
      <a class="text-white" href="/contact">Contact Me</a>
    </div>
  </div>
  <div class="cover-page  bg-black flex flex-col  text-white">
    <div id="experience" class="section bg-gray-800 text-white ">
      <!-- Contenu de la section Experience -->
      <h2 class="text-4xl font-bold mb-4">Experience</h2>
      <!-- Ajoutez ici le contenu de la section Experience -->
      <div class="experience-item mb-4">
        <h3 class="text-2xl font-semibold">Conception d’une application web en utilisant .NET et Blazor</h3>
        <p>Projet réalisé dans le cadre de la formation UHA 4.0. L'application était dédiée au groupe SCHMIDT et permettait de consulter la configuration des postes de palettisation pour toutes les usines concernées.</p>
        <p>Durée: 6 semaines (2023)</p>
        <p>Description:</p>
        <p>Application pour gérer des palettes dans le MES de chaque usine. Développement d'une application web nommée Netiospect pour la gestion de la prospection commerciale, permettant une gestion efficace des opportunités commerciales et un suivi des interactions avec les clients potentiels.</p>
      </div>
      <div class="experience-item">
        <h3 class="text-2xl font-semibold">Application pour gérer des palettes dans le MES de chaque usine</h3>
        <p>Projet réalisé dans le cadre de la formation UHA 4.0. L'objectif était de développer une application web nommée Netiospect pour la gestion de la prospection commerciale, permettant une gestion efficace des opportunités commerciales et un suivi des interactions avec les clients potentiels.</p>
        <p>Durée: 6 semaines (2024)</p>
        <p>Description:</p>
        <p>Conception d’une application web en utilisant .NET et Blazor, dédiée au groupe SCHMIDT, qui offre la possibilité de consulter la configuration des postes de palettisation pour toutes les usines concernées.</p>
      </div>
    </div>

    <div id="about" class="section bg-gray-800 text-white ">
      <!-- Contenu de la section About me -->
      <h2 class="text-4xl font-bold mb-4">About me</h2>
      <p>Je suis actuellement étudiant en développement web et m'apprête à entamer ma deuxième année. Dans le cadre de ma formation, je recherche activement une opportunité de stage ou d'alternance. Cette expérience pratique me permettra non seulement d'approfondir mes compétences, mais elle est également essentielle pour valider mon année académique. Ma passion pour le développement web est motivée par ma fascination pour la manière dont la technologie transforme le monde, et je considère cette opportunité de stage ou d'alternance comme un moyen concret de contribuer à cette transformation.</p>
    </div>

    <div id="skills" class="section bg-gray-800 text-white ">
      <!-- Contenu de la section Skills -->
      <h2 class="text-4xl font-bold mb-4">Skills</h2>
      <!-- Ajoutez ici le contenu de la section Skills -->
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-4">
        <!-- HTML / CSS -->
        <div class="skill">
          <img src="../assets/htmlcss.png" alt="HTML/CSS">
          <p>HTML / CSS</p>
        </div>
        <!-- PHP / MySQL -->
        <div class="skill">
          <img src="../assets/mysqlphp.png" alt="PHP/MySQL">
          <p>PHP / MySQL</p>
        </div>
        <!-- Javascript -->
        <div class="skill">
          <img src="../assets/JavaScript.png" alt="Javascript">
          <p>Javascript</p>
        </div>
        <!-- Wordpress -->
        <div class="skill">
          <img src="../assets/WordPress.png" alt="Wordpress">
          <p>Wordpress</p>
        </div>
        <!-- Bootstrap -->
        <div class="skill">
          <img src="../assets/Bootstrap.png" alt="Bootstrap">
          <p>Bootstrap</p>
        </div>
        <!-- Nest -->
        <div class="skill">
          <img src="../assets/nestjs.png" alt="Nest">
          <p>#Nest</p>
        </div>
        <!-- NUXt -->
        <div class="skill">
          <img src="../assets/NuxtJS.png" alt="nuxt">
          <p>#Nuxt</p>
        </div>
        <!-- Django Python -->
        <div class="skill">
          <img src="../assets/django.png" alt="Django Python">
          <p>Django Python</p>
        </div>
        <!-- Angular -->
        <div class="skill">
          <img src="../assets/angular.png" alt="Angular">
          <p>Angular</p>
        </div>
      </div>
    </div>

  </div>
</template>

<style>
.cover-page {
  background-color: #222; /* Gris foncé */
  border-radius: 20px; /* Contour arrondi */
  border: 5px solid green; /* Bordure verte */
  padding: 20px;
  margin: 50px; /* Ajout de marges */
}

.section {
  padding: 20px;

  border-radius: 12px;
  box-shadow: 0px 8px 24px rgba(0, 0, 0, 0.1);
  margin: 50px; /* Ajout de marges */
}

.experience-item {
  margin-bottom: 20px;
}

.skill {
  text-align: center;
  width: calc(25% - 20px); /* Largeur des cases ajustée pour occuper un quart de l'espace */
}

.skill img {
  width: 100px; /* Ajustez la taille de l'image selon vos préférences */
  height: auto;
}

.skill p {
  margin-top: 10px;
}
</style>



<script setup lang="ts">
</script>

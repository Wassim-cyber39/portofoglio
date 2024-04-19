<template>
  <div>
    <div class="nav-container flex justify-between items-center p-4">
      <div>
        <a href="/">
          <h1 class="text-2xl font-bold text-white">&lt;Wassim Safaa/&gt;</h1>
        </a>
      </div>
      <nav class="flex justify-center text-white">
        <a :class="{ 'active': activeTab === 'experience' }" class="text-white mx-4 hover:text-gray-700" @click="activeTab = 'experience'">Experience</a>
        <a :class="{ 'active': activeTab === 'about' }" class="text-white mx-4 hover:text-gray-700" @click="activeTab = 'about'">About me</a>
        <a :class="{ 'active': activeTab === 'skills' }" class="text-white mx-4 hover:text-gray-700" @click="activeTab = 'skills'">Skills</a>
        <a class="text-white mx-4 hover:text-gray-700" href="mailto:safaawassim01@gmail.com">Contact Me</a>
      </nav>
    </div>
<div class="flex justify-center  text-white">
    <div v-if="activeTab === 'experience'">
      <div class="content-container flex" style="width: 500px ; ">
        <div class="section bg-blue-200 text-black" @click="openModal1()">
          <div class="card mb-4">
            <h2 class="text-1xl font-bold mb-4">Expérience 1 : Conception d’une application web en utilisant .NET et Blazor</h2>
          </div>
        </div>
      </div>

      <div class="content-container flex" style="width: 500px ; ">
        <div class="section bg-blue-200 text-black" @click="openModal2()">
          <div class="card mb-4">
            <h2 class="text-1xl font-bold mb-4">Expérience 2 : Application pour gérer des palettes dans le MES de chaque usine</h2>
          </div>
        </div>
      </div>
    </div>
</div>
    <div v-if="activeTab === 'about'" class="section bg-blue-200 text-black">
      <h2 class="text-2xl font-bold mb-4">About me</h2>
      <p>Je suis actuellement étudiant en développement web et m'apprête à entamer ma deuxième année. Dans le cadre de ma formation, je recherche activement une opportunité de stage ou d'alternance. Cette expérience pratique me permettra non seulement d'approfondir mes compétences, mais elle est également essentielle pour valider mon année académique. Ma passion pour le développement web est motivée par ma fascination pour la manière dont la technologie transforme le monde, et je considère cette opportunité de stage ou d'alternance comme un moyen concret de contribuer à cette transformation.</p>
    </div>
    <div v-if="activeTab === 'skills'" class="section bg-blue-200 text-black">
      <h2 class="text-4xl font-bold mb-4">Skills</h2>
      <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4">
        <div class="skill bg-white p-4 rounded-lg shadow-md transition-colors border hover:bg-gray-200 hover:border-blue-500">
          <p>HTML / CSS</p>
        </div>
        <div class="skill bg-white p-4 rounded-lg shadow-md transition-colors border hover:bg-gray-200 hover:border-blue-500">
          <p>PHP / MySQL</p>
        </div>
        <div class="skill bg-white p-4 rounded-lg shadow-md transition-colors border hover:bg-gray-200 hover:border-blue-500">
          <p>Javascript</p>
        </div>
        <div class="skill bg-white p-4 rounded-lg shadow-md transition-colors border hover:bg-gray-200 hover:border-blue-500">
          <p>Wordpress</p>
        </div>
        <div class="skill bg-white p-4 rounded-lg shadow-md transition-colors border hover:bg-gray-200 hover:border-blue-500">
          <p>Bootstrap</p>
        </div>
        <div class="skill bg-white p-4 rounded-lg shadow-md transition-colors border hover:bg-gray-200 hover:border-blue-500">
          <p>#Nest</p>
        </div>
        <div class="skill bg-white p-4 rounded-lg shadow-md transition-colors border hover:bg-gray-200 hover:border-blue-500">
          <p>#Nuxt</p>
        </div>
        <div class="skill bg-white p-4 rounded-lg shadow-md transition-colors border hover:bg-gray-200 hover:border-blue-500">
          <p>Django Python</p>
        </div>
        <div class="skill bg-white p-4 rounded-lg shadow-md transition-colors border hover:bg-gray-200 hover:border-blue-500">
          <p>Angular</p>
        </div>
      </div>
    </div>

    <!-- Modal -->
    <transition name="modal">
      <div v-if="showModal1" class="modal-mask" @click="closeModal(1)">
        <div class="modal-wrapper">
          <div class="modal-container">
            <div class="modal-header">
              <h3 class="modal-title">Expérience 1</h3>
              <span class="modal-close" @click="closeModal(1)">&times;</span>
            </div>
            <div class="modal-body">
              <!-- Content for Experience 1 modal -->
              <div class="experience-item">
                <p>Projet réalisé dans le cadre de la formation UHA 4.0. L'application était dédiée au groupe SCHMIDT et permettait de consulter la configuration des postes de palettisation pour toutes les usines concernées.</p>
                <p><strong> Durée: </strong> 6 semaines (2024)</p>
                <p><strong> Description: </strong> Application pour gérer des palettes dans le MES de chaque usine. Développement d'une application web nommée Netiospect pour la gestion de la prospection commerciale, permettant une gestion efficace des opportunités commerciales et un suivi des interactions avec les clients potentiels.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </transition>

    <!-- Modal for Experience 2 -->
    <transition name="modal">
      <div v-if="showModal2" class="modal-mask" @click="closeModal(2)">
        <div class="modal-wrapper">
          <div class="modal-container">
            <div class="modal-header">
              <h3 class="modal-title">Expérience 2</h3>
              <span class="modal-close" @click="closeModal(2)">&times;</span>
            </div>
            <div class="modal-body">
              <!-- Content for Experience 2 modal -->
              <div class="experience-item">
                <p>Projet réalisé dans le cadre de la formation UHA 4.0. L'application était dédiée au groupe SCHMIDT et permettait de consulter la configuration des postes de palettisation pour toutes les usines concernées.</p>
                <p><strong> Durée: </strong> 6 semaines (2024)</p>
                <p><strong> Description: </strong> Conception d’une application web en utilisant .NET et Blazor, dédiée au groupe SCHMIDT, qui offre la possibilité de consulter la configuration des postes de palettisation pour toutes les usines concernées.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </transition>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue';

const activeTab = ref('experience'); // Définit la première tab active par défaut
const showModal = ref(false);

const showModal1 = ref(false);
const showModal2 = ref(false);

// Function to open the modal for Experience 1
function openModal1() {
  showModal1.value = true;
}

// Function to open the modal for Experience 2
function openModal2() {
  showModal2.value = true;
}

// Function to close the modal
function closeModal(modalNumber) {
  if (modalNumber === 1) {
    showModal1.value = false;
  } else if (modalNumber === 2) {
    showModal2.value = false;
  }
}
</script>

<style scoped>
.skill:hover {
  cursor: pointer;
}
.nav-container a {
  transition: color 0.3s ease; /* Animation de transition pour les liens */
}

.nav-container a.active {
  color: #fff; /* Couleur du texte pour l'onglet actif */
}

.content-container {
  padding: 20px;
}

.section {
  padding: 20px;
  border-radius: 12px;
  box-shadow: 0px 8px 24px rgba(0, 0, 0, 0.1);
  margin-bottom: 20px; /* Ajout de marges entre les sections */
  cursor: pointer; /* Add cursor pointer to indicate it's clickable */
}

.modal-mask {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: rgba(0, 0, 0, 0.5);
  display: flex;
  justify-content: center;
  align-items: center;
}

.modal-wrapper {
  width: 100%;
}

.modal-container {
  background-color: #fff;
  border-radius: 8px;
  padding: 20px;
  width: auto;
  height: auto;
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}


.modal-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-bottom: 1px solid #ccc;
  padding-bottom: 10px;
}

.modal-title {
  font-size: 20px;
  font-weight: bold;
}

.modal-close {
  cursor: pointer;
  font-size: 24px;
}

.modal-body {
  padding-top: 20px;
}

.modal-enter-active,
.modal-leave-active {
  transition: opacity 0.3s;
}

.modal-enter-from,
.modal-leave-to {
  opacity: 0;
}
</style>

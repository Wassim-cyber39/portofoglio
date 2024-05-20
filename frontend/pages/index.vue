<template>
  <div class="pages-container">
    <div class="pages">
      <section id="home" class="page">
        <div class="text1 flex flex-col items-center justify-center">
          <h1 class="heading-primary text-white">HEY, I'M SAFAA WASSIM</h1>
          <div class="text-center">
            <p class="text-primary text-white">Bienvenue sur mon portfolio ! Je suis passionné par le développement web
              et je crée des expériences numériques innovantes.</p>
          </div>
        </div>
        <div class="mouse">
          <fa :icon="['fas', 'angle-down']" class="fa-angle-down"></fa>
        </div>
      </section>

      <section id="about" class="page">
        <h1 class="heading-primary text-white " style="margin: 50px">ABOUT ME</h1>
        <div class="about2">
          <div class="about-content">
            <div class="about-text text-white">
              <p>Je suis un étudiant passionné par le développement web, sur le point d'entamer ma deuxième année
                d'études. Actuellement, je suis à la recherche active d'opportunités de stage ou d'alternance dans le
                domaine. Cette expérience pratique sera non seulement bénéfique pour approfondir mes compétences, mais
                elle est également cruciale pour valider mon année académique.</p>
              <p>Ma fascination pour le développement web découle de ma conviction en la capacité de la technologie à
                transformer le monde. Ainsi, je considère chaque opportunité de stage ou d'alternance comme un moyen
                concret de contribuer à cette transformation.</p>
              <p>J'ai déjà travaillé sur 5 projets avec des entreprises dans le cadre de mon école, où j'ai acquis une
                expérience pratique du travail en équipe et de la méthodologie Scrum. Ma capacité à collaborer
                efficacement dans un environnement Agile a été renforcée à travers ces expériences.</p>
              <p>En dehors de mes études et de mon travail en développement web, j'ai une passion pour le football, un
                sport qui m'inspire à atteindre l'excellence et à travailler en équipe.</p>
              <p>Je vous invite à me contacter sur LinkedIn pour suivre mes projets et mes publications liées au
                développement web. Vous pouvez également me joindre par e-mail à </p> <a href="mailto:safaawassim01@gmail.com">wassimsafaa01@gmail.com</a> <p> pour toute
              opportunité professionnelle.</p>
            </div>
          </div>
          <div class="about-image">
            <img src="../assets/pdp.png" alt="Votre photo de profil">
          </div>
        </div>
      </section>

      <section id="skills" class="page">
        <h1 class="heading-primary text-white " style="margin: 50px">Skills</h1>
        <div class="skill2">
          <div class="skill-content">
            <div class="skills-list text-white">
              <div class="skill badge">
                <span>HTML</span>
              </div>
              <div class="skill badge">
                <span>CSS</span>
              </div>
              <div class="skill badge">
                <span>JavaScript</span>
              </div>
              <div class="skill badge">
                <span>PHP</span>
              </div>
              <div class="skill badge">
                <span>MySQL</span>
              </div>
              <div class="skill badge">
                <span>Wordpress</span>
              </div>
              <div class="skill badge">
                <span>Bootstrap</span>
              </div>
              <div class="skill badge">
                <span>Git</span>
              </div>
              <div class="skill badge">
                <span>Framework Scrum</span>
              </div>
              <div class="skill badge">
                <span>Confluence</span>
              </div>
              <div class="skill badge">
                <span>Jira</span>
              </div>
              <div class="skill badge">
                <span>NestJS</span>
              </div>
              <div class="skill badge">
                <span>Vue.js</span>
              </div>
              <div class="skill badge">
                <span>Angular</span>
              </div>
            </div>
          </div>
          <div class="skills-image">
            <img src="../assets/c.jpg" alt="Votre photo de profil">
          </div>
        </div>
      </section>

      <footer class="main-footer" id="contact">
        <div class="main-footer__upper">
          <div class="main-footer__text">
            <p>Merci de visiter mon portfolio ! N'hésitez pas à me contacter pour toute opportunité professionnelle.</p>
          </div>
          <div class="main-footer__social">
            <p>Contactez-moi :</p>
            <a href="mailto:safaawassim01@gmail.com" class="social-icon">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                <path d="M48 64C21.5 64 0 85.5 0 112c0 15.1 7.1 29.3 19.2 38.4L236.8 313.6c11.4 8.5 27 8.5 38.4 0L492.8 150.4c12.1-9.1 19.2-23.3 19.2-38.4c0-26.5-21.5-48-48-48H48zM0 176V384c0 35.3 28.7 64 64 64H448c35.3 0 64-28.7 64-64V176L294.4 339.2c-22.8 17.1-54 17.1-76.8 0L0 176z"/>
              </svg>
            </a>
            <a href="https://www.linkedin.com/in/wassim-safaa-8380b426a/" target="_blank" class="social-icon">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
                <path d="M416 32H31.9C14.3 32 0 46.5 0 64.3v383.4C0 465.5 14.3 480 31.9 480H416c17.6 0 32-14.5 32-32.3V64.3c0-17.8-14.4-32.3-32-32.3zM135.4 416H69V202.2h66.5V416zm-33.2-243c-21.3 0-38.5-17.3-38.5-38.5S80.9 96 102.2 96c21.2 0 38.5 17.3 38.5 38.5 0 21.3-17.2 38.5-38.5 38.5zm282.1 243h-66.4V312c0-24.8-.5-56.7-34.5-56.7-34.6 0-39.9 27-39.9 54.9V416h-66.4V202.2h63.7v29.2h.9c8.9-16.8 30.6-34.5 62.9-34.5 67.2 0 79.7 44.3 79.7 101.9V416z"/>
              </svg>
            </a>
          </div>
        </div>
        <div class="main-footer__lower">
          <div class="main-footer__credits">
            © Copyright 2024. Made by <a href="#">SAFAA Wassim</a>
          </div>
        </div>
      </footer>

    </div>
  </div>
</template>

<style scoped>
.text1 {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  max-width: 90rem;
  width: 92%;
}

.mouse {
  width: 25px;
  height: 40px;
  border: 2px solid white;
  border-radius: 60px;
  position: absolute;
  bottom: 20px;
  left: 50%;
  transform: translateX(-50%);
  overflow: hidden;
}

.mouse .fa-angle-down {
  width: 5px;
  height: 5px;
  position: absolute;
  top: 50%;
  left: 40%;
  transform: translate(-50%, -50%);
  color: white;
  background-color: white;
  border-radius: 50%;
  opacity: 1;
  animation: wheel 1.3s infinite;
}

@keyframes wheel {
  0% {
    opacity: 0;
    transform: translateY(-20px);
  }
  50% {
    opacity: 1;
    transform: translateY(0);
  }
  100% {
    opacity: 0;
    transform: translateY(20px);
  }
}

.text-primary {
  font-size: 1rem;
  text-align: center;
  width: 100%;
  line-height: 1.6;
}

.heading-primary {
  font-size: 3rem;
  text-transform: uppercase;
  letter-spacing: 3px;
  text-align: center;
  font-weight: 800;
}

.pages {
  overflow-y: auto;
  flex-grow: 1;
}

.page {
  min-height: 100vh;
  padding: 20px;
}

.about2 {
  margin-top: 50px;
  display: flex;
  justify-content: space-around;
}

.skill2 {
  margin-top: 100px;
  display: flex;
  justify-content: space-around;
}

.about-content {
  display: flex;
  align-items: center;
  justify-content: space-between;
  border-radius: 15px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  padding: 30px;
  text-align: center;
  max-width: 800px;
  font-size: 1.1rem; /* Augmenter la taille de la police */
  line-height: 1.8; /* Espacement entre les lignes */
  margin-bottom: 20px;
}

.about-text {
  flex: 1;
}

.about-image {
  margin-left: 20px;
}

.about-image img {
  width: 100%;
  border-radius: 10px;
}

.skills-list {
  display: flex;
  flex-wrap: wrap;
}

.skills-image {
  margin-left: 20px;
  width: 40%;
  border-radius: 10px;
}

.badge {
  display: inline-block;
  padding: 10px 20px;
  margin: 5px;
  border-radius: 20px;
  background-color: #033303; /* Couleur de fond */
  color: white; /* Couleur du texte */
  font-size: 1.1rem;
}

.badge i {
  margin-right: 10px; /* Ajouter un espace entre l'icône et le texte */
}

.skill-content {
  display: flex;
  align-items: center;
  justify-content: space-between;
  border-radius: 15px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  padding: 30px;
  text-align: center;
  max-width: 800px;
  font-size: 1.1rem; /* Augmenter la taille de la police */
  line-height: 1.8; /* Espacement entre les lignes */
  margin-bottom: 20px;
}

.cv-section {
  display: flex;
  justify-content: center;
  gap: 20px;
}

.cv-item {
  display: flex;
  justify-content: center;
  align-items: center;
}

.cv-link {
  text-decoration: none;
}

.cv-button {
  background-color: #033303;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 10px;
  font-size: 1.1rem;
  cursor: pointer;
  transition: background-color 0.3s;
}

.cv-button:hover {
  background-color: #045204;
}

.main-footer {
  background: #000000;
  color: #fffdfd;
  padding: 2rem 1rem;
}

.main-footer__upper {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-bottom: 1rem;
  margin-bottom: 1rem;
}

.main-footer__text {
  flex: 1;
  font-size: 1.2rem;
  line-height: 1.6;
}

.main-footer__social {
  display: flex;
  align-items: center;
}

.main-footer__social p {
  margin-right: 1rem;
}

.main-footer__social a {
  display: inline-block;
  margin-right: 10px;
  width: 24px;
  height: 24px;
}

.main-footer__social svg {
  width: 100%;
  height: 100%;
  fill: #ffffff; /* Ensure the color is white */
}

.main-footer__lower {
  text-align: center;
  font-size: 0.8rem;
  padding-top: 1rem;
}

.main-footer__credits a {
  text-decoration: underline;
  font-weight: bold;
  margin-left: 2px;
  color: #ffffff;
}
</style>

<script setup lang="ts">
import { ref } from 'vue';
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome';

const currentPage = ref(1);
const pageCount = ref(4);
</script>

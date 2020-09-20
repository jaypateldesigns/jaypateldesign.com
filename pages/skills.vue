<template>
  <div class="skill-container">
    <ul class="skills-content">
      <li><FontAwesomeIcon :icon="['fab', 'html5']" size="5x" /></li>
      <li><FontAwesomeIcon :icon="['fab', 'css3']" size="5x" /></li>
      <li><FontAwesomeIcon :icon="['fab', 'js']" size="5x" /></li>
      <li><FontAwesomeIcon :icon="['fab', 'react']" size="5x" /></li>
      <li><FontAwesomeIcon :icon="['fab', 'vuejs']" size="5x" /></li>
      <li><FontAwesomeIcon :icon="['fab', 'node-js']" size="5x" /></li>
      <li><FontAwesomeIcon :icon="['fab', 'git']" size="5x" /></li>
      <li><FontAwesomeIcon :icon="['fab', 'github']" size="5x" /></li>
      <li><FontAwesomeIcon :icon="['fab', 'npm']" size="5x" /></li>
      <li><FontAwesomeIcon :icon="['fab', 'yarn']" size="5x" /></li>
      <li><FontAwesomeIcon :icon="['fab', 'sass']" size="5x" /></li>
      <li><FontAwesomeIcon :icon="['fab', 'java']" size="5x" /></li>
      <li><FontAwesomeIcon :icon="['fab', 'php']" size="5x" /></li>
      <li><FontAwesomeIcon :icon="['fab', 'wordpress']" size="5x" /></li>
      <li><FontAwesomeIcon :icon="['fab', 'joomla']" size="5x" /></li>
      <li><FontAwesomeIcon icon="terminal" size="5x" /></li>
      <li><FontAwesomeIcon icon="server" size="5x" /></li>
      <li><FontAwesomeIcon icon="database" size="5x" /></li>
      <li><FontAwesomeIcon icon="camera" size="5x" /></li>
      <li><FontAwesomeIcon :icon="['fab', 'apple']" size="5x" /></li>
      <li><FontAwesomeIcon :icon="['fab', 'windows']" size="5x" /></li>
      <li><FontAwesomeIcon :icon="['fab', 'linux']" size="5x" /></li>
    </ul>
  </div>
</template>

<script>
// import Vue from 'vue'
import { library } from '@fortawesome/fontawesome-svg-core';
import {
  faReact,
  faVuejs,
  faPhp,
  faWordpress,
  faNodeJs,
  faJs,
  faJava,
  faHtml5,
  faCss3,
  faJoomla,
  faApple,
  faWindows,
  faLinux,
  faGit,
  faGithub,
  faCpanel,
  faNpm,
  faYarn,
  faSass,
} from '@fortawesome/free-brands-svg-icons';
import {
  faCamera,
  faDatabase,
  faServer,
  faTerminal,
} from '@fortawesome/free-solid-svg-icons';
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome';

library.add(faReact);
library.add(faVuejs);
library.add(faPhp);
library.add(faWordpress);
library.add(faNodeJs);
library.add(faJs);
library.add(faJava);
library.add(faHtml5);
library.add(faCss3);
library.add(faJoomla);
library.add(faApple);
library.add(faWindows);
library.add(faLinux);
library.add(faGit);
library.add(faGithub);
library.add(faDatabase);
library.add(faTerminal);
library.add(faServer);
library.add(faCamera);
library.add(faCpanel);
library.add(faNpm);
library.add(faYarn);
library.add(faSass);

export default {
  components: {
    FontAwesomeIcon,
  },
};
</script>

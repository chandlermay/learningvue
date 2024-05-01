<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
const navclass = "navclass"
const mainsection = "mainsection"
const wholepage = "wholepage"
</script>

<template>
  <div :class="wholepage">
    <div :class='navclass'>
      <nav>
        <a>Chandler Mei</a>
        <ul>
          <a>Click Me</a>
          <a>Resume</a>
        </ul>
      </nav>
    </div>
    <div :class="mainsection">
      <header>Hey! I'm Chandler and this is who I am...</header>
    </div>
  </div>
</template>

<style scoped>
/* .navclass {
  background-color: aqua;
  display: flex;
  flex-direction: row;
  justify-content: center;
  width: 100vw;
  line-height: 10vh;
}

.mainsection {
  background-color: brown;
  height: 90vh;
}

.wholepage {
  background-image: "https://images.pexels.com/photos/12786595/pexels-photo-12786595.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1";
} */
</style>

<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
const navclass = "navclass"
</script>

<template>
  <nav :class='navclass'>
  <li>
    <button>Click Me</button>
    <button>Resume</button>
  </li>
  </nav>
</template>

<style scoped>
.navclass {
  background-color: aqua;

}
</style>

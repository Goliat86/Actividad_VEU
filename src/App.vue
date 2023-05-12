<template>
  <div id="app">
    <actividadPeaku></actividadPeaku>
    
    <contenidoPeaku/>
    <contenidoPeaku/>
    <contenidoPeaku/>
    <contenidoPeaku/>
    <contenidoPeaku/>
  </div>
</template>

<script>

import actividadPeaku from './components/actividad.vue';
import contenidoPeaku from './components/contenido.vue'

export default {
  name: 'App',
  components: {
    actividadPeaku,
    contenidoPeaku

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

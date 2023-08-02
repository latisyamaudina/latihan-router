<!-- <template>
  <Navbar :idMenu="idMenu" key="idMenu"/>
  <router-view @id-menu="setMenu($event)"/>
</template> -->
<template>
  <Navbar/>
  <router-view/>
</template>

<script>
import Navbar from './components/Navbar.vue'

export default {
  name: 'App',
  components : {
    Navbar
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2e47d3;
}
</style>
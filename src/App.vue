<template>
  <!-- <HelloWorld />
  <HalloDua /> -->
  <HomeComponent />
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import HalloDua from './components/HalloDua.vue'
import HomeComponent from './components/HomeComponent.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    // HalloDua,
    HomeComponent
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

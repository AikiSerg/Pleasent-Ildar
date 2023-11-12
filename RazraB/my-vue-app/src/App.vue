<template>
  <TheHeader />
  <TheVideo />
  <TheSnacks />
</template>

<script>

import TheHeader from './components/TheHeader.vue'
import TheVideo from './components/TheVideo.vue'
import TheSnacks from './components/TheSnacks.vue'

export default {
  name: 'App',
  components: {

    TheHeader,
    TheVideo,
    TheSnacks,
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
  margin-top: -55px; 
}
</style>

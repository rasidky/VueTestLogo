<template>
  <img class="front-logo" alt="Vue logo" 
  src="./assets/Blue_Archive_EN_logo.svg.png"
  >
  <LogoTest/>
</template>

<script>
import LogoTest from './components/LogoTest.vue'

export default {
  name: 'App',
  components: {
    LogoTest
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

.front-logo{
  width: 40%;
}
</style>

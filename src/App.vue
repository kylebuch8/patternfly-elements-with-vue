<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
:root {
  --pfe-card--BorderColor: #eee;
  --pfe-card--BorderWeight: 1px;
}

body {
  font-family: "Source Sans Pro", sans-serif;
}

section {
  margin-bottom: 36px;
}

@media (min-width: 768px) {
  #app {
    width: 100%;
  }
}

@media (min-width: 1200px) {
  #app {
    width: 1140px;
    margin: auto;
  }
}
</style>

<template>
  <div id="app">
      <MainWrapper/>
  </div>
</template>

<script>
import MainWrapper from "@/components/MainWrapper.vue";

export default {
  name: 'App',
  components: {
      MainWrapper
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
  margin-top: 1%;
  margin-bottom: 1%;
}
</style>

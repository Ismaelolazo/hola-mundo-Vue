<template>
  <div id="app">
    <img
      alt="Vue logo"
      src="https://adminweb.miteleferico.bo/uploads/BUSA_Logo_Azul_RGB_01_c178dd2b50.png"
      width="400"
    />
    <HelloWorld msg="El Banco de los Bolivianos" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
};
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

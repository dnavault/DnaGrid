<template>
  <div id="app">
    <HelloWorld/>
    <DnaGrid/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import DnaGrid from "./components/DnaGrid";

export default {
  name: "App",
  components: {
    HelloWorld,
    DnaGrid
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

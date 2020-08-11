<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png">
    <Pixel msg="Hello Vue in CodeSandbox!"/>
  </div>
</template>

<script>
import Pixel from "./components/Pixel";

export default {
  name: "App",
  components: {
    Pixel
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

<template>
  <div id="app">
    <NavBar />
    <Invoice />
  </div>
</template>

<script>
import NavBar from "./components/NavBar";
import Invoice from "./components/Invoice";
export default {
  name: "App",
  components: {
    NavBar,
    Invoice,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
body {
  background-color: rgb(247, 247, 247);
}
</style>

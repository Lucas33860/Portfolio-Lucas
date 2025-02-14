<template>
  <div id="app">
    <Header />
    <About />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import About from "./components/About.vue";

export default {
  name: "App",
  components: {
    Header,
    About,
  },
};
</script>

<style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}
</style>

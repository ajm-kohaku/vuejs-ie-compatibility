<template>
  <div class="container">
    <div class="d-flex justify-content-center">
      <img class="" alt="Vue logo" src="./assets/logo.png" />
    </div>
    <hello-world msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,400;0,600;1,400&family=Raleway:ital,wght@0,400;0,500;1,500&display=swap");
$primary: #8132a8;
$font-family: "Raleway", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
  sans-serif;
@import "~bootstrap/scss/bootstrap";
</style>

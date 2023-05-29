<template>
  <div class="container">
    <img src="./assets/rsvp.png" alt="Imagen" class="centered-image">
  </div>
</template>

<script>
// import Info from "./components/Info.vue";

export default {
  name: 'App',
}
</script>

<style>
html, body {
  height: 100%;
  margin: 0;
  padding: 0;
}
#app {
  height: 100%;
}
.container {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
}

.centered-image {
  max-width: 100%;
  max-height: 100%;
  display: block;
  margin: auto;
}
</style>

<template>
  <div id="app">
    <Header />
    <div class="main-container">
      <Heading />
      <Releases />
    </div>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Heading from "./components/Heading.vue";
import Releases from "./components/Releases.vue";

export default {
  name: "app",
  components: {
    Header,
    Heading,
    Releases
  }
};
</script>

<style>
.main-container {
  padding: 67px;
}
* {
  margin: 0;
  padding: 0%;
  background: #000;
}
#app {
  background: #000;
  height: 100vh;
}
</style>>


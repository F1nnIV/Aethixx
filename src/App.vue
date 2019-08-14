<template>
  <div id="app">
    <h1 class="side-heading">Aethixx</h1>
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
.side-heading {
  position: absolute;
  width: 530px;
  height: 151px;
  top: 450px;
  right: 70px;
  font-family: "Apercu";
  font-style: normal;
  font-weight: 500;
  font-size: 90px;
  line-height: 111px;
  letter-spacing: 0.33em;
  background: none;
  color: rgba(255, 255, 255, 0.22);

  transform: rotate(-90deg);
}
.main-container {
  padding: 64px;
}
* {
  margin: 0;
  padding: 0%;
  background: #000;
}
#app {
  background: #000;
  height: 100vh;
  position: relative;
}
</style>>


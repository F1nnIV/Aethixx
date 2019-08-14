<template>
  <div class="releases">
    <Waves class="track" />
    <Nebula class="track" />
  </div>
</template>

<script>
import Waves from "./Releases/Waves.vue";
import Nebula from "./Releases/Nebula.vue";

export default {
  name: "Releases",
  props: {
    msg: String
  },
  components: {
    Waves,
    Nebula
  }
};
</script>

<style scoped>
.track {
  margin-top: 43px;
}
.releases {
  padding-bottom: 127px;
}
</style>
<template>
  <div class="waves">
    <img src="../../assets/waves.jpg" alt="waves" />
    <Button content="Listen Now" />
  </div>
</template>


<script>
import Button from "../UI/Button.vue";
export default {
  name: "Waves",
  props: {
    msg: String
  },
  components: {
    Button
  }
};
</script>

<style scoped>
img {
  width: 277px;
}
</style>
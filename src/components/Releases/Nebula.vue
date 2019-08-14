<template>
  <div class="nebula">
    <img src="../../assets/Nebula.jpg" alt="nebula" />
    <Button content="Listen Now" />
  </div>
</template>

<script>
import Button from "../UI/Button.vue";
export default {
  name: "Nebula",
  props: {
    msg: String
  },
  components: { Button }
};
</script>

<style scoped>
img {
  width: 277px;
}
</style>
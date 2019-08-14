<template>
  <div class="heading">
    <h1>
      A Music
      <br />Duo.
    </h1>
  </div>
</template>

<script>
export default {
  name: "Heading",
  props: {
    msg: String
  }
};
</script>

<style scoped>
h1 {
  font-family: "Apercu", "Courier New", Courier, monospace;
  font-size: 72px;
  font-weight: bold;
  color: white;
  letter-spacing: -0.06em;
  text-indent: 6px;
  line-height: 75px;
}
</style>
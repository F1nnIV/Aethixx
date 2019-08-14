<template>
  <div class="container">
    <a href="https://nebula.fanlink.to/aethixx">{{content}}</a>
  </div>
</template>

<script>
export default {
  name: "Button",
  props: {
    content: String
  },
  components: {}
};
</script>

<style scoped>
.container {
  display: flex;
  justify-content: center;
}
a {
  font-family: "Apercu";
  font-style: normal;
  font-weight: bold;
  font-size: 15px;
  line-height: 43px;
  letter-spacing: 0.12em;
  color: #ffffff;
  text-decoration: none;
  display: block;
  width: 156px;
  height: 43px;
  background: #116a7f;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 26px;
  margin-top: 23px;
  color: white;
  text-align: center;
}
a:hover {
  background: #507179;
}
</style>
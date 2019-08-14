<template>
  <div class="container">
    <img src="../assets/logo.png" alt="logo" class="logo" />
    <img src="../assets/menu.svg" alt="menu" class="menu-bars" />
  </div>
</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container {
  padding: 18px 18px 0 18px;
  display: flex;
  justify-content: space-between;
}
.logo {
  width: 51px;
}
.menu-bars {
  width: 29px;
}
</style>

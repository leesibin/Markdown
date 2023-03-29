<template>
  <div class="two-box1">
    <span class="two-text">02</span>
  </div>
</template>

<script>
/* eslint-disable */
export default {
  name: "app",
  data() {
    return {};
  },
  methods: {},
};
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
}
.two-box1 {
  position: absolute;
  top: 35%;
  left: 25%;
  width: 60%;
  height: 300px;
  background: rgb(255, 255, 255);
  box-shadow: -10px 10px 20px 0;
  z-index: 4;
  text-align: right;
}
.two-text {
  background-image: url("/public/tree1.png");
  background-clip: text;
  -webkit-background-clip: text;
  color: transparent;
  margin-right: 3rem;
  text-align: right;
  font-family: "Bowlby One SC", cursive;
  font-size: 8rem;
}
</style>

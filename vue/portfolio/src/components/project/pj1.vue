<template>
  <div class="one-box1">
    <span class="one-text">01</span>
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
.one-box1 {
  position: absolute;
  top: 0%;
  left: 10%;
  margin: 10rem 10rem;
  width: 60%;
  height: 300px;
  background: rgb(255, 255, 255);
  box-shadow: -10px 10px 20px 0px;
  text-align: left;
  z-index: 6;
}
.one-text {
  background-image: url("/public/tree.png");
  background-clip: text;
  -webkit-background-clip: text;
  color: transparent;
  margin-left: 3rem;
  font-family: "Bowlby One SC", cursive;
  font-size: 8rem;
}
</style>

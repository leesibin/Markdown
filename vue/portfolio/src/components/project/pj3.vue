<template>
  <div class="three-box1">
    <span class="three-text">03</span>
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
.three-box1 {
  position: absolute;
  top: 60%;
  right: 20%;
  width: 60%;
  height: 300px;
  background: rgb(255, 255, 255);
  box-shadow: -10px 10px 20px 0;
  z-index: 2;
  text-align: left;
}
.three-text {
  background-image: url("/public/tree3.png");
  background-clip: text;
  -webkit-background-clip: text;
  color: transparent;
  margin-right: 3rem;
  margin-left: 3rem;
  font-family: "Bowlby One SC", cursive;
  font-size: 8rem;
}
</style>

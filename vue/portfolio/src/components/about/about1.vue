<template>
  <div class="about1-box">
    <div class="about1-text">ABOUT ME</div>
    <p>- name : LEE SI BIN</p>
    <p>- adress : Changwon City</p>
    <p>- phone number : 010-2868-6628</p>
    <p>- email : 010-2868-6628</p>
    <p class="pointer" @click="att()">- Github : https://github.com/leesibin</p>
  </div>
</template>

<script>
/* eslint-disable */
export default {
  name: "app",
  data() {
    return {};
  },
  methods: {
    att() {
      window.location.href = "https://github.com/leesibin";
    },
  },
};
</script>

<style>
.about1-box {
  background-color: #eeeae2;
  width: 100%;
  margin: auto;
  flex: 1;
}
.about1-text {
  font-family: "Bowlby One SC", cursive;
  font-size: 4rem;
  color: #202020;
}
.about1-box p {
  font-family: "Roboto", sans-serif;
  font-size: 2rem;
  text-align: left;
  margin: 3rem;
}
.pointer {
  cursor: pointer;
}
</style>

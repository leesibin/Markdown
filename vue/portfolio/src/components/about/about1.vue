<template>
  <div class="about1-box">
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
  width: 48%;
  margin: auto;
  float: right;
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

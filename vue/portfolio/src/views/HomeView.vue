<template>
  <div class="head-box">
    <top></top>
    <heads></heads>
  </div>
  <div class="about-box">
    <about1></about1>
    <about2></about2>
  </div>
  <div class="skills-box">
    <div class="skills-text">skills</div>
    <skills1></skills1>
  </div>
  <div class="project-box">
    <div class="project-text">project</div>
    <pj1></pj1>
    <pj2></pj2>
    <pj3></pj3>
  </div>
</template>

<script>
/* eslint-disable */
import top from "@/components/head/top.vue";
import heads from "@/components/head/heads.vue";
import about1 from "@/components/about/about1.vue";
import about2 from "@/components/about/about2.vue";
import skills1 from "@/components/skills/skills1.vue";
import pj1 from "@/components/project/pj1.vue";
import pj2 from "@/components/project/pj2.vue";
import pj3 from "@/components/project/pj3.vue";
export default {
  name: "app",
  data() {
    return {};
  },
  methods: {},
  components: {
    top,
    heads,
    about1,
    about2,
    skills1,
    pj1,
    pj2,
    pj3,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
}
li {
  list-style: none;
}
.about-box {
  background-color: #eeeae2;
  width: 100%;
  height: 80vh;
  margin: 0;
  display: flex;
}

.skills-box {
  background-color: #eeeae2;
  width: 100%;
  height: 100vh;
  margin: 0;
}
.skills-text {
  font-family: "Bowlby One SC", cursive;
  font-size: 48px;
  text-align: center;
  color: #202020;
}
.project-box {
  position: relative;
  background-size: cover;
  background-color: #c7a991;
  width: 100%;
  height: 120vh;
  margin: 0;
}
.project-text {
  font-family: "Bowlby One SC", cursive;
  font-size: 48px;
  color: #202020;
}
</style>

<template>
  <div class="main-box">
    <top></top>
    <ohead></ohead>
    <oaboutme></oaboutme>
    <oproject></oproject>
  </div>
</template>

<script>
/* eslint-disable */
import top from "@/components/0top.vue";
import ohead from "@/components/1head.vue";
import oaboutme from "@/components/2aboutme.vue";
import oproject from "@/components/3project.vue";
export default {
  name: "app",
  data() {
    return {};
  },
  methods: {},
  components: {
    top,
    ohead,
    oaboutme,
    oproject,
  },
};
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
}
.main-box {
  /* background-image: url(/public/jang.png); */
  position: relative;
  background-size: cover;
  background-color: wheat;
  width: 100%;
  height: 2000px;
  margin: ;
}
</style>

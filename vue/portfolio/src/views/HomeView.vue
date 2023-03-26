<template>
  <div>home 페이지</div>
  <head></head>
  <aboutme></aboutme>
  <project></project>
</template>

<script>
/* eslint-disable */
import head from "@/components/1head.vue";
import aboutme from "@/components/2aboutme.vue";
import project from "@/components/3project.vue";
export default {
  name: "app",
  data() {
    return {};
  },
  methods: {},
  components: {
    head,
    aboutme,
    project,
  },
};
</script>

<style></style>

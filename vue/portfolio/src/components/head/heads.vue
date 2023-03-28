<template>
  <div class="heads-box1">
    <div class="heads-box2">
      <div class="heads-img2"></div>
    </div>
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
.heads-box1 {
  background-image: url("/public/back.png");
  width: 100%;
  height: 90vh;
  background-size: cover;
  display: flex;
  justify-content: center;
  align-items: center;
}
.heads-box2 {
  background-color: rgba(199, 189, 160, 0.7);
  background: rgba();
  width: 100%;
  height: 90vh;
}

.heads-img {
  position: absolute;
  top: 20%;
  border-radius: 50%;
  width: 500px;
}
.heads-img2 {
  position: absolute;
  top: 20%;
  border-radius: 50%;
  width: 20%;
}
</style>

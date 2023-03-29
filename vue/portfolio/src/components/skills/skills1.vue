<template>
  <div class="skills1-box">
    <div class="chart">
      <div class="chart-bar" data-deg="50"></div>
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

<style>
.skills1-box {
  background-color: #eeeae2;
  width: 100%;
}
/* 원형차트 */
.chart {
  position: relative;
  width: 300px;
  height: 300px;
  border-radius: 50%;
  transition: 0.3s;
  background: lightgray;
  display: inline-block;
}

.chart:after {
  /* 가상선택자는 도넛 모양을 만들기 위함이다.*/
  content: "";
  background: #fff; /* 백그라운드 컬러로 중앙가리기 */
  position: absolute;
  top: 50%;
  left: 50%;
  width: 200px;
  height: 200px; /* 도넛의 너비 설정 */
  border-radius: 50%;
  transform: translate(-50%, -50%);
}
.chart-bar {
  width: inherit;
  height: inherit;
  border-radius: 50%;
  background: conic-gradient(
    #e34f26 45deg,
    #1572b6 45deg 90deg,
    #f7df1e 90deg 135deg,
    #4fc08d 135deg 180deg,
    #339933 180deg 225deg,
    #47a248 225deg 270deg,
    #ff6f00 270deg 325deg,
    #181717 325deg 360deg
  ); /* 차트 설정 */
}
</style>

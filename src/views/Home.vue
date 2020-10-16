<template>
  <div id="app">
    <ClockRow />
  </div>
</template>

<script>
import ClockRow from "../components/ClockRow.vue";

export default {
  name: "App",
  components: {
    ClockRow
  }
};
</script>

<style lang="scss" scoped>
@import "../styles/components/_home.scss";
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>

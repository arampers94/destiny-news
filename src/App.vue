<template>
  <div id="app">
    <img alt="Destiny logo" src="./assets/destiny-2-icon.jpg" />
    <h1>{{ title }}</h1>
  </div>
</template>

<script>
export default {
  name: "app",
  components: {},
  data() {
    return {
      title: "Destiny News"
    };
  },
  methods: {}
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

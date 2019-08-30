// 展示模板
<template>
  <div id="app">
    <h1>{{title}}</h1>
    <p>{{greeting()}}</p>
  </div>
</template>

<script>
export default {
  name: "app",
  data() {
    return {
      title: "this is app.vue"
    };
  },
  methods: {
    greeting() {
      return "Hello Vue.js";
    }
  }
};
</script>

<style>
</style>

<template>
  <div id="app">
    <img alt="Vue logo" src="https://vuejs.org/images/logo.png" width="300" />
    <Input />
  </div>
</template>

<script>
import Input from './components/Input.vue';

export default {
  name: 'App',
  components: {
    Input,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

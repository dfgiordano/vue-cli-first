<template>
  <div id="app">
    <Title />
    <Heroes />
  </div>
</template>

<script>
import Title from './components/Title';
import Heroes from './components/Heroes';

export default {
  name: 'App',
  components: {
    Title,
    Heroes
  }
}
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

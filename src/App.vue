<template>
  <div id="app">
    <Tribute></Tribute>
  </div>
</template>

<script>
import Tribute from './components/tribute/tribute.component';

export default {
  name: 'app',
  components: {
    Tribute
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

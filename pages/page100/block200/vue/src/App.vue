<template>
  <div id="app">
  this is a test using the clone command
now push it back

using eclipse!

done
    <version></version>
    <hello></hello>
  </div>

</template>

<script>
import Hello from './components/Hello'
import Version from './myshop/Version'

export default {
  name: 'app',
  components: {
    Hello, Version
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

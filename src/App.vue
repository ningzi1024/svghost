<template>
  <div id="app">
    <Home></Home>
  </div>
</template>

<script>
import Home from './pages/home'

export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

<style>
#app,html,body {
  width: 100%;
  height: 100%;
  margin: 0;
  padding: 0;
}
</style>

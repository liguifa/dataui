<template>
  <div id="app">
    <data-line></data-line>
  </div>
</template>

<script>
import Line from './components/Line.vue'

export default {
  name: 'app',
  components: {
    "data-line":Line
  }
}
</script>

<style>
  html,body,#app{
    width:100%;
    height: 100%;
  }
</style>
<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/image.gif">
    <Location />
  </div>
</template>

<script>
import Location from './components/Location.vue'

export default {
  name: 'app',
  components: {
    Location
  }
}
</script>

<style>
  #app {
    text-align: center;
    height: 100%;
    margin: 0;    
    background-color: black;
  }
</style>
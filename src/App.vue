<template>
  <div id="app">
    <app-header></app-header>
    <router-view class="container"/>
    <App-Lat></App-Lat>
  </div>
</template>

<script>

import AppHeader from '@/components/AppHeader'
import AppLat from '@/components/AppLat'
export default {
  name: 'App',
  components:{
    AppHeader,
    AppLat
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
}
</style>

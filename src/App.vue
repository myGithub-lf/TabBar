<template>
  <div id="app">
    <router-view/>
    <main-tab-bar/>
  </div>
</template>

<script>
import MainTabBar from './components/MainComponents/MainTabBar.vue'
export default {
   name: "App",
   components: {
      MainTabBar
   }
}
</script>

<style>
   @import url('./assets/css/base.css');
</style>

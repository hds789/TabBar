<template>
  <div id="app">
    <router-view></router-view>
    <mainTabBar/>
  </div>
</template>

<script>
import mainTabBar from 'components/mainTabBar/mainTabBar'
export default {
  name: 'App',
  components: {
    mainTabBar
  }
}
</script>

<style>
@import "assets/css/base.css";
</style>

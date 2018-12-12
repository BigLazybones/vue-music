<template>
  <div id="app">
    <m-header></m-header>
    <tab></tab>
    <router-view></router-view>
  </div>
</template>

<script>
import MHeader from './components/m-header'
import Tab from './components/tab'

export default {
  name: 'App',
  components: {
    'm-header': MHeader,
    'tab': Tab
  }
}
</script>

<style>
</style>

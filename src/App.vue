<template>
<div id="app">
    <action-sheet></action-sheet>
  </div>
</template>

<script>
import ActionSheet from './components/ActionSheet'

export default {
  name: 'App',
  components: {
    ActionSheet
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

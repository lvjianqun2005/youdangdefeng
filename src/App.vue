<template>
<div id="app">
    <Search></Search>
  </div>
</template>

<script>
import Search from './components/Search'

export default {
  name: 'App',
  components: {
    Search
  }
}
</script>

<style>
@import './style/reset.css';
html{
     background: rgb(0,0,0,0.5);
}
</style>

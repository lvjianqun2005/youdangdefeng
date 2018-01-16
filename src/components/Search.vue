<template>
    <div id="search">{{msg}}
        <div class="search">
           <div class="search_input">
             <div></div>
           </div>
        </div>
    </div>
</template>

<script type="text/ecmascript-6">
export default {
  name: 'Search',
  data () {
    return {
      msg: '你好 勇士'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>

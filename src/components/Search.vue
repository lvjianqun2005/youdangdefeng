<template>
    <div id="search">
        <div class="search">
           <div class="search_input">
             <img src="./../assets/icon-search.png" alt="" />
                  <form @submit.prevent="search(key)">
                       <input type="text" placeholder="搜索 歌曲/专辑/歌手"  @focus="focus()">
                  </form>
           </div>
                  <div class="search_cancel">
                                                 取消
                  </div>
        </div>
        <div class="hotkey">
            <div class="search_hisotry">
                  <div class="search_hisotry_item">说散就散</div>
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
.search{
   width: 100%;
   height: 60px;
   display: flex;
   flex-direction:row;
   -webkit-flex-direction:row;
   position: fixed;
   top: 0;
   background:#ffffff;
   z-index: 1;
}
.search_input{
    width: 100%;
    background: #eeeeee;
    border-radius:10px;
    margin:10px;
    display: flex;
    -webkit-flex-direction:row;
    align-items:center;
    -webkit-align-items:center;
}
.search_input img{
    width: 30px;
    height: 30px;
    display:inline-block;
    margin: 0 5px;
}
.search_input form,
.search_input input{
    width: 100%;
    height: 100%;
    border: none;
    background: #eeeeee;
    font-size: medium;
    flex-grow: 1;
    border-radius:5px;
    outline: none;
}
.search_cancel{
    height: 40px;
    width: 55px;
    margin: 10px auto;
    line-height: 40px;
    overflow: hidden;
    transition: width 0.3s;
    cursor: pointer;
}
.search_cancel_show{
    width: 55px;
}
.hotkey{
    margin: 60px 0 50px 0;
    background: #eeeeee;
    display: flex;
    flex-direction:column;
}
.search_hisotry{
    display:flex;
    flex-wrap:wrap;
    background: #ffffff;
    padding: 0 10px ;
    max-height: 66px;
}

</style>

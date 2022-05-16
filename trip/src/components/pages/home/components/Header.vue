<template>
  <div class="header">
      <div class="header-left">
          <span class="iconfont back-icon back-icon1 ">&#xe658;</span>
       </div>
      <div class="header-input">
            <span class="iconfont back-icon">&#xe63c;</span>
          输入城市/景点/游玩主题</div>
      <div class="header-right">
          城市
           <span class="iconfont back-icon">&#xe65c;</span>
          </div>
  </div>
</template>

<script>
export default {
    name:'HomeHeader'
}
</script>

<style scoped>
.header{
    display:flex;
    height:54px;
    line-height:54px;
    background:#00bcd4;
    color:white;
    margin-top:-60px ;
}
.header-input{
    flex:1;
    background:#fff;
    color:#666;
    border-radius:5px;
    margin:10px 30px 5px 8px ;
    font-size: 16px;
    height:34px;
    line-height:34px;
   
}
.header-left{
    float:left;
    width:46px;   
}
.header-right{
    float:right;
    margin-right: 12px;
    font-size: 16px;
}
.header .back-icon{
    display: inline-block;
    font-size: 22px;
    margin-bottom: 4px;
}
.header .back-icon1{
    font-size: 30px;
}
/* .header .back-icon:nth-child(2){
    font-size: 30px;
} */
</style>
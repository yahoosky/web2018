<template>
  <div>
    <el-container class="container">
        <el-header class="header">
        
        </el-header>
      <el-container class="container2">
        <el-aside class="asider">
          

        </el-aside>
        <el-main class="main">
          

        </el-main>
      </el-container>   
        
    </el-container>   

  </div>
</template>
<script>
export default {
  data () {
    return {}
  }
}
</script>
<style lang="scss" scoped>
  .container{
    background:gray;
    .header{
      padding:0;
      margin:0;
      height: 60px;
      background:pink;
    }
    .container2{
      position:absolute;
      top:60px;
      bottom:0;
      left: 0;
      right: 0;
    }
    .asider{
      background:lightblue;
      position: absolute;
      top:0px;
      bottom:0px;
      left: 0px;
      width:300px;
    }
    .main{
      background: lightcyan;
      position: absolute;
      top:0;
      left: 300px;
      right: 0;
      bottom:0;
    }
  }
</style>

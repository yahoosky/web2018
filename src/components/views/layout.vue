<template>
  <div class="left-nav">
    <ul>
        <li>
            <i class="icon iconfont icon-feiyong"></i>
            <div>收银</div>
        </li>
         <li>
            <i class="icon iconfont icon-shouye"></i>
            <div>店铺</div>
        </li>
         <li>
            <i class="icon iconfont icon-zhuanshi"></i>
            <div>商品</div>
        </li>
         <li>
            <i class="icon iconfont icon-VIPhuiyuan"></i>
            <div>会员</div>
        </li>
        <li>    
            <i class="icon iconfont icon-tongji"></i>
            <div>统计</div>
        </li>
        <li>    
            <i class="icon iconfont icon-shezhi"></i>
            <div>设置</div>
        </li>
    </ul>
  </div>
</template>
<script>
    export default {
      name: 'leftNav'
    }
</script>
<style lang="scss">
    .left-nav{
        color: #fff;
        font-size: 10px;
        height: 100%;
        background-color: #1DBCf0;
        float: left;
        width: 5%;
        .iconfont{
           font-size:24px; 
        }
        ul{
            padding: 0px;
            margin: 0px;
        }
        li{
            list-style-type: square none;
            text-align: center;
            border-bottom: 1px solid #20a0ff;
            padding: 10px;
        }
    }
</style>

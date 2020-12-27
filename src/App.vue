<template>
  <div id="app">
    <router-view></router-view>
    <h1>头条项目</h1>
    <div>
      <i class="toutiao toutiao-dianzan2"></i>
    </div>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="info">信息按钮</van-button>
    <van-button type="default">默认按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
    <van-button type="danger">危险按钮</van-button>
    <div class="box"></div>
  </div>
</template>
<script>
  export default {
    name: 'App'
  }
</script>
<style lang="less">
  .box {
    width: 750px;
    height: 60px;
    background-color: pink;
  }
</style>

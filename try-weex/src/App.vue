<template>
  <div class="app-wrapper">
    <router-view></router-view>
    <!--<div class="wrapper">
      <text>index</text>
    </div>-->
    <!-- <home-header></home-header>
    <top-channel></top-channel>
    <tab-bar></tab-bar> -->
  </div>
</template>

<style>
  /* body{
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333333;
  } */
</style>
<style scoped>
.app-wrapper{
        background-color: #f4f4f4;
    }
    .r-box{
        position: absolute;
        top:0;
        left: 0;
        right: 0;
        bottom: 0;
    }
  /* .app-wrapper{
    background-color: #f4f4f4;
  }
  .r-box{
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
  } */
</style>

<script>
  // import tabBar from './assets/components/tabBar.vue';
  // import Header from './assets/components/Header.vue';
  // import util from './assets/components/util.js';
  // import TopChannel from './assets/components/TopChannel.vue'
  // export default {
  //   // 组件
  //   "components":{
  //     'home-header':Header,
  //     'tab-bar': tabBar,
  //     'top-channel': TopChannel

  //   },
  //   //生命周期，组件创建
  //   created () {
  //     util.initIconFont();
  //   },
  //   data: {
     
  //   },
  //   methods: {
     
  //   }
  // }
</script>

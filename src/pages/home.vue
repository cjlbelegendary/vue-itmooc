<template>
  <div class="w-full ">
    <!-- 海报图 -->
    <img 
      class="w-full"
      src="@/assets/images/ad.png"
    >
    <!-- 头部导航 -->
    <div class="shadow mb-[10px]">
      <div class="w-[1200px] mx-auto">
        <Header></Header>
      </div>
    </div>
    <!-- 主要内容 -->
    <div class="w-[1200px] mx-auto mt-4 mb-4">
      <div class="flex items-center justify-between">
        <!-- 分类导航 -->
        <!-- 轮播图 -->
        <!-- 新人福利 -->
      </div>
      <!-- 高单价导航 -->
      <!-- 课程分类导航 -->
    </div>
    <!-- 底部的内容导航 -->
  </div>
  <!-- 提醒登录浮层组件 -->
</template>

<script lang='ts' setup name='Home'>
  import {useUserStore} from '@/stores/user.js'
  import Header from '@/components/Header.vue'
  const user=useUserStore()
</script>

<style scoped>
  
</style>
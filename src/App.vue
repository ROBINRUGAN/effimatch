<script setup lang="ts">
import { RouterView } from 'vue-router'
import SideBar from '@/components/SideBar.vue'
</script>

<template>
  <el-container>
    <el-header>基于可编程数据平面的智能数据包分类与梯度聚合优化系统</el-header>
    <el-container>
      <el-aside width="fit-content">
        <SideBar />
      </el-aside>
      <el-main> <router-view /></el-main>
    </el-container>
  </el-container>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Microsoft YaHei', Arial, sans-serif;
}
</style>
<style scoped>
.el-header {
  background-color: rgb(42, 107, 168);
  color: #ffffff;
  text-align: center;

  display: flex;
  justify-content: center;
  align-items: center;
  box-shadow: 0 2px 1px 1px rgba(0, 0, 0, 0.2);
  margin-top: -2px;
  border: 1px solid #ebeef5;
  font-size: 24px;
  font-weight: bold;
  border-bottom-left-radius: 40px;
  border-bottom-right-radius: 40px;
  z-index: 2;
  padding: 30px 0px 30px 0;
}

.el-aside {
  background-color: #ffffff;
  color: #333;
  text-align: center;
  line-height: 200px;
  height: 100%;
  border-radius: 10px;
  margin-top: 10px;
}

.el-main {
  background-color: #f6faff;
  color: #333;
  text-align: center;
  height: 100%;
}
.el-container {
  height: 100%;
  overflow: hidden;
}
</style>

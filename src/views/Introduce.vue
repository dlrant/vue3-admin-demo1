<template>
  <el-card class="account-container">
    <h1>系统简介</h1>
    <div style="line-height: 30px">
      vue3-admin 是一套企业级后台管理系统，基于 Vue 3.0 相关技术栈开发，供各位开发者们体验和学习，一定给你最好的学习体验。
    </div>

    <h1>开发及部署文档</h1>

    <ul class="course" @click="goJuejin">
      <li>开篇词：通关Vue3.0 项目开发，升职</li>

      <li>后端 API 项目启动和运行注意事项</li>
    </ul>

    <h1>技术选型</h1>
    <ul style="font-weight: bold;">
      <li>Vue 3.x</li>
      <li>Vite 2.x</li>
      <li>Vue-Router 4.x</li>
      <li>Element-Plus（适配全新 Vue 3.x 的 PC 端组件库）</li>
      <li>Echarts 5.0</li>
      <li>axios</li>
      <li>wangEditor</li>
    </ul>

  </el-card>
</template>

<script setup>
const goJuejin = () => {
  console.log('goJuejin')
  window.open('https://xxxx', 'target')
}
</script>
<style scoped>
  .course {
    font-weight: bold;
    display: inline-block;
  }
  .course li {
    line-height: 36px;
    color: #409eff;
    cursor: pointer;
  }
</style>

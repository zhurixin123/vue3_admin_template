<template>
  <div>
    <el-button type="primary" size="default" :icon="Plus">Primary</el-button>
    <el-button type="success" size="small" :icon="Edit">编辑按钮</el-button>
    <el-button type="danger" size="default" :icon="Delete">删除按钮</el-button>
  </div>
  <div class="demo-pagination-block">
    <div class="demonstration">Jump to</div>
    <el-pagination layout="prev, pager, next, jumper" :total="1000" />
    <Test />
  </div>
</template>

<script setup lang="ts">
// 引入图标组件
import { Plus, Edit, Delete } from '@element-plus/icons-vue'
import Test from '@/components/Test.vue'
</script>

<style scoped></style>

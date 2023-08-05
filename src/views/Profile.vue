<template>
  <div class="profile">
    <el-card class="box-card">
      <template #header>
        <div class="card-header">
          <span>个人简介</span>
        </div>
      </template>
      <div class="text item">
        email: xiong_canyang@163.com
      </div>
      <div class="text item">
      </div>
    </el-card>
  </div>
</template>

<script setup lang="ts">
import Profile from '../components/profile/index.vue'
</script>

<style lang="less" scoped>
.profile {
  width: 90%;
  height: 100%;
  .el-card {
    height: 100%;
  }
}
</style>

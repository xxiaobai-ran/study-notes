<template>
  <div class="common-layout">
    <el-container>
      <el-aside width="200px">
        <Aside/>
      </el-aside>
      <el-main>Main</el-main>
    </el-container>
  </div>
</template>

<script setup lang="ts">
    import Aside from '@/components/aside/index.vue'
</script>

<style lang="less" scoped>
.common-layout{
    width: 100%;
    height: 100%;
}
</style>

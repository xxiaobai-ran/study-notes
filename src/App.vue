<template>
  <Header />
  <div class="content">
    <RouterView />
  </div>
</template>

<script setup lang="ts">
import Header from '@/components/header/index.vue'

import { RouterView } from 'vue-router'
</script>

<style scoped lang="less">
.content{
    width: 100%;
    height: calc(100% - 155px);
    display: flex;
    justify-content: center;
}
</style>

<template>
  <!-- 蒙层阴影 -->
  <div class="taper-line"></div>
  <div class="header__nav">
    <div class="header__nav_left">
      <ul>
        <li v-for="(tab, index) in NAV" :key="index">
          <span>{{ tab.text }}</span>
        </li>
      </ul>
    </div>
  </div>
</template>

<script setup lang="ts">
import './index.less'
import { NAV } from '@/const/nav'
</script>

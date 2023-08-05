<template>
  <!-- 蒙层阴影 -->
  <div class="taper-line"></div>
  <div class="header__nav">
    <div class="header__nav_left">
      <ul>
        <li v-for="(tab, index) in NAV" :key="index" @click="handleGo(tab.src)">
          <span>{{ tab.text }}</span>
        </li>
      </ul>
    </div>
    <div class="header__nav_right">
      <div class="avatar">
        <el-avatar
          src="https://himg.bdimg.com/sys/portrait/item/wise.1.2d0aaf8b.WMxcT04ZUrONpHBQiuIHnQ.jpg?time=5992&tieba_portrait_time=5992"
          @click="handleGo('/profile')"
        />
      </div>
      <div class="profile" @click="handleGo('/profile')">admin</div>
    </div>
  </div>
</template>

<script setup lang="ts">
import router from '@/router'
import './index.less'
import { NAV } from '@/const/nav'


const handleGo = (src: string) => {
  router.push(src)
}
</script>

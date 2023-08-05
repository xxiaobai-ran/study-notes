<template>
    <div class="header">
        <HeaderAnimation/>
        <HeaderNav/>
    </div>
    <Content/>
</template>

<script setup lang="ts">
import HeaderAnimation from '../header-animation/index.vue'
import HeaderNav from '../header-nav/index.vue'
import Content from '../content/index.vue'
import './index.less'

</script>

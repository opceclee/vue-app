<template>
  <div id="app">
    <m-header></m-header>
    <tab></tab>
    <recommend></recommend>
    <router-view></router-view>
  </div>
</template>

<script>
import MHeader from '@/components/m-header/m-header'
import Tab from '@/components/tab/tab'
import Recommend from '@/components/recommend/recommend'
export default {
  components: {
    MHeader,
    Tab,
    Recommend
  }
}
</script>

<style lang="stylus" scoped>
</style>

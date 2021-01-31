<template>
  <div>
    <home-header></home-header>
    <home-swiper></home-swiper>
    <home-icons></home-icons>
    <recommend></recommend>
  </div>
</template>
<script>
import HomeHeader from './components/Header.vue'
import HomeSwiper from './components/Swiper.vue'
import HomeIcons from './components/Icons.vue'
import Recommend from './components/Recommend'
export default{
  name: 'home',
  components: {
    HomeHeader,
    HomeSwiper,
    HomeIcons,
    Recommend
  }
}
</script>
<style scoped>
</style>

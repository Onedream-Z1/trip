<template>
  <div>
      <home-header></home-header>
      <home-swiper></home-swiper>
      <home-icons></home-icons>
  </div>
</template>

<script>
import HomeHeader from '@/components/pages/home/components/Header'
import HomeSwiper from '@/components/pages/home/components/Swiper'
import HomeIcons from '@/components/pages/home/components/Icons'
export default {
    name:'Home',
    components:{
      HomeHeader,
      HomeSwiper,
      HomeIcons
    }
}
</script>

<style scoped>

</style>
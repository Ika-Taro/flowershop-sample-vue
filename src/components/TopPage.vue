<template>
  <section class="top-page">
    <HomeHero/>
    <AppHeader/>
    <ShopInfo/>
    <AboutMe/>
    <ShopWorks/>
  </section>
</template>
<script>
import HomeHero from './HomeHero.vue'
import AppHeader from './AppHeader.vue'
import ShopInfo from './ShopInfo.vue'
import AboutMe from './AboutMe.vue'
import ShopWorks from './ShopWorks.vue'

export default {
  components: {
    HomeHero,
    AppHeader,
    ShopInfo,
    AboutMe,
    ShopWorks,
  }
}
</script>
<style lang="scss" scoped>
.top-page {
  padding-bottom: 50px;
}
</style>
<template>
  <section class="top-page">
    <HomeHero/>
    <AppHeader/>
    <ShopInfo/>
    <AboutMe/>
    <ShopWorks/>
    <ShopContact/>
    <ShopMap/>
  </section>
</template>
<script>
import HomeHero from './HomeHero.vue'
import AppHeader from './AppHeader.vue'
import ShopInfo from './ShopInfo.vue'
import AboutMe from './AboutMe.vue'
import ShopWorks from './ShopWorks.vue'
import ShopContact from './ShopContact.vue'
import ShopMap from './ShopMap.vue'

export default {
  components: {
    HomeHero,
    AppHeader,
    ShopInfo,
    AboutMe,
    ShopWorks,
    ShopContact,
    ShopMap,
  }
}
</script>

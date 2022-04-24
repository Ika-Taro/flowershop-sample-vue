<template lang="pug">
div
  .slide-outer
    transition(name="fade")
      .slide-inner(v-for="(slide, idx) in slides" v-if="currentSlide == idx" :key="idx")
        img.slide-img(:src="slides[idx].img")
    .hero-logo
      img.hero-logo-img(src= "../assets/flowershoplogo.jpg")
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component({
})

export default class SlideShow extends Vue {
  private currentSlide = 0
  private slides = [
    { img: require('@/assets/flowershop-hero1.jpg') },
    { img: require('@/assets/flowershop-hero2.jpg') },
  ]
  private fade = 'next'
  private show = true
  private timer = 0

  created () {
    this.$nextTick(() => {
      this.timer = setInterval(() => {
        this.autoPlay()
      }, 7000)
    })
  }

  autoPlay () {
    this.currentSlide++
    if (this.currentSlide === this.slides.length) {
      this.currentSlide = 0
    }
  }
}
</script>

<style lang="stylus">

.slide-outer
  position relative
  overflow hidden
  width 100vw
  height 100vh
  display flex

.slider-inner
  position absolute
  width 100vw
  height 100vh

.slide-img
  width 100vw
  height 100vh
  object-fit cover

.fade-enter-active
  transition all 1s ease

.fade-leave-active
  transition all 1s ease
  position absolute

.fade-enter
.fade-leave-to
  opacity 0

.hero-logo 
  position absolute
  top 50%
  left 50%
  transform translate(-50%, -50%)
  height 200
  width 200


</style>
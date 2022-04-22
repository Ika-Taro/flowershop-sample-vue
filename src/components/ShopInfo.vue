<template lang="pug">
  section.home-about
    v-container.section__title
      .section__title-text Information
    v-container
      v-row.home-about__contents
        <v-col sm="6" class="home-about__contents-img">
          <v-img src="../assets/flowershop-shop.jpg" alt="shopimage" class="img-fluid"></v-img>
        </v-col>
        <v-col sm="6" class="home-about__contents-text">
          p XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
          p XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
        </v-col>
</template>

<style lang="stylus">

.section__title 
  text-align center
  font-weight bold
  padding 15px
  border-bottom 2px solid black

.home-about__contents
  margin-top 20px
  justify-content center

  img 
    text-align center

  p 
    word-wrap break-word

.img-fluid 
  max-width 100%
  height auto

</style>
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
          <p>吾輩は猫である。名前はまだ無い。どこで生れたかとんと見当がつかぬ。何でも薄暗いじめじめした所でニャーニャー泣いていた事だけは記憶している。吾輩はここで始めて人間というものを見た。しかもあとで聞くとそれは書生という人間中で一番獰悪な種族であったそうだ。この書生というのは時々我々を捕えて煮て食うという話である。</p>
          <p>しかしその当時は何という考もなかったから別段恐しいとも思わなかった。</p>
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
<template lang="pug">
  section.home-about
    v-container
      .section-text information
    v-container
      v-row.home-about__contents
        <v-col sm="6" class="home-about__contents-img">
          <v-img src="../assets/flowershop-shop.jpg" alt="shopimage" class="img-fluid"></v-img>
        </v-col>
        <v-col sm="6" class="explanation-note" >
          p 吾輩は猫である。名前はまだ無い。どこで生れたかとんと見当がつかぬ。何でも薄暗いじめじめした所でニャーニャー泣いていた事だけは記憶している。吾輩はここで始めて人間というものを見た。しかもあとで聞くとそれは書生という人間中で一番獰悪な種族であったそうだ。この書生というのは時々我々を捕えて煮て食うという話である。しかしその当時は何という考もなかったから別段恐しいとも思わなかった。
        </v-col>
</template>

<style lang="stylus" scoped>

.home-about__contents
  margin-top 20px
  justify-content center

  img 
    text-align center

.img-fluid 
  max-width 100%
  height auto


</style>
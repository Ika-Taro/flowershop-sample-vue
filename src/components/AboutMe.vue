<template lang="pug">
div
  v-container.contact
      p.contact-text contact/access
  v-container
    v-card
      v-row
        <v-col cols="12" sm="6">
          <v-card-title class="text-h5" text="item.title">owner</v-card-title>
            v-card-subtitle.card-text
              <p>木曾路はすべて山の中である。あるところは岨づたいに行く崖の道であり、あるところは数十間の深さに臨む木曾川の岸であり、あるところは山の尾をめぐる谷の入り口である。一筋の街道はこの深い森林地帯を貫いていた。東ざかいの桜沢から、西の十曲峠まで、木曾十一宿はこの街道に添うて、二十二里余にわたる長い谿谷の間に散在していた。道路の位置も幾たびか改まったもので、古道はいつのまにか深い山間に埋もれた。</p>
        </v-col>
      
        <v-col cols="12" sm="6">
          <v-img class="owner-image" src="../assets/flowershop-owner.jpg" height="100%"></v-img>
        </v-col>
</template>

<style lang="stylus">

.card-text
  word-break break-word

</style>
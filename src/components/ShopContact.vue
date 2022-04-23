<template lang="pug">
div#contact_access
  v-container
    p.section-text contact/access
  v-container.box-ilb
    v-row
      <v-col cols="12" sm="6" class="lib-lm explanation-note">
        p FlowerShopTaro
          br
          | 000-0000 青森県八戸市XXXXXXXXXXXXXXXXXXXXXX
          br
          | TEL : 000-000-0000
          br
          | 駐車場 4台
          br 
          | 営業時間 10:00～18:00
          br
          | 定休日 月曜日
          br
          | 日曜日までにご予約いただきました商品のお引き渡し・配達・お打ち合わせは行っております。
          br
          | *前日までのご予約に限り、配達のみ対応
          br
          |*定休日の月曜日は、ご予約の配達業務のみ対応致します
        </v-col>
      <v-col cols="12" sm="6" class="lib-rm explanation-note">
        p.shop-info お花やサービス、お店に関するご質問やご不明点などは、
          br
          | お電話、もしくはFAXよりお気軽にお問い合わせください。
          br
          | 各種ご注文や商品のご相談も受け付けております。
          br
          | 注文を受付後に、お支払いなどの詳細内容はご連絡させて頂きます。
      </v-col>
</template>

<style lang="stylus" scoped>

.lib-lm
  padding 40px
  @media screen and (max-width: 600px) {
    text-align center
    border-bottom 1px solid black
  }

.lib-rm
  padding 40px
  @media screen and (min-width: 600px) {
  border-left 1px solid black
  }

</style>
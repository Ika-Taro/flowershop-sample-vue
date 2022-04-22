<template>

  <section class="home-about">
    <div class="section__title">
      <div class="section__title-text">Information</div>
    </div>
    <v-container>
      <v-row class="home-about__contents">
        <v-col sm="6" class="home-about__contents-img">
          <v-img src="../assets/flowershop-shop.jpg" alt="shopimage" class="img-fluid"></v-img>
        </v-col>
        <v-col sm="6" class="home-about__contents-text">
          <p>XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX</p>
          <p>XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX</p>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>
<style lang="scss" scoped>
.section__title {
  margin-top: 30px;
  text-align: center;

  &-text {
    font-weight: 700;
    font-size: 40px;
    color: #e65f78;
  }
}
.home-about__contents {
  margin-top: 20px;
  justify-content: center;

  &-img {
    text-align: center;
  }

  &-text {
    word-wrap: break-word;
  }
}
.img-fluid {
  max-width: 100%;
  height: auto;
}
</style>
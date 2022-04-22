<template>
  <v-container>
    <v-card>
      <v-row>
        <v-col cols="12" sm="6">
          <v-card-title
            class="text-h5"
            text="item.title"
          >owner</v-card-title>
          <v-card-subtitle class="card-text">
            <p>
              XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
              <br>
              XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
              </p>
          </v-card-subtitle>
        </v-col>
      
        <v-col cols="12" sm="6">
          <v-img
          class="owner-image"
          src="../assets/flowershop-owner.jpg"
          height="100%"
          ></v-img>
        </v-col>
      </v-row>
    </v-card>
  </v-container>
</template>
<style lang="scss" scoped>
.card-text {
  word-break: break-word;
}

</style>
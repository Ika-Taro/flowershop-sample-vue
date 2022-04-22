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
              p XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                br
                | XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
        </v-col>
      
        <v-col cols="12" sm="6">
          <v-img class="owner-image" src="../assets/flowershop-owner.jpg" height="100%"></v-img>
        </v-col>
</template>

<style lang="stylus">

.card-text
  word-break break-word

</style>
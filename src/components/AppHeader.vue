<template lang="pug">
  <v-toolbar dark class="toolbar">
    .toolbar-title Flower Shop Taro

    v-spacer

    <v-btn id="access-btn" text>Access</v-btn>

    <v-btn href="https://www.instagram.com">
      <v-icon>mdi-instagram</v-icon>
    </v-btn>

  </v-toolbar>
</template>

<style lang="stylus" scoped>

.toolbar-title
  font-family: 'Square Peg', cursive;
  margin-left 8px
  font-size 30px
  font-weight bold

</style>
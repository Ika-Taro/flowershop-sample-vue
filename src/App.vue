<template>
  <v-app>
    <v-main>
      <v-content>
        <TopPage/>
      </v-content>
      <AppFooter/>
    </v-main>
  </v-app>
</template>

<script>
import TopPage from './components/TopPage.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  name: 'App',

  components: {
    TopPage,
    AppFooter,
  },

  data: () => ({
    //
  }),
}
</script>

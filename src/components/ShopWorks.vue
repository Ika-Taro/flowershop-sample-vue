<template lang="pug">
div
  v-container.contact
    p.contact-text contact/access
  v-container
    <v-carousel show-arrows-on-hover>
      .carousel-item
        <v-carousel-item v-for="(item,i) in items" :key="i" :src="item.src" reverse-transition="fade-transition" transition="fade-transition">
        </v-carousel-item>
    </v-carousel>
</template>


<script>
  export default {
    data () {
      return {
        items: [
          {
            src: require('@/assets/flowershop-slide1.jpg'),
          },
          {
            src: require('@/assets/flowershop-slide2.jpg'),
          },
          {
            src: require('@/assets/flowershop-slide3.jpg'),
          },
          {
            src: require('@/assets/flowershop-slide4.jpg'),
          },
        ],
      }
    },
  }
</script>


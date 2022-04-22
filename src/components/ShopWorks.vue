<template>
  <v-container>
    <v-carousel
    show-arrows-on-hover
    cycle
    >
      <div class="carousel-item">
        <v-carousel-item 
          v-for="(item,i) in items"
          :key="i"
          :src="item.src"
          reverse-transition="fade-transition"
          transition="fade-transition"
        ></v-carousel-item>
      </div>
    </v-carousel>
  </v-container>
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


<template lang="pug">
  <v-container>
    <div ref="map" style="height:500px;width:100%;"></div>
  </v-container>
</template>
<script>
export default {
  data() {
    return {
      myLatLng: { lat: -34.397, lng: 150.644 },
    };
  },
  mounted() {
    let timer = setInterval(() => {
      if (window.google) {
        clearInterval(timer);
        const map = new window.google.maps.Map(this.$refs.map, {
          center: this.myLatLng,
          zoom: 8,
        });
        new window.google.maps.Marker({
          position: this.myLatLng,
          map,
        });
      }
    }, 500);
  },
};
</script>
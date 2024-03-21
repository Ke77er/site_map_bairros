<template>
  <section id="section-map">
    <div id="map"></div>
  </section>
</template>

<script>
export default {
  name: "SectionMap",
  mounted() {
    this.initMapbox();
  },
  methods: {
    async initMapbox() {
      const response = await fetch(
        'https://api.maptiler.com/maps/basic-v2/style.json?key=49RUadURGLXgj0A7AWfo'
      );
      try {
        if (!response.ok) throw Error(response.statusText);
        const style = await response.json();
        const map = new mapboxgl.Map({
          container: 'map',
          style: style,
          zoom: 11,
          center: [-48.8461, -26.3051],
        });
      } catch (error) {
        console.error({ error });
      }
    },
  },
};
</script>

<style scoped>
@import url('https://api.tiles.mapbox.com/mapbox-gl-js/v0.49.0/mapbox-gl.css');

#map {
  top: 0;
  left: 0;
  width: 80%;
  height: 100vh;
}
</style>

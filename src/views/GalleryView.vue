
<template>
  
  <div class="gallery">
    <Gallery></Gallery>
  </div>
</template>

<script>
import Gallery from '../components/Gallery.vue'

export default {
  name: 'GalleryVue',
  components: {
    Gallery
  }
  }
</script>

<style scoped>
@media (min-width: 1024px) {
  .gallery {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>

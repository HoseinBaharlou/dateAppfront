<template>
  <v-container class="mt-75">
    <!-- start our gallery -->
    <OurGallery/>
    <!-- end our gallery -->

    <!-- start gallery -->
    <Gallery class="mt-140"/>
    <!-- end gallery -->
  </v-container>
</template>

<script>
import OurGallery from '../components/partials/Gallery/OurGallery.vue'
import Gallery from '../components/partials/Gallery/photoGallery.vue'
export default {
  setup() {
    
  },
  components:{Gallery,OurGallery}
}
</script>

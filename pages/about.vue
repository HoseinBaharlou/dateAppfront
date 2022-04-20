<template>
  <v-container class="mt-14">
    <!-- start header -->
    <Header/>
    <!-- end header -->

    <!-- start about company -->
    <about-company class="mt-140"/>
    <!-- end about company -->

    <!-- start photo ghalery -->
    <photo-ghalery class="mt-140" />
    <!-- start photo ghalery -->

    <!-- start global food -->
    <global-food class="mt-110"/>
    <!-- end global food -->

    <!-- start farmer -->
    <farmer/>
    <!-- end farmer -->
  </v-container>
</template>

<script>
import Header from '../components/partials/about/header.vue'
import aboutCompany from '../components/partials/about/aboutCompany.vue'
import PhotoGhalery from '../components/partials/about/photoGallery.vue'
import GlobalFood from '../components/partials/about/GlobalFood.vue'
import farmer from '../components/partials/about/Farmer.vue'
export default {
  setup() {
    
  },
  components:{Header,aboutCompany,PhotoGhalery,GlobalFood,farmer},
  layout:'default'

}
</script>

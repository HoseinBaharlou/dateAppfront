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
  </v-container>
</template>

<script>
import Header from '../components/partials/about/header.vue'
import aboutCompany from '../components/partials/about/aboutCompany.vue'
import PhotoGhalery from '../components/partials/about/photoGhalery.vue'
import GlobalFood from '../components/partials/about/GlobalFood.vue'
export default {
  setup() {
    
  },
  components:{Header,aboutCompany,PhotoGhalery,GlobalFood},
  layout:'default'

}
</script>

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
  </v-container>
</template>

<script>
import Header from '../components/partials/about/header.vue'
import aboutCompany from '../components/partials/about/aboutCompany.vue'
import PhotoGhalery from '../components/partials/about/photoGhalery.vue'
export default {
  setup() {
    
  },
  components:{Header,aboutCompany,PhotoGhalery},
  layout:'default'

}
</script>

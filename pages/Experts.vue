<template>
  <v-container class="mt-75">
    <!-- start header -->
    <Header/>
    <!-- end header -->

    <!-- start our farmers -->
    <OurFarmers class="mt-135"/>
    <!-- end our farmers -->

    <!-- start farmer -->
    <Farmer/>
    <!-- end farmer -->
  </v-container>
</template>

<script>
import Header from '../components/partials/Experts/header.vue'
import OurFarmers from '../components/partials/Experts/ourFarmers.vue';
import Farmer from '../components/partials/Experts/Farmer.vue'
export default {
  setup() {
    
  },
  components:{Header,OurFarmers,Farmer}
}
</script>

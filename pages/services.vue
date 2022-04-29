<template>
  <v-container class="mt-75">
    <!-- start header -->
    <Header />
    <!-- end header -->

    <!-- start service -->
    <service/>
    <!-- end service -->
  </v-container>
</template>
<script>
import Header from '../components/partials/services/header.vue'
import service from '../components/partials/services/service.vue'
export default {
  setup() {
    
  },
  components:{Header,service}
}
</script>

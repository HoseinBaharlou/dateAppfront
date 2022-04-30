<template>
  <v-container class="mt-75">
    <!-- start header -->
    <Header/>
    <!-- end header -->
    <!-- start FAQs -->
    <FAQs class="mt-140"/>
    <!-- end FAQs -->
  </v-container>
</template>

<script>
import Header from '../components/partials/FAQs/header.vue'
import FAQs from '../components/partials/FAQs/FAQs.vue'
export default {
  setup() {
    
  },
  components:{Header,FAQs}
}
</script>

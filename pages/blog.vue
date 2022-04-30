<template>
  <v-container class="mt-75">
    <!-- start header -->
    <Header/>
    <!-- end header -->

    <!-- start News -->
    <News class="mt-140"/>
    <!-- end News -->
  </v-container>
</template>

<script>
import Header from '../components/partials/blog/header.vue';
import News from '../components/partials/blog/News.vue';
export default {
  setup() {
    
  },
  components:{Header,News}
}
</script>

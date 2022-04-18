<template>
<v-lazy v-model="isActive" :options="{threshold:.5}" transition="fade-transition">
  <v-app>
    <!-- start toolbar and header -->
    <section class="background-header-home-page">
      <!-- start toolbar -->
      <toolbar/>
      <!-- end toolbar -->

      <!-- start image header and text-header -->
      <Header/>
      <!-- end image header and text-header -->
    </section>
    <!-- end toolbar and header -->

    <!-- start render page -->
    <nuxt/>
    <!-- end render -->

    <!-- start footer -->
    <Footer/>
    <!-- end footer -->

  </v-app>
</v-lazy>

</template>
<script>
import Toolbar from '../components/common/toolbar.vue'
import Header from '../components/partials/index/header.vue'
import Footer from '../components/common/footer.vue'
export default {
  data: () => ({
      isActive: false,
  }),
  components:{
    Toolbar,Header,Footer
  }
}
</script>

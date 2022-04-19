<template>
<v-lazy v-model="isActive" :options="{threshold:.5}" transition="fade-transition">
  <v-app>
    <!-- start toolbar and header -->
    <section>
      <!-- start toolbar -->
      <toolbar/>
      <!-- end toolbar -->
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
import Footer from '../components/common/footer.vue'
export default {
  data: () => ({
      isActive: false,
  }),
  components:{
    Toolbar,Footer
  }
}
</script>

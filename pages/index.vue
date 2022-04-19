<template>
  <section class="mt-75">
      <!-- start property -->
      <property />
      <!-- end property -->

      <!-- start about -->
      <about-home class="mt-130" />
      <!-- end about -->

      <!-- start parallax -->
      <parallax-component class="mt-140"/>
      <!-- end parallax -->

      <!-- start special support -->
      <special-support class="mt-140"/>
      <!-- end special support -->

      <!-- start Testimonials -->
      <testimonials class="mt-100"/>
      <!-- end Testimonials -->

      <!-- start blogsTips -->
      <blogs-tips />
      <!-- end blogsTips -->
  </section>
</template>

<script>
import property from '../components/partials/index/property.vue'
import aboutHome from '../components/partials/index/about.vue'
import parallaxComponent from '../components/partials/index/parallax.vue'
import SpecialSupport from '../components/partials/index/SpecialSupport.vue'
import Testimonials from '../components/partials/index/Testimonials.vue'
import blogsTips from '../components/partials/index/BlogsTips.vue'
export default {
  data: () => ({
      isActive: false,
  }),
  layout:'home',
  components:{property,aboutHome,parallaxComponent,SpecialSupport,Testimonials,blogsTips}
}
</script>

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
import property from '../components/index/partials/property.vue'
import aboutHome from '../components/index/partials/about.vue'
import parallaxComponent from '../components/index/partials/parallax.vue'
import SpecialSupport from '../components/index/partials/SpecialSupport.vue'
import Testimonials from '../components/index/partials/Testimonials.vue'
import blogsTips from '../components/index/partials/BlogsTips.vue'
export default {
  data: () => ({
      isActive: false,
  }),
  components:{property,aboutHome,parallaxComponent,SpecialSupport,Testimonials,blogsTips}
}
</script>

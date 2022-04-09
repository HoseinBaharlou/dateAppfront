<template>
  <v-lazy v-model="isActive" :options="{threshold:.5}" transition="fade-transition" class="mt-75">
    <property />
  </v-lazy>
</template>

<script>
import property from '../components/index/partials/property.vue'
export default {
  data: () => ({
      isActive: false,
  }),
  components:{property}
}
</script>

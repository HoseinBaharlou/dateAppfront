<template>
<VueSlickCarousel v-bind="settings">
  <v-card class="light-green lighten-2">
    <v-card-actions class="mb-100 mt-10">
      <v-row>
        <!-- start texts -->
        <v-col cols="12" md="6" class="pl-md-10">
          <!-- start title -->
          <h1 class="font-size-60 text-center">our gallery</h1>
          <!-- start content -->
          <p class="mt-8 text-center">Donec eu ligula velit. Duis magna turpis, lobortis eu mollis et, hendrerit sit amet sem. Nulla volutpat felis dolor, et condimentum tortor consequat nec. Integer vitae ligula ac est volutpat volutpat. Cras sed porttitor arcu. Morbi interdum neque vel maximus sodales. Cras aliquam id ex ut varius.</p>
          <!-- end content -->
        </v-col>
        <!-- end texts -->

        <!-- start image -->
        <v-col cols="12" md="6">
          <v-row class="mr-md-16">
            <v-col md="4">
              <v-img src="images/dates-1067265_1920 2.svg" class="rounded-xl"/>
            </v-col>

            <v-col md="4">
              <v-img src="images/dates-1067265_1920 2.svg" class="rounded-xl"/>
            </v-col>

            <v-col md="4">
              <v-img src="images/dates-1067265_1920 2.svg" class="rounded-xl"/>
            </v-col>
          </v-row>
        </v-col>
        <!-- end image -->
      </v-row>
    </v-card-actions>
  </v-card>

  <v-card class="light-green lighten-2">
    <v-card-actions class="mb-100 mt-10">
      <v-row>
        <!-- start texts -->
        <v-col cols="12" md="6" class="pl-md-10">
          <!-- start title -->
          <h1 class="font-size-60 text-center">our gallery</h1>
          <!-- start content -->
          <p class="mt-8 text-center">Donec eu ligula velit. Duis magna turpis, lobortis eu mollis et, hendrerit sit amet sem. Nulla volutpat felis dolor, et condimentum tortor consequat nec. Integer vitae ligula ac est volutpat volutpat. Cras sed porttitor arcu. Morbi interdum neque vel maximus sodales. Cras aliquam id ex ut varius.</p>
          <!-- end content -->
        </v-col>
        <!-- end texts -->

        <!-- start image -->
        <v-col cols="12" md="6">
          <v-row class="mr-md-16">
            <v-col md="4">
              <v-img src="images/dates-1067265_1920 2.svg" class="rounded-xl"/>
            </v-col>

            <v-col md="4">
              <v-img src="images/dates-1067265_1920 2.svg" class="rounded-xl"/>
            </v-col>

            <v-col md="4">
              <v-img src="images/dates-1067265_1920 2.svg" class="rounded-xl"/>
            </v-col>
          </v-row>
        </v-col>
        <!-- end image -->
      </v-row>
    </v-card-actions>
  </v-card>
  /*...*/
</VueSlickCarousel>
</template>
<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
// optional style for arrows & dots
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
export default {
  components:{VueSlickCarousel},
  setup() {
    
  },
  data:()=>{
    return{
      settings:{
        "dots": true,
        'arrows':false,
        "dotsClass": "slick-dots custom-dot-class",
        "edgeFriction": 0.35,
        "infinite": false,
        "speed": 500,
        "slidesToShow": 1,
        "slidesToScroll": 1
      }
    }
  }
}
</script>

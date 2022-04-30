<template>
  <v-row class="mt-100">
    <v-col cols="12">
      <!-- start group slider -->
      <VueSlickCarousel v-bind="settings">
        <div class="px-1">
          <v-img src="images/dates-1067265_1920 1.svg"/>
        </div>
        <div class="px-1">
          <v-img src="images/palma-1454793_1920 1.svg"/>
        </div>
        <div class="px-1">
          <v-img src="images/dates-1067265_1920 1.svg"/>
        </div>
        <div class="px-1">
          <v-img src="images/palma-1454793_1920 1.svg"/>
        </div>
        <div class="px-1">
          <v-img src="images/dates-1067265_1920 1.svg"/>
        </div>
        <div class="px-1">
          <v-img src="images/dates-1067265_1920 1.svg"/>
        </div>
        <div class="px-1">
          <v-img src="images/palma-1454793_1920 1.svg"/>
        </div>
        <div class="px-1">
          <v-img src="images/dates-1067265_1920 1.svg"/>
        </div>
      </VueSlickCarousel>
      <!-- end group slider -->
    </v-col>
  </v-row>
</template>

<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
// optional style for arrows & dots
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'

export default {
  components:{VueSlickCarousel},
  data:()=>{
    return{
      settings:{
        "dots": true,
        "infinite": false,
        "arrows":false,
        "speed": 500,
        "slidesToShow": 5,
        "slidesToScroll": 5,
        "initialSlide": 0,
        "responsive": [
          {
            "breakpoint": 1024,
            "settings": {
              "slidesToShow": 3,
              "slidesToScroll": 3,
              "infinite": false,
              "dots": true
            }
          },
          {
            "breakpoint": 600,
            "settings": {
              "slidesToShow": 2,
              "slidesToScroll": 2,
              "initialSlide": 2
            }
          },
          {
            "breakpoint": 480,
            "settings": {
              "slidesToShow": 1,
              "slidesToScroll": 1
            }
          }
        ]
      }
    }
  }
}
</script>
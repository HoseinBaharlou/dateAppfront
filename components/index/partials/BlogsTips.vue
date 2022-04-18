<template>
  <v-container>
    <v-row class="mt-140">
      <!-- start title -->
      <v-col cols="12">
        <h1 class="font-size-60 blue-gray-text text-center">Blog Tips &#38; Articles To Grow</h1>
      </v-col>
      <!-- end title -->

      <!-- start carousel -->
      <v-col cols="12" class="mt-10">
          <!-- start group slider -->
          <VueSlickCarousel v-bind="settings" class="custom-carousel pb-8">
            <div class="px-1 rounded-0">
              <v-img src="images/dates-1067265_1920 1.svg"/>
              <v-sheet max-width="320" class="py-2">
                <!-- start title -->
                <div class="mx-3">
                  <span class="font-szie-17 font-famyle-lato"><i class="green-light">25 Aug 2020</i><i class="blue-gray-text mx-3">by Merkulove</i></span>
                  <span class="blue-gray-text font-size-24">Minimalist trending in modern agriculture</span>
                </div>
              </v-sheet>
            </div>
            <div class="px-1">
              <v-img src="images/palma-1454793_1920 1.svg"/>
              <v-sheet max-width="320" class="py-2">
                <!-- start title -->
                <div class="mx-3">
                  <span class="font-szie-17 font-famyle-lato"><i class="green-light">25 Aug 2020</i><i class="blue-gray-text mx-3">by Merkulove</i></span>
                  <span class="blue-gray-text font-size-24">Minimalist trending in modern agriculture</span>
                </div>
              </v-sheet>
            </div>
            <div class="px-1">
              <v-img src="images/dates-1067265_1920 1.svg"/>
              <v-sheet max-width="320" class="py-2">
                <!-- start title -->
                <div class="mx-3">
                  <span class="font-szie-17 font-famyle-lato"><i class="green-light">25 Aug 2020</i><i class="blue-gray-text mx-3">by Merkulove</i></span>
                  <span class="blue-gray-text font-size-24">Minimalist trending in modern agriculture</span>
                </div>
              </v-sheet>
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
      <!-- end carousel -->
    </v-row>
  </v-container>
</template>
<script>
export default {
  setup() {
    
  },
}
</script>
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
        "slidesToShow": 3,
        "slidesToScroll": 3,
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
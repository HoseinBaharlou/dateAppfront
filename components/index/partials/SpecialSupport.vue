<template>
  <v-container>
    <v-row>
      <!-- start image -->
      <v-col md="6">
        <v-img src="images/date-palm-1859060_1920 1.svg"></v-img>
      </v-col>
      <!-- end image -->
      <v-col md="6">
        <!-- start title -->
        <p class="green-light">Why Choose Us</p>
        <h1 class="font-family-rubik font-size-50">
          Special Support &#38; 
          Caring <span class="custom-title">Farm Agency</span>
        </h1>
        <!-- end title -->

        <!-- start description -->
        <p class="mt-7">
          Cras non mi odio. Aliquam rhoncus libero urna, sed tincidunt tellus iaculis at. Donec risus ipsum, tincidunt in dictum sed, vulputate sit amet purus.
        </p>
        <!-- end description -->

        <!-- start progress -->
        <section class="d-flex mt-10">
          <div>
            <v-progress-circular
            :rotate="360"
            :size="180"
            :width="12"
            :value="100"
            color="light-green accent-4"
            class="mx-8"
            >
            <span class="black--text"></span>
            </v-progress-circular>
            <p class="text-center mt-4"></p>
          </div>

          <div>
            <v-progress-circular
            :rotate="360"
            :size="180"
            :width="12"
            :value="80"
            color="yellow darken-3"
            class="mx-8"
            >
            <span class="black--text">80%</span>
            </v-progress-circular>
            <p class="mt-4 text-center">Biography Save</p>
          </div>
          
          <div>
            <v-progress-circular
            :rotate="360"
            :size="180"
            :width="12"
            :value="90"
            color="light-green accent-4"
            class="mx-8"
            >
            <span class="black--text">90%</span>
            </v-progress-circular>
            <p class="mt-4 text-center">Happy Customer</p>
          </div>
        </section>
        <!-- end progress -->
      </v-col>
    </v-row>

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
  </v-container>
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

<style scoped>
.custom-title{
  border-bottom: 2px solid #7FB800;
}
</style>
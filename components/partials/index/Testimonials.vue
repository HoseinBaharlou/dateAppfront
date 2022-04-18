<template>
  <v-container>
    <v-row>
      <v-col cols="12">
        <!-- start title and subtitle -->
        <p class="green-light text-center">Testimonials</p>
        <h1 class="font-size-70 text-center">
          Our Happy <span class="custom-title">Clients</span> Say
        </h1>
        <!-- end title and subtitle -->
      </v-col>

      <v-col cols="12">
        <v-row>
          <!-- start next -->
          <v-col cols="2" class="d-flex justify-end align-center">
            <v-btn class="white" elevation="1" @click="prev()" small fab><v-icon x-large>mdi-chevron-left</v-icon></v-btn>
          </v-col>
          <!-- end next -->
          
          <!-- start carousel -->
          <v-col cols="8">
            <VueSlickCarousel v-bind="settings" :arrows="true" ref="slick">
              <v-row class="d-md-flex">
                <!-- start image and icons -->
                <v-col md="4" cols="12">
                  <!-- start image slider-->
                  <div class="m-auto d-flex justify-center">
                    <v-avatar size="170">
                      <v-img src="images/woman-3083377_640 1.svg"/>
                    </v-avatar>
                  </div>
                  <!-- end image slider -->

                  <!-- start icon slider -->
                  <div class="d-flex justify-end mt-5">
                    <v-avatar size="56" class="bg-icons">
                      <v-img src="icons/avocado.svg" lazy-src="icons/avocado.svg" max-height="32" max-width="36" class="rounded-0"/>
                    </v-avatar>
                  </div>
                  <!-- end icon slider -->
                </v-col>
                <!-- end image and icons -->

                <!-- start content -->
                <v-col cols="12" md="8">
                  <p class="font-size-17 font-famyle-lato text-center text-md-justify">
                    Donec placerat, metus sed consectetur viverra, dolor nisl egestas ligula, ac gravida turpis orci eget quam. Aliquam nulla nisi, accumsan id sapien varius, egestas vehicula diam. Suspendisse faucibus neque in ante dignissim interdum at sit amet tellus. Proin aliquam mi eget posuere porta. Nam porta neque vel lectus dicsftum condimentum.
                  </p>
                  <p class="blue-gray-text font-size-20 font-famyle-rubik">Polina Podolski</p>
                  <i class="font-famyle-lato green-light font-size-17">Customer</i>
                </v-col>
                <!-- end content -->
              </v-row>

              <v-row class="d-md-flex">
                <!-- start image and icons -->
                <v-col md="4" cols="12">
                  <!-- start image slider-->
                  <div class="m-auto d-flex justify-center">
                    <v-avatar size="170">
                      <v-img src="images/woman-3083377_640 1.svg"/>
                    </v-avatar>
                  </div>
                  <!-- end image slider -->

                  <!-- start icon slider -->
                  <div class="d-flex justify-end mt-5">
                    <v-avatar size="56" class="bg-icons">
                      <v-img src="icons/avocado.svg" lazy-src="icons/avocado.svg" max-height="32" max-width="36" class="rounded-0"/>
                    </v-avatar>
                  </div>
                  <!-- end icon slider -->
                </v-col>
                <!-- end image and icons -->

                <!-- start content -->
                <v-col cols="12" md="8">
                  <p class="font-size-17 font-famyle-lato text-center text-md-justify">
                    Donec placerat, metus sed consectetur viverra, dolor nisl egestas ligula, ac gravida turpis orci eget quam. Aliquam nulla nisi, accumsan id sapien varius, egestas vehicula diam. Suspendisse faucibus neque in ante dignissim interdum at sit amet tellus. Proin aliquam mi eget posuere porta. Nam porta neque vel lectus dicsftum condimentum.
                  </p>
                  <p class="blue-gray-text font-size-20 font-famyle-rubik">Polina Podolski</p>
                  <i class="font-famyle-lato green-light font-size-17">Customer</i>
                </v-col>
                <!-- end content -->
              </v-row>
            </VueSlickCarousel>
          </v-col>
          <!-- end carousel -->

          <!-- start prev -->
          <v-col cols="2" class="d-flex justify-start align-center">
            <v-btn class="white" elevation="1" fab @click="next()" small><v-icon x-large>mdi-chevron-right</v-icon></v-btn>
          </v-col>
          <!-- end prev -->
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>
<style scoped>
.custom-title{
  border-bottom: 7px solid #7FB800;
}
</style>

 
<script>
  import VueSlickCarousel from 'vue-slick-carousel'
  import 'vue-slick-carousel/dist/vue-slick-carousel.css'
  // optional style for arrows & dots
  import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
 
  export default {
    name: 'MyComponent',
    components: { VueSlickCarousel },
    data:()=>{
      return{
        settings:{
          "dots": false,
          "dotsClass": "slick-dots custom-dot-class",
          "edgeFriction": 0.35,
          "infinite": false,
          "speed": 500,
          "slidesToShow": 1,
          "slidesToScroll": 1
        }
      }
    },
    methods:{
      next(){
        this.$refs.slick.next();
      },
      prev(){
        this.$refs.slick.prev();
      }
    }
  }
</script> 
<template>
  <v-row>
    <!-- start news -->
    <v-col md="8">
      <!-- start news -->
      <article>
        <v-row>
          <v-col md="6">
            <v-img src="images/dates-1067265_1920 2.svg" />
          </v-col>
          <v-col md="6" class="d-flex align-center">
            <section>
              <!-- start date and writer-->
              <div>
                <span><i class="green-light">25 Aug 2020</i> <i class="mx-3 grey--text">by Merkulove</i></span>
              </div>
              <!-- end date and writer -->

              <!-- start title and description -->
              <div class="mt-3">
                <h2 class="blue-gray-text">Practical Suggestions To Improve Usability Landing</h2>

                <p class="mt-5 grey--text font-weight-light">
                  Fusce in nisi ut libero consequat mollis. Donec pulvinar elementum nisl, non hendre
                </p>

                <nuxt-link class="text-capitalize text-decoration-none black--text" to="">Read More<v-icon color="black">mdi-chevron-right</v-icon></nuxt-link>
              </div>
              <!-- end title and  description-->
            </section>
          </v-col>
        </v-row>
      </article>

      <article class="mt-10">
        <v-row>
          <v-col md="6">
            <v-img src="images/dates-1067265_1920 2.svg" />
          </v-col>
          <v-col md="6" class="d-flex align-center">
            <section>
              <!-- start date and writer-->
              <div>
                <span><i class="green-light">25 Aug 2020</i> <i class="mx-3 grey--text">by Merkulove</i></span>
              </div>
              <!-- end date and writer -->

              <!-- start title and description -->
              <div class="mt-3">
                <h2 class="blue-gray-text">Practical Suggestions To Improve Usability Landing</h2>

                <p class="mt-5 grey--text font-weight-light">
                  Fusce in nisi ut libero consequat mollis. Donec pulvinar elementum nisl, non hendre
                </p>

                <nuxt-link class="text-capitalize text-decoration-none black--text" to="">Read More<v-icon color="black">mdi-chevron-right</v-icon></nuxt-link>
              </div>
              <!-- end title and  description-->
            </section>
          </v-col>
        </v-row>
      </article>
      <!-- end news -->

      <!-- start carousel -->
      <v-row class="grey darken-2 mt-10">
        <!-- start next -->
        <v-col cols="2" class="d-flex justify-end align-center">
          <v-btn class="white" elevation="0" @click="prev()" small fab><v-icon x-large color="green lighten-1">mdi-chevron-left</v-icon></v-btn>
        </v-col>
        <!-- end next -->
        <v-col cols="8">
          <VueSlickCarousel v-bind="settings" ref="slick">
            <v-card color="grey darken-2" elevation="0">
              <v-card-title class="d-flex justify-center">
                <!-- start date and writer-->
                <div>
                  <span><i class="green-light">25 Aug 2020</i> <i class="mx-3 white--text">by Merkulove</i></span>
                </div>
                <!-- end date and writer -->
              </v-card-title>
              <v-card-actions class="d-flex justify-center">
                <!-- start title and description -->
                <div class="mt-3 text-center">
                  <h2 class="white--text">Practical Suggestions To Improve Usability Landing</h2>

                  <p class="mt-5 white--text font-weight-light">
                    Fusce in nisi ut libero consequat mollis. Donec pulvinar elementum nisl, non hendre
                  </p>

                  <nuxt-link class="text-capitalize text-decoration-none white--text" to="">Read More<v-icon color="white">mdi-chevron-right</v-icon></nuxt-link>
                </div>
                <!-- end title and  description-->
              </v-card-actions>
            </v-card>
          </VueSlickCarousel>
        </v-col>
        <!-- start prev -->
        <v-col cols="2" class="d-flex justify-start align-center">
          <v-btn class="white" elevation="0" fab @click="next()" small><v-icon x-large color="green lighten-1">mdi-chevron-right</v-icon></v-btn>
        </v-col>
        <!-- end prev -->
      </v-row>
      <!-- end carousel -->
      <!-- start news -->
      <article class="mt-10">
        <v-row>
          <v-col md="6">
            <v-img src="images/dates-1067265_1920 2.svg" />
          </v-col>
          <v-col md="6" class="d-flex align-center">
            <section>
              <!-- start date and writer-->
              <div>
                <span><i class="green-light">25 Aug 2020</i> <i class="mx-3 grey--text">by Merkulove</i></span>
              </div>
              <!-- end date and writer -->

              <!-- start title and description -->
              <div class="mt-3">
                <h2 class="blue-gray-text">Practical Suggestions To Improve Usability Landing</h2>

                <p class="mt-5 grey--text font-weight-light">
                  Fusce in nisi ut libero consequat mollis. Donec pulvinar elementum nisl, non hendre
                </p>

                <nuxt-link class="text-capitalize text-decoration-none black--text" to="">Read More<v-icon color="black">mdi-chevron-right</v-icon></nuxt-link>
              </div>
              <!-- end title and  description-->
            </section>
          </v-col>
        </v-row>
      </article>

      <article class="mt-10">
        <v-row>
          <!-- start image quote -->
          <v-col cols="2" class="hidden-sm-down d-flex justify-center align-center">
            <v-img src="images/quote (1).svg"/>
          </v-col>
          <!-- end image quote -->
          <!-- start content -->
          <v-col md="10" cols="12">
            <!-- start date and writer-->
            <div>
              <span><i class="green-light">25 Aug 2020</i> <i class="mx-3 grey--text">by Merkulove</i></span>
            </div>
            <!-- end date and writer -->

            <!-- start content -->
            <div class="mt-4">
              <p class="grey--text font-weight-light">Donec placerat, metus sed consectetur viverra, dolor nisl egestas ligula, ac gravida turpis orci eget quam. Aliquam nulla nisi, accumsan id sapien varius, egestas vehicula diam. Suspendisse faucibus neque in ante dignissim interdum at sit amet tellus. Proin aliquam mi eget posuere porta. Nam porta neque vel lectus dicsftum condimentum.</p>
              <p class="font-size-20 blue-gray-text">Polina Podolski</p>
              <p class="font-size-17 font-weigth-regular green-light">Customer</p>
            </div>
            <!-- end content -->
          </v-col>
          <!-- end content -->
        </v-row>
      </article>

      <article class="mt-10">
        <v-row>
          <v-col md="6">
            <v-img src="images/dates-1067265_1920 2.svg" />
          </v-col>
          <v-col md="6" class="d-flex align-center">
            <section>
              <!-- start date and writer-->
              <div>
                <span><i class="green-light">25 Aug 2020</i> <i class="mx-3 grey--text">by Merkulove</i></span>
              </div>
              <!-- end date and writer -->

              <!-- start title and description -->
              <div class="mt-3">
                <h2 class="blue-gray-text">Practical Suggestions To Improve Usability Landing</h2>

                <p class="mt-5 grey--text font-weight-light">
                  Fusce in nisi ut libero consequat mollis. Donec pulvinar elementum nisl, non hendre
                </p>

                <nuxt-link class="text-capitalize text-decoration-none black--text" to="">Read More<v-icon color="black">mdi-chevron-right</v-icon></nuxt-link>
              </div>
              <!-- end title and  description-->
            </section>
          </v-col>
        </v-row>
      </article>

      <article class="mt-10">
        <v-row>
          <v-col md="6">
            <v-img src="images/dates-1067265_1920 2.svg" />
          </v-col>
          <v-col md="6" class="d-flex align-center">
            <section>
              <!-- start date and writer-->
              <div>
                <span><i class="green-light">25 Aug 2020</i> <i class="mx-3 grey--text">by Merkulove</i></span>
              </div>
              <!-- end date and writer -->

              <!-- start title and description -->
              <div class="mt-3">
                <h2 class="blue-gray-text">Practical Suggestions To Improve Usability Landing</h2>

                <p class="mt-5 grey--text font-weight-light">
                  Fusce in nisi ut libero consequat mollis. Donec pulvinar elementum nisl, non hendre
                </p>

                <nuxt-link class="text-capitalize text-decoration-none black--text" to="">Read More<v-icon color="black">mdi-chevron-right</v-icon></nuxt-link>
              </div>
              <!-- end title and  description-->
            </section>
          </v-col>
        </v-row>
      </article>
      <!-- end news -->
    </v-col>
    <!-- end news -->
    <!-- start cards and search box -->
    <v-col md="4" class="News">
      <div class="d-flex">
      <v-text-field 
      filled
      placeholder="search..."
      class="rounded-l-xl rounded-r-0"
      outlined
      rounded
      height="56"
      dense></v-text-field>
      <v-btn class="bg-green-darken-to-light rounded-l-0 rounded-r-xl white--text text-capitalize" elevation="0" height="56">search</v-btn>
      </div>
      <v-card class="rounded-xl custom-box-shadow">
        <!-- start title -->
        <v-card-title class="px-10 py-10 pb-1">
          <v-badge dot color="green" left offset-y="15" offset-x="-2">
            <h3 class="blue-gray-text font-weight-medium">Latest Posts</h3>
          </v-badge>
        </v-card-title>
        <!-- end title -->

        <!-- start content -->
        <v-card-text class="pr-6">
          <div class="mt-4">
            <p class="font-size-18 font-weight-regular blue-gray-text mb-1">
              Minimalist trending in modern agriculture
            </p>
            <span class="grey--text"><i>25 Aug 2020</i><i class="ml-5">by Merculove</i></span>
          </div>
          <div class="mt-4">
            <p class="font-size-18 font-weight-regular blue-gray-text mb-1">
              Minimalist trending in modern agriculture
            </p>
            <span class="grey--text"><i>25 Aug 2020</i><i class="ml-5">by Merculove</i></span>
          </div>
          <div class="mt-4">
            <p class="font-size-18 font-weight-regular blue-gray-text mb-1">
              Minimalist trending in modern agriculture
            </p>
            <span class="grey--text"><i>25 Aug 2020</i><i class="ml-5">by Merculove</i></span>
          </div>
          <div class="mt-4">
            <p class="font-size-18 font-weight-regular blue-gray-text mb-1">
              Minimalist trending in modern agriculture
            </p>
            <span class="grey--text"><i>25 Aug 2020</i><i class="ml-5">by Merculove</i></span>
          </div>
        </v-card-text>
        <!-- end content -->
      </v-card>

      <v-card class="rounded-xl custom-box-shadow mt-8">
        <!-- start title -->
        <v-card-title class="px-10 py-10 pb-1">
          <v-badge dot color="green" left offset-y="15" offset-x="-2">
            <h3 class="blue-gray-text font-weight-medium">Recent Comments</h3>
          </v-badge>
        </v-card-title>
        <!-- end title -->

        <!-- start content -->
        <v-card-text class="pr-6">
          <div class="mt-4 d-flex">
            <v-img src="icons/comment.svg" width="28" height="28"/>
            <p class="font-size-18 font-weight-regular blue-gray-text mb-1 ml-2">
              <b>Admin</b> in Mauris maximus iaculis nunc quis
            </p>
          </div>
          <div class="mt-4 d-flex">
            <v-img src="icons/comment.svg" width="28" height="28"/>
            <p class="font-size-18 font-weight-regular blue-gray-text mb-1 ml-2">
              <b>Admin</b> in Mauris maximus iaculis nunc quis
            </p>
          </div>
          <div class="mt-4 d-flex">
            <v-img src="icons/comment.svg" width="28" height="28"/>
            <p class="font-size-18 font-weight-regular blue-gray-text mb-1 ml-2">
              <b>Admin</b> in Mauris maximus iaculis nunc quis
            </p>
          </div>
          <div class="mt-4 d-flex">
            <v-img src="icons/comment.svg" width="28" height="28"/>
            <p class="font-size-18 font-weight-regular blue-gray-text mb-1 ml-2">
              <b>Admin</b> in Mauris maximus iaculis nunc quis
            </p>
          </div>
        </v-card-text>
        <!-- end content -->
      </v-card>

      <v-card class="rounded-xl custom-box-shadow mt-8">
        <!-- start title -->
        <v-card-title class="px-10 py-10 pb-1">
          <v-badge dot color="green" left offset-y="15" offset-x="-2">
            <h3 class="blue-gray-text font-weight-medium">Latest Posts</h3>
          </v-badge>
        </v-card-title>
        <!-- end title -->

        <!-- start content -->
        <v-card-text class="pr-6">
          <div class="mt-4">
            <p class="font-size-18 font-weight-regular blue-gray-text mb-1">
              Minimalist trending in modern agriculture
            </p>
            <span class="grey--text"><i>25 Aug 2020</i><i class="ml-5">by Merculove</i></span>
          </div>
          <div class="mt-4">
            <p class="font-size-18 font-weight-regular blue-gray-text mb-1">
              Minimalist trending in modern agriculture
            </p>
            <span class="grey--text"><i>25 Aug 2020</i><i class="ml-5">by Merculove</i></span>
          </div>
          <div class="mt-4">
            <p class="font-size-18 font-weight-regular blue-gray-text mb-1">
              Minimalist trending in modern agriculture
            </p>
            <span class="grey--text"><i>25 Aug 2020</i><i class="ml-5">by Merculove</i></span>
          </div>
          <div class="mt-4">
            <p class="font-size-18 font-weight-regular blue-gray-text mb-1">
              Minimalist trending in modern agriculture
            </p>
            <span class="grey--text"><i>25 Aug 2020</i><i class="ml-5">by Merculove</i></span>
          </div>
        </v-card-text>
        <!-- end content -->
      </v-card>
    </v-col>
    <!-- end cards and search box -->
  </v-row>
</template>
<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
// optional style for arrows & dots
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
import Articles from '../index/articles.vue'
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

<style scoped lang="scss">
  .custom-box-shadow{
    box-shadow: 0px 0px 15px rgba(127, 184, 0, 0.15) !important;
  }
</style>
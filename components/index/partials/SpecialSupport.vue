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
            <span class="black--text">80%</span>
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
  </v-container>
</template>
<style scoped>
.custom-title{
  border-bottom: 2px solid #7FB800;
}
</style>
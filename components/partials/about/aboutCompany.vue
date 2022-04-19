<template>
  <v-row class="align-center">
    <v-col cols="12" md="6">
      <!-- start title and subtitle -->
      <p class="green-light">About Company</p>
      <h1 class="font-size-60 mt-4 blue-gray-text">Fun Facts About <span class="green-border">Hossein</span></h1>
      <!-- end title and subtitle -->

      <!-- start description -->
      <p class="mt-5 font-famyle-lato font-weight-light">Fusce in nisi ut libero consequat mollis. Donec pulvinar elementum nisl, non hendrerit ipsum consequat eu. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ullamcorper, velit at mollis vehicula, neque arcu ultricies eros</p>
      <!-- end description -->

      <!-- start btn -->
      <div class="mt-10">
        <v-btn color="amber darken-3" outlined fab ><v-icon>mdi-play</v-icon></v-btn><span class="mx-2">Watch Video</span>
      </div>
      <!-- end btn -->
    </v-col>
    
    <!-- start image -->
    <v-col cols="12" md="6">
      <v-img src="images/date-palm-331293_1920 1.svg" lazy-src="images/date-palm-331293_1920 1.svg" height="423" class="rounded-xl" />
    </v-col>
    <!-- end image -->
  </v-row>
</template>
<template>
  <v-app>
    <section class="background-header-home-page">
      <!-- start toolbar -->
      <v-toolbar class="light py-8 elevation-0 mb-24 transparent">
        <!-- start title -->
        <v-toolbar-title class="green-border font-size-27 text-center">BEHTA ABADIS PARSA</v-toolbar-title>
        <!-- end title -->
        <v-spacer></v-spacer>
        <!-- start item menu -->
        <nuxt-link to="" class="mx-15 black--text text-decoration-none">Home</nuxt-link>
        <nuxt-link to="" class="mx-15 black--text text-decoration-none">Home</nuxt-link>
        <nuxt-link to="" class="mx-15 black--text text-decoration-none">Home</nuxt-link>
        <nuxt-link to="" class="mx-15 black--text text-decoration-none">Home</nuxt-link>
        <!-- end item menu -->
        <v-spacer></v-spacer>
        <!-- start search box -->
        <v-text-field>
          <v-icon slot="prepend" color="black">mdi-magnify</v-icon>
        </v-text-field>
        <!-- end search box -->
      </v-toolbar>
      <!-- end toolbar -->
      <!-- start image header and text-header -->
      <v-container class="mt-90">
        <v-row>
          <v-col md="6">
            <v-lazy v-model="isActive" :options="{threshold:.5}" transition="fade-transition">
              <section>
                <!-- start title -->
                <h1 class="font-size-83"><span class="blue-gray-text">Eat CleanEat</span> <span class="green-light">Organic</span></h1>
                <!-- end title -->
                <!-- start content -->
                <p>
                  Donec placerat, metus sed consectetur viverra, dolor nisl egestas ligula, ac gravida turpis orci eget quam. Aliquam nulla nisi, accumsan id sapien varius
                </p>
                <!-- end content -->
                <!-- start button -->
                <div>
                  <v-row>
                    <v-col>
                      <v-btn class="bg-green-darken-to-light white--text text-capitalize" rounded x-large>About kamran</v-btn>
                    </v-col>
                  </v-row>
                </div>
                <!-- end button -->
              </section>
            </v-lazy>
          </v-col>
          <!-- start image -->
          <v-col md="6" class="pb-0">
            <v-img  src="/images/dates-6638825_1280 1.svg" max-width="664" max-height="442"/>
          </v-col>
          <!-- end image -->
        </v-row>
      </v-container>
    </section>
    <!-- start render page -->
    <nuxt/>
    <!-- end render -->


  </v-app>
</template>
<script>
export default {
  data: () => ({
      isActive: false,
  }),
}
</script>

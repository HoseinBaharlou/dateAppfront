<template>
  <!-- start footer -->
  <v-footer class="mt-70 white">
    <v-container>
      <v-row class="d-flex align-center">
        <!-- start about -->
        <v-col cols="6">
          <section>
            <!-- start icons -->
            <div class="d-flex align-center">
              <v-img src="icons/Object.svg" max-height="65" max-width="65" />
              <h2 class="font-weight-regular font-size-37 ml-2">kamran</h2>
            </div>
            <!-- end icons -->
            <!-- start desciption -->
            <p class="text-justify font-size-17 grey--text darken-2 font-weight-light mt-5">
              Donec placerat, metus sed consectetur viverra, dolor nisl egestas ligula, ac gravida turpis orci eget quam. Aliquam nulla nisi, accumsan id sapien varius, egestas vehicula di
            </p>
            <!-- end description -->
            <!-- start social media -->
            <div class="mt-10">
              <v-icon color="light-green accent-4" class="mx-2">mdi-instagram</v-icon>
              <v-icon color="light-green accent-4" class="mx-2">mdi-facebook</v-icon>
              <v-icon color="light-green accent-4" class="mx-2">mdi-youtube</v-icon>
              <v-icon color="light-green accent-4" class="mx-2">mdi-linkedin</v-icon>
            </div>
            <!-- end social media -->

            <!-- start about programmer -->
            <p class="my-15">kamran <span class="grey--text">&copy; kamran Template All rights reserved Copyrights 2020</span></p>
            <!-- end about programmer -->
          </section>
        </v-col>
        <!-- end about -->

        <!-- start sign up to newslatter -->
        <v-col cols="6">
          <v-card class="bg-green-darken-to-light rounded-t-xl px-15" elevation="0">
            <!-- start title and subtitle-->
            <v-card-title class="mt-16 d-flex justify-center">
              <section>
                <h1 class="font-size-42 font-famyle-rubik white--text mt-140 text-center">
                Be informed!
                </h1>
                <h2 class="font-size-42 font-famyle-rubik font-weight-regular white--text text-center mt-5">
                  Sign up for newsletter
                </h2>
              </section>
            </v-card-title>
            <!-- end title and subtitle-->
            
            <!-- start description and input -->
            <v-card-actions class="d-block">
              <!-- start description -->
              <p class="text-center white--text font-weight-regular">Donec placerat, metus sed consectetur viverra, dolor nisl egestas ligula, ac gravida turpis</p>
              <!-- end description -->

              <!-- start input email -->
              <section class="mb-140">
                <div>
                  <v-text-field
                label="Email"
                filled
                dense
                rounded
                background-color="transparent"
                outlined
                class="mt-10"
                color="black"
                  ></v-text-field>
                </div>
                <div class="d-flex justify-center mt-3">
                  <v-btn class="white--text text-capitalize px-10 py-4" color="orange lighten-1" large elevation="0" rounded>Submit Now</v-btn>
                </div>
              </section>
              <!-- end input email -->
            </v-card-actions>
            <!-- end description and input -->
          </v-card>
        </v-col>
        <!-- end sign up to newslatter -->
      </v-row>
    </v-container>
  </v-footer>
  <!-- end footer -->
</template>
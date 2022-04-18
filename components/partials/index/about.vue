<template>
  <v-container>
    <v-row>
      <!-- start title and subtitle -->
      <v-col cols="12">
        <p class="font-size-17 green-light text-center">Who We Are</p>
        <h1 class="font-size-60 blue-gray-text text-center font-weight-bold">
          Few Words About Farmino
        </h1>
        <hr class="custom-line">
      </v-col>
      <!-- end title and subtitle -->

      <!-- start special support -->
      <v-col cols="12">
        <v-row>
          <v-col md="6" cols="12">
            <section class="mt-8">
              <!-- start title -->
                <h2 class="blue-gray-text">
                  Special Support &#38; Caring Organic
                  Farmino Agency
                </h2>
              <!-- end title -->

              <!-- start description -->
                <p class="mt-3">
                  Suspendisse faucibus neque in ante dignissim interdum at sit amet tellus. Proin aliquam mi eget posuere porta. Nam porta neque vel lectus dictum condimentum.
                </p>
              <!-- end description -->
            </section>

            <section class="mt-14">
              <!-- start card -->
              <v-card class="elevation-0">
                <v-card-title class="flex-nowrap">
                  <div class="custom-icon">
                    <v-img src="icons/check.svg"/>
                  </div>
                  <div class="d-block px-4">
                    <h3 class="font-famyle-rubic d-block font-size-19 mt-1 blue-gray-text">Naturall Food</h3>
                    <span class="font-famyle-lato text-truncate font-size-17 grey--text custom-subtitle">
                      Liquam nulla nisi, accumsan id sapien varius, egestas vehicula diam. Suspendisse faucibus neque
                    </span>
                  </div>
                </v-card-title>
              </v-card>

              <v-card class="elevation-0 mt-10">
                <v-card-title class="flex-nowrap">
                  <div class="custom-icon">
                    <v-img src="icons/check.svg"/>
                  </div>
                  <div class="d-block px-4">
                    <h3 class="font-famyle-rubic d-block font-size-19 mt-1 blue-gray-text">Naturall Food</h3>
                    <span class="font-famyle-lato text-truncate font-size-17 grey--text custom-subtitle">
                      Morbi leo tellus, semper sed vestibulum quis, suscipit eu tortor. Fusce cursus tortor ut consequat venenatis
                    </span>
                  </div>
                </v-card-title>
              </v-card>

              <v-card class="elevation-0 mt-10">
                <v-card-title class="flex-nowrap">
                  <div class="custom-icon">
                    <v-img src="icons/check.svg"/>
                  </div>
                  <div class="d-block px-4">
                    <h3 class="font-famyle-rubic d-block font-size-19 mt-1 blue-gray-text">Naturall Food</h3>
                    <span class="font-famyle-lato  text-truncate font-size-17 grey--text custom-subtitle">
                      Donec placerat, metus sed consectetur viverra, dolor nisl egestas ligula, ac gravida turpis orci eget quam
                    </span>
                  </div>
                </v-card-title>
              </v-card>
              <!-- end card -->
            </section>
          </v-col>

          <v-col md="6" cols="12">
          </v-col>
        </v-row>
      </v-col>
    <!-- end special support -->
    </v-row>
  </v-container>
</template>
<script>
export default {
  data:()=>{
    return{}
  }
}
</script>

<style scoped>
.custom-line{
  height: 8px;
  background: #7FB800;
  max-width: 280px;
  border: #7FB800 solid;
  margin: auto;
}
.custom-icon{
  border: 1px solid #7FB800;
  border-radius: 146px;
  padding: 23px;
  height: 86.71px;
}
</style>
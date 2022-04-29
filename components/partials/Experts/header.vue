<template>
  <v-parallax src="images/Rectangle 6.svg" height="425">
    <v-row class="align-center">
      <!-- start title and breadcrumbs -->
      <v-col cols="10" offset="2">
        <!-- start title -->
        <h1 class="font-size-80 blue-gray-text">Services</h1>
        <!-- end title -->
        <!-- start breadcrumbs -->
        <v-breadcrumbs :items="items">
          <template v-slot:divider>
            <v-img src="icons/element.svg" />
          </template>
          <template v-slot:item="{ item }">
            <v-breadcrumbs-item :disabled="item.disabled">
              <span class="black--text">
                {{ item.text }}
              </span>
            </v-breadcrumbs-item>
          </template>
        </v-breadcrumbs>
        <!-- end breadcrumbs -->
      </v-col>
      <!-- end title and breadcrumbs -->
    </v-row>
  </v-parallax>
</template>

<script>

export default {
  setup() {
    
  },
  data:()=>{
    return{
      items:[
        {
          text:'Home',
          disabled:false,
          href:''
        },
        {
          text:'about',
          disabled:false,
          href:''
        },
        {
          text:'Our Farmers',
          disabled:false,
          href:''
        }
      ]
    }
  }
}
</script>



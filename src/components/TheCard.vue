<template>
  <v-container>
    <v-list class=" transparent d-flex justify-space-between  mt-16">
      <v-hover v-slot="{ hover }" open-delay="100">
        <v-card class="rounded-lg " width="263" color="#312F30" :class="{ 'on-hover': hover }" :elevation="hover ? 12 : 2">
          <v-img class=" mt-auto rounded" src="../assets/image/slider-1.png"> </v-img>
          <v-list-item-content class="  justify-center">
            <v-card-title class=" justify-center  text-center white--text font-weight-medium text-lg-h6  pa-0">Chicken
              Paella </v-card-title>
            <v-card-subtitle
              class=" font-weight-regular opacity-subtitle white--text pa-0 text-center mt-3 mb-4 text-sm-body-1">We
              just
              don't make and sell food.Good food warms</v-card-subtitle>
          </v-list-item-content>
        </v-card>
      </v-hover>

 <v-hover v-slot="{ hover }" open-delay="100">
    <v-card class="rounded-lg " width="263" color="#312F30" :class="{ 'on-hover': hover }" :elevation="hover ? 12 : 2">
        <v-img class=" mt-auto rounded" src="../assets/image/slider-2.png"> </v-img>
        <v-list-item-content class="  justify-center">
          <v-card-title class=" justify-center  text-center white--text font-weight-medium text-lg-h6  pa-0">Taco Del
            Mar </v-card-title>
          <v-card-subtitle
            class=" font-weight-regular opacity-subtitle white--text pa-0 text-center mt-3 mb-4 text-sm-body-1">Taco Del
            Mar brings the best out of Mexican cuisine with fresh.</v-card-subtitle>
        </v-list-item-content>
      </v-card>
 </v-hover>
   
<v-hover v-slot="{ hover }" open-delay="100">
  <v-card class="rounded-lg " width="263" color="#312F30" :class="{ 'on-hover': hover }" :elevation="hover ? 12 : 2">
        <v-img class=" mt-auto rounded" src="../assets/image/slider-3.png"> </v-img>
        <v-list-item-content class="  justify-center">
          <v-card-title class=" justify-center  text-center white--text font-weight-medium text-lg-h6  pa-0">Bon Au Pain
          </v-card-title>
          <v-card-subtitle
            class=" font-weight-regular opacity-subtitle white--text pa-0 text-center mt-3 mb-4 text-sm-body-1">Bon Au
            Pain is a pioneer in the healthy fast food scene.</v-card-subtitle>
        </v-list-item-content>
      </v-card>
</v-hover>
    
<v-hover v-slot="{ hover }" open-delay="100">
   <v-card class="rounded-lg " width="263" color="#312F30" :class="{ 'on-hover': hover }" :elevation="hover ? 12 : 2">
        <v-img class=" mt-auto rounded" src="../assets/image/slider-4.png"> </v-img>
        <v-list-item-content class="  justify-center">
          <v-card-title class=" justify-center  text-center white--text font-weight-medium text-lg-h6  pa-0">Pizza Hut.
          </v-card-title>
          <v-card-subtitle
            class=" font-weight-regular opacity-subtitle white--text pa-0 text-center mt-3 mb-4 text-sm-body-1">Although
            the Pizza Hut Menu Prices have tumbled over the years.</v-card-subtitle>
        </v-list-item-content>
      </v-card>
</v-hover>
   

    </v-list>
  </v-container>

</template>

<script>
export default {

}

</script>

<style>
</style>
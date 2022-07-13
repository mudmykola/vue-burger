<template >
  <div class="header ">
    <v-container>
      <v-toolbar color=" transparent  " align-center outlined>
        <v-list-item-avatar>
          <v-img src="../assets/top-logo.png" width="100px" height="100px"></v-img>
        </v-list-item-avatar>
        <v-tabs color="#FF5D00 " centered>
          <v-tab class=" white--text font-weight-regular text-lg-center" v-for="link in links" :key="link">{{ link
          }} </v-tab>
        </v-tabs>
        <v-hover v-slot="{ hover }">
          <v-btn class=" white--text font-weight-medium" :style="{ 'background-color': hover ? '#FF5D00' : '#F6762C' }">
            ORDER NOW</v-btn>
        </v-hover>
      </v-toolbar>
      <template >
  <v-card class=" white--text header-cont"  outlined color=" transparent" width="540" >
    <v-list-item-subtitle class=" font-weight-medium text-subtitle-2">FAST FOOD BURGERS</v-list-item-subtitle>
          <v-list-item-title class=" text-h2 text-wrap font-weight-medium mt-2 ">
The fastest food, for instant hunger.
          </v-list-item-title>
         <v-list-item-subtitle class=" text-wrap mt-9 font-weight-regular opacity-subtitle">Some food has looked so awful that it's looked like something that the dog's brought home, yet after one mouthful I've been left eating my thoughts, my words & my food and gone back for seconds.
            </v-list-item-subtitle>
    
          <v-hover v-slot="{ hover }" >
            <v-btn class=" white--text font-weight-medium mt-10" 
              :style="{ 'background-color': hover ? '#FF5D00' : '#F6762C' }">
              ORDER NOW</v-btn>
          </v-hover>
  </v-card>
      </template>
     
      

   
    </v-container>
  </div>
</template>

<script >
export default {
  data() {

    return {
      items: [
        {
          logo: '../assets/top-logo.png'
        },
      ],
      links: [

        'Home', 'Pages', 'OUR OFFER', 'PRICING', 'Shop',


      ]
    }

  }

}
</script>

<style>
.header {
  background-image: url('../assets/header-bg.png');
  background-repeat: no-repeat;
  height: 100vh;
  background-position: center;
  background-size: cover;
}
.header-cont{
  margin-top: 186px;
}
.opacity-subtitle{
  opacity: 0.7;
}
</style>
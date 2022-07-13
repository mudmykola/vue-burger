<template>
    <v-app :style="{ background: $vuetify.theme.themes.dark.background }">
    <the-header/>
    </v-app>
</template>

<script>
import TheHeader from '@/components/TheHeader.vue'
 

  export default {
    name: 'TheHome',

    components: {TheHeader,},
  }
</script>

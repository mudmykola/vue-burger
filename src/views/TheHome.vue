<template>
    <v-app :style="{ background: $vuetify.theme.themes.dark.background }">
    <the-header/>
    <the-card/>
    </v-app>
</template>

<script>
import TheHeader from '@/components/TheHeader.vue'
import TheCard from '@/components/TheCard.vue'
 

  export default {
    name: 'TheHome',

    components: { TheHeader, TheCard },
  }
</script>

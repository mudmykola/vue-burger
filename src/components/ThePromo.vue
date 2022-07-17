<template>
    <v-card class=" mt-16" color="rgba(49, 47, 48, 1)">
        <v-container>
            <v-list class=" d-flex align-center transparent "  v-for="(item) in files" :key="item.title" flat>
                <v-list-item-content class=" mr-16">
                    <v-img  src="../assets/image/promo.png" width="550"></v-img>
                </v-list-item-content>
                <v-list-item-content class=" d-block ml-auto ml-16">
                    <v-list-item-title class=" text-h4 white--text font-weight-medium mb-6" v-text="item.title">
                    </v-list-item-title>
                    <v-list-item-subtitle class=" d-block text-wrap  white--text font-weight-regular text-subtitle-1   opacity-subtitle  mb-3"
                        v-text="item.subtitle"></v-list-item-subtitle>
                    <v-list-item-subtitle class=" orange--text font-weight-medium text-h6 mb-3" >{{ item.price }}<span class="opacity-subtitle text-decoration-line-through font-weight-medium text-subtitle-1 ml-3">$8</span></v-list-item-subtitle>
                    <v-hover v-slot="{ hover }">
                        <v-btn class=" white--text font-weight-medium" width="165" height="49"
                            :style="{ 'background-color': hover ? '#FF5D00' : '#F6762C' }">
                            ORDER NOW</v-btn>
                    </v-hover>
                </v-list-item-content>
            </v-list>
        </v-container>
    </v-card>
</template>

<script>
export default {
    data: () => ({
        files: [
            {
                title: 'Burger King',
                subtitle: 'Together with McDonald’s, Burger King has grown to become synonymous with burgers in the US.',
                price: '$6',
            },
        ],
    }),
}
</script>

<style>
</style>
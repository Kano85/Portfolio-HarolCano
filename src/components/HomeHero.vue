<template>
    <v-container fluid fill-height class="home-hero" style="max-height: 100vh;">
        <v-layout justify-center align-center column pa-5>
            <div class="display-4 font-weight-black white--text text-xs-center">
                Harold Cano
            </div>
            <div
                class="display-4 font-weight-black white--text text-xs-center mb-3"
            >
                Portfolio
            </div>
            <div class="display-1 font-weight-bold white--text text-xs-center">
                “Simplicity is the ultimate sophistication.” –Leonardo da Vinci
            </div>
            <!-- <v-btn fab class="mt-5 brown darken-4">
                <v-icon large color="white">expand_more</v-icon>
            </v-btn> -->
        </v-layout>
    </v-container>
</template>

<script>
export default {
    name: 'HomeHero'
};
</script>

<style scoped>
.home-hero {
    background-image: url('~@/assets/Bewerbungsfoto.jpg');
    background-size: cover;
    width: 100%;
    height: 100%;
}
.display-4 {
    padding-left: 90vh;
}
.display-1 {
    padding-left: 90vh;
}
/* .mt-5 {
  padding-top: 50vh;
} */
</style>

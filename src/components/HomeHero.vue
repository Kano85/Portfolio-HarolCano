<template>
<v-container fluid fill-height class="home-hero">
  <v-layout justify-center align-center column pa-5>
    <div class="display-4 font-weight-black black--text text-xs-center" id="top-text">
      Harold Cano
    </div>
    <div class="display-4 font-weight-black black--text text-xs-center mb-3">
      Portfolio
    </div>
    <div class="display-1 font-weight-bold black--text text-xs-center">
      'Form Follows Function'
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
  background-image: url('~@/assets/Bewerbungsfoto2.jpg');
  background-size: cover;
  width: 100%;
  height: 100%;
  max-height: 100vh;

}
.display-4 {
  padding-left: 110vh;
}

.display-1 {
  padding-left: 110vh;
}

@media only screen and (max-width: 1750px) {

.home-hero {
  background-image: url('~@/assets/Bewerbungsfoto2.jpg');
  background-size: cover;
  width: 100%;
  height: 100%;
  max-height: 100vh;
  }

#top-text {
  padding-top: 30vh;
  }
.display-4 {
  padding-left: 0vh;
  }

.display-1 {
  padding-left: 0vh;
  }
}
@media only screen and (max-width: 1200px) {

.home-hero {
  background-image: url('~@/assets/Bewerbungsfoto.jpg');
  background-size: cover;
  width: 100%;
  height: auto;
  margin-bottom: 40vh;
  max-height: 40vh;
  }

#top-text {
  padding-top: 80vh;
  }
.display-4 {
  padding-left: 0vh;
  }

.display-1 {
  padding-left: 0vh;
  }
}
@media only screen and (max-width: 500px) {

.home-hero {
  background-image: url('~@/assets/Bewerbungsfoto.jpg');
  background-repeat: no-repeat;
  background-position: center;
  width: 100%;
  max-height: 40vh;
  margin-bottom: 90vh;
  max-height: 40vh;
  }

#top-text {
  padding-top: 110vh;
  }
.display-4 {
  padding-left: 0vh;
  }

.display-1 {
  padding-left: 0vh;
  }
}

/* .mt-5 {
  padding-top: 50vh;
} */
</style>

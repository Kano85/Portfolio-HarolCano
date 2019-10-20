<template>
<v-container fluid class="container-contact lighten-4">
  <v-container grid-list-lg>
    <v-layout column>
      <div class="display-4 font-weight-black white--text text-xs-left">
        Contact
      </div>
      <div class="headline">
        Phone
      </div>
      <p class="subheading mt-3">
        +49 17627744274
      </p>

      <v-flex>
        <div class="headline">
          Email
        </div>
        <p class="subheading mt-3">
          hcanocardenas@gmail.com
        </p>
      </v-flex>
    </v-layout>
  </v-container>
</v-container>
</template>

<script>
export default {
  name: 'contact'
};
</script>

<style scoped>
.container-contact {
  background-color: #1976D2;
}
.headline {
    margin-top: 3vh;
    font-weight: bold;
    color: white;
}
.subheading {
  color: white;
}
</style>

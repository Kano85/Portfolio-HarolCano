<template>
<span>
  <!-- hamburger-menu small viewport -->
  <v-navigation-drawer app v-model="drawer" class="#B3E5FC" dark disable-resize-watcher>
    <v-list>
      <template v-for="(item, index) in items">
        <v-list-tile :key="index" :to="item.url">
          <v-list-tile-content>
            {{ item.title }}
          </v-list-tile-content>
        </v-list-tile>
        <v-divider :key="`divider-${index}`"></v-divider>
      </template>
    </v-list>
  </v-navigation-drawer>
<!-- toolbar top viewport -->
  <v-toolbar app color="#b0bec5" dark>
    <v-toolbar-side-icon class="hidden-md-and-up" @click="drawer = !drawer"></v-toolbar-side-icon>
    <v-spacer class="hidden-md-and-up"></v-spacer>
    <router-link to="/">
      <v-toolbar-title data-cy="titleBtn">{{
                    appTitle
                }}</v-toolbar-title>
    </router-link>
    <v-btn flat class="hidden-sm-and-down nav-menu" to="/menu" data-cy="menuBtn">projects</v-btn>
    <v-spacer class="hidden-sm-and-down"></v-spacer>
    <div v-if="!isAuthenticated" class="hidden-sm-and-down">
      <v-btn flat to="/sign-in" data-cy="signinBtn">SIGN IN</v-btn>
      <v-btn color="#29B6F6" to="/join" class="nav-join" data-cy="joinBtn">JOIN</v-btn>
    </div>
    <div v-else>
      <v-btn flat to="/about">PROFILE</v-btn>
      <v-btn outline color="white" @click="logout" data-cy="logout">Logout</v-btn>
    </div>
  </v-toolbar>
</span>
</template>

<script>
export default {
  name: 'AppNavigation',
  data() {
    return {
      appTitle: 'Portfolio',
      drawer: false,
      items: [{
          title: 'Projects',
          url: '/menu'
        },
        {
          title: 'Profile',
          url: '/about'
        },
        {
          title: 'Sign In',
          url: '/sign-in'
        },
        {
          title: 'Join',
          url: '/join'
        }
      ]
    };
  },
  computed: {
    isAuthenticated() {
      return this.$store.getters.isAuthenticated;
    }
  },
  methods: {
    logout() {
      this.$store.dispatch('userSignOut');
    }
  }
};
</script>

<style scoped>
a {
  color: white;
  text-decoration: none;
  font-size: 18px;
}
</style>

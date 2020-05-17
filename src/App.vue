<template>
  <v-app class="app-fix">
    <v-app-bar app color="primary" dark class="nav-bar" style="position: sticky !important;">
      <v-app-bar-nav-icon @click="drawer = true" style="display: none;" class="hamburger"></v-app-bar-nav-icon>
      <v-toolbar-title class="tb-title">
        <router-link to="/" style="height: 100%;">Eric Jungbluth | Front End Developer</router-link>
      </v-toolbar-title>

      <v-spacer></v-spacer>

      <router-link to="/resume" style="height: 100%;" v-if="this.$route.path !== '/'">
        <v-btn class="nav-btn">Résumé</v-btn>
      </router-link>

      <router-link to="/contact" style="height: 100%;" v-if="this.$route.path !== '/'">
        <v-btn class="nav-btn">Contact</v-btn>
      </router-link>

      <router-link to="/about" style="height: 100%;" v-if="this.$route.path !== '/'">
        <v-btn class="nav-btn">About</v-btn>
      </router-link>
    </v-app-bar>
    <v-navigation-drawer v-model="drawer" absolute temporary class="drawer-content">
      <v-list nav dense>
        <v-list-item-group>
          <router-link to="/" style="height: 100%;">
            <v-list-item>
              <v-list-item-icon>
                <v-icon class="icons">mdi-home</v-icon>
              </v-list-item-icon>
              <v-list-item-title class="icons">Home</v-list-item-title>
            </v-list-item>
          </router-link>

          <router-link to="/resume" style="height: 100%;" v-if="this.$route.path !== '/'">
            <v-list-item>
              <v-list-item-icon>
                <v-icon class="icons">mdi-information</v-icon>
              </v-list-item-icon>
              <v-list-item-title class="icons">Résumé</v-list-item-title>
            </v-list-item>
          </router-link>

          <router-link to="/contact" style="height: 100%;" v-if="this.$route.path !== '/'">
            <v-list-item>
              <v-list-item-icon>
                <v-icon class="icons">mdi-account</v-icon>
              </v-list-item-icon>
              <v-list-item-title class="icons">Contact</v-list-item-title>
            </v-list-item>
          </router-link>

          <router-link to="/about" style="height: 100%;" v-if="this.$route.path !== '/'">
            <v-list-item>
              <v-list-item-icon>
                <v-icon class="icons">mdi-book-open-variant</v-icon>
              </v-list-item-icon>
              <v-list-item-title class="icons">About</v-list-item-title>
            </v-list-item>
          </router-link>
        </v-list-item-group>
      </v-list>
    </v-navigation-drawer>

    <router-view></router-view>
  </v-app>
</template>

<style scoped>
.nav-btn {
  /* border-left: 1px white solid; */
  background-color: #272727;
  height: 100% !important;
  margin: 0;
  /* border-right: 1px white solid; */
  width: 15vw;
  border-radius: 0;
  box-shadow: none;
  color: #3ecbbe;
}

/deep/ .v-toolbar__content {
  padding: 0 16px !important;
}

/deep/ .v-btn__content {
  color: #3ecbbe !important;
}

/deep/ .v-btn:not(.v-btn--text):not(.v-btn--outlined):hover:before {
  opacity: 0.08;
  color: white;
}

.app-fix {
    background: #000 !important;
}

a.router-link-active {
  color: white;
  text-decoration: none;
}

a:link {
  text-decoration: none;
  color: white;
}

a:visited {
  color: white;
  text-decoration: none;
}

.drawer-content {
  background-color: #353535 !important;
  color: #3ecbbe;
}

.icons {
  color: #3ecbbe !important;
}

@media only screen and (max-width: 680px) {
  .hamburger {
    display: block !important;
  }

  .tb-title {
    display: none;
  }

  .nav-btn {
    display: none;
  }
}
</style>

<script>
// import HelloWorld from "./components/HelloWorld";
// import Home from "./views/Home";

export default {
  name: "App",

  components: {
    // HelloWorld
    // Home
  },

  data: () => ({
    route: "hi",
    drawer: false
  })
};
</script>

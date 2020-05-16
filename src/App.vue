<template>
  <v-app>
    <v-app-bar app color="primary" dark class="nav-bar" style="position: sticky !important;">
      <v-toolbar-title>
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
    route: "hi"
  })
};
</script>

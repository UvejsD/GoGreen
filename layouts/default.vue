<template>
  <v-app dark>
    <!-- This is html code for header.-->
    <v-app-bar app flat absolute class="transparent green--text">
      <v-toolbar-title>
        <v-img :src="logo" max-width="50px" max-height="50px"></v-img>
      </v-toolbar-title>

      <v-spacer />

      <v-toolbar-items>
        <v-layout align-center>
          <v-flex>
            <v-btn
              v-for="link in links"
              :key="link"
              height="100%"
              class="font-weight-bold rounded-pill mx-1 py-1 px-2 transparent"
              :to="link.to"
            >
              <span class="white--text font-weight-light">
                {{ link.name }}
              </span>
            </v-btn>
          </v-flex>
        </v-layout>
      </v-toolbar-items>
    </v-app-bar>

    <!-- This is html code for main-->
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>

    <!-- This is html code for footer-->
    <v-footer :absolute="!fixed" app>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: "DefaultLayout",

  data: () => ({
    logo: "/logo.png",
    links: [
      { name: "Home", to: "/" },
      { name: "Knowledge Hub", to: "/Knowledge" },
      { name: "Donations", to: "/FindADoctor" },
      { name: "Petitions", to: "/Covid-19" },
      { name: "Emissions", to: "/ContactUs" },
    ],
  }),
};
</script>

<style lang="scss" scope>
@import "assets/variables";

.v-app-bar .v-toolbar__items {
  .v-btn {
    box-shadow: none;
    text-transform: none;
    .v-ripple__container {
      opacity: 0 !important;
    }
    &::before {
      opacity: 0 !important;
    }
    &--active span {
      font-weight: bold !important;
    }
  }
}
</style>
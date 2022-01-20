<template >
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <v-card class="logo py-4 d-flex justify-center">
        <NuxtLogo />
        <VuetifyLogo />
      </v-card>
      <v-card>
        <v-card-title class="headline">
          Welcome to the Vuetify + Nuxt.js template
        </v-card-title>
        <v-card-text>
          <p>
            Vuetify is a progressive Material Design component framework for
            Vue.js. It was designed to empower developers to create amazing
            applications. Lorem ipsum dolor sit amet consectetur, adipisicing
            elit. Mollitia reiciendis quo vero asperiores eius? Natus minima
            sunt, labore aspernatur odit nisi, necessitatibus ipsam vitae
            facilis in quo doloribus autem laudantium voluptatibus explicabo
            inventore rem deserunt eum impedit voluptate molestias fugiat nam?
            Enim at accusamus maiores, assumenda adipisci qui a animi ex vel
            dolorem, delectus culpa aliquid ducimus vitae alias quas similique
            quaerat aliquam quo exercitationem corporis. Dolor laudantium
            officia, in illum deserunt vero amet dignissimos! Officiis nesciunt
            natus sunt illo eos at ut inventore autem labore. Quae cum laborum
            vitae commodi nisi architecto et laboriosam enim similique, itaque
            esse iusto dolorem beatae molestiae necessitatibus quibusdam,
            reprehenderit, cumque natus quis fugit omnis dolore exercitationem
            vel ratione. Magni quia maxime perferendis fugiat iste, veritatis in
            cupiditate, ad ut dolor blanditiis, sequi minus eum reprehenderit
            neque ullam! Corrupti, assumenda nam similique ab laborum, voluptate
            unde omnis asperiores ipsa totam explicabo obcaecati ratione magni,
            impedit natus quidem sunt libero ex accusantium distinctio debitis
            molestias veniam deserunt repellat. Adipisci voluptatem, ipsa quas
            accusantium nam, suscipit quis harum, deleniti ex rem vitae maiores
            hic voluptatibus! Accusantium dolore voluptatum libero rerum cumque
            in, sequi, vero, saepe animi exercitationem veritatis et expedita!
            Illo veritatis animi rem exercitationem dolore.
          </p>
          <p>
            For more information on Vuetify, check out the
            <a
              href="https://vuetifyjs.com"
              target="_blank"
              rel="noopener noreferrer"
            >
              documentation </a
            >.
          </p>
          <p>
            If you have questions, please join the official
            <a
              href="https://chat.vuetifyjs.com/"
              target="_blank"
              rel="noopener noreferrer"
              title="chat"
            >
              discord </a
            >.
          </p>
          <p>
            Find a bug? Report it on the github
            <a
              href="https://github.com/vuetifyjs/vuetify/issues"
              target="_blank"
              rel="noopener noreferrer"
              title="contribute"
            >
              issue board </a
            >.
          </p>
          <p>
            Thank you for developing with Vuetify and I look forward to bringing
            more exciting features in the future.
          </p>
          <div class="text-xs-right">
            <em><small>&mdash; John Leider</small></em>
          </div>
          <hr class="my-3" />
          <a
            href="https://nuxtjs.org/"
            target="_blank"
            rel="noopener noreferrer"
          >
            Nuxt Documentation
          </a>
          <br />
          <a
            href="https://github.com/nuxt/nuxt.js"
            target="_blank"
            rel="noopener noreferrer"
          >
            Nuxt GitHub
          </a>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" nuxt to="/inspire"> Continue </v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>

<template>
  <v-app>
    <v-app-bar
      app
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="MultiRepo Workspace Logo"
          class="shrink mr-2"
          contain
          src="./assets/logo.png"
          transition="scale-transition"
          width="40"
        />
      </div>
      <v-toolbar-title>MultiRepo Workspace</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn
        href="https://github.com/MultiRepo-Workspace/cli/releases"
        target="_blank"
        text
      >
        <span class="mr-2">Latest Release</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn>
    </v-app-bar>

    <v-content>
      <Landing/>
    </v-content>
  </v-app>
</template>

<script>
import Landing from './components/Landing';

export default {
  name: 'App',

  components: {
    Landing,
  },
  created () {
      this.$vuetify.theme.dark = true
    },
};
</script>

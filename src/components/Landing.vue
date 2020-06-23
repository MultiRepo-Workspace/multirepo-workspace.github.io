<template>
  <v-container>
    <v-card
      class="mx-auto"
      max-width=850
      >
      <v-card-title>workspace CLI</v-card-title>
      <v-card-text class="text--primary">
      <v-img
        class="align-end"
        src="../assets/workspace-help.png"
        >
      </v-img>
      </v-card-text>
    </v-card>
    <v-card
      class="mx-auto"
      max-width=850
      >
      <v-card-title>Open workspace UI</v-card-title>
      <v-card-text class="text--primary">
      <v-img
        class="align-end"
        src="../assets/workspace-ui.png"
        >
      </v-img>
      <v-img
        class="align-end"
        src="../assets/workspace-ui-html.png"
        >
      </v-img>
      </v-card-text>
    </v-card>
  </v-container>
</template>

<script>
  export default {
    name: 'Landing',
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
margin: 40px 0 0;
}
ul {
  list-style-type: none;
padding: 0;
}
li {
display: inline-block;
margin: 0 10px;
}
a {
color: #42b983;
}
</style>

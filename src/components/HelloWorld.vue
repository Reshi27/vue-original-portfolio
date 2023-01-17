<template>
  <div class="hello">
    <v-container class="bg-surface-variant">
      <v-row no-gutters>
        <v-col v-for="n in 3" :key="n" cols="12" sm="4">
          <v-sheet class="ma-2 pa-2">
            <v-card variant="outlined">
              <v-card-title>This</v-card-title>
              <v-card-subtitle>This</v-card-subtitle>
              <v-card-text>This</v-card-text>
              <v-card-actions>This</v-card-actions>
            </v-card>
          </v-sheet>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
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

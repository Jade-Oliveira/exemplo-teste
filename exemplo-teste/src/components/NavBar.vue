<template>
  <div>
    <v-app-bar
      color="blue"
      dense
      dark
    >
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title class="title1">Projeto</v-toolbar-title>

      <v-spacer></v-spacer>

     
      <v-menu
        left
        bottom
      >
        <template v-slot:activator="{ on, attrs }">
          <v-btn
            icon
            v-bind="attrs"
            v-on="on"
          >

          </v-btn>
        </template>

        <v-list>
          <v-list-item
            v-for="n in 5"
            :key="n"
            @click="() => {}"
          >
            <v-list-item-title>Option {{ n }}</v-list-item-title>
          </v-list-item>
        </v-list>
      </v-menu>
    </v-app-bar>
    <v-img class="first-img" src="https://www.lopes.com.br/blog/wp-content/uploads/2017/02/casas-bonitas.jpg" alt="Gatinhos"></v-img>

  </div>
</template>

<script>
export default {
   name: 'NavBar'
}
</script>

<style scoped>
  .first-img {
    margin: 15px;
  }
</style>

<template>
  <v-app>
    <v-main>
      <NavBar/>
      <ProductsInfos/>
    </v-main>
  </v-app>
</template>

<script>
import NavBar from './components/NavBar';
import ProductsInfos from './components/ProductsInfos';

export default {
  name: 'App',

  components: {
    NavBar,
    ProductsInfos,
  },

  data: () => ({
    //
  }),
};
</script>

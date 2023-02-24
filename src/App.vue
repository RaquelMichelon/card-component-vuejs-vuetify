<template>
  <v-app>
    <v-row class="pa-4">
      <v-col cols="4" class="d-inline">
        <product-card
          darkCard="dark"
          cardImage="https://pixabay.com/get/g2131c585c08030f9d87aeef6eeaf80105d1d03c6db35b63e12a9ac2f032502bd6176907e0f7757236f5306c23d319704f9c3bfc171255dfee03fc1fcb8239735_640.jpg"
        />
      </v-col>

      <v-col cols="4">
        <product-card
          cardImage="https://pixabay.com/get/g2131c585c08030f9d87aeef6eeaf80105d1d03c6db35b63e12a9ac2f032502bd6176907e0f7757236f5306c23d319704f9c3bfc171255dfee03fc1fcb8239735_640.jpg"
        />
      </v-col>

      <v-col cols="4">
        <product-card
          darkCard="dark"
          cardImage="https://pixabay.com/get/g2131c585c08030f9d87aeef6eeaf80105d1d03c6db35b63e12a9ac2f032502bd6176907e0f7757236f5306c23d319704f9c3bfc171255dfee03fc1fcb8239735_640.jpg"
        />
      </v-col>
    </v-row>
  </v-app>
</template>

<script>
import ProductCard from "./components/ProductCard.vue";
export default {
  name: "App",
  components: {
    ProductCard,
  },
};
</script>

<style>
#app {
}
</style>

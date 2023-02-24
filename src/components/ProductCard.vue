<template>
  <v-card elevation="10" :theme="darkCard">
    <!-- <v-card elevation="10" :dark="darkCard"> -->

    <v-card-title class="pa-2">
      <img class="card-img rounded" :src="cardImage" />
    </v-card-title>

    <v-card-text class="pa-2">
      <h3>Vitamin B</h3>
      <div class="d-flex">
        <h4>$40</h4>
        <small class="pl-1">(Exclusive of all taxes)</small>
      </div>
      <p class="text-justify card-text">
        These vitamins help a variety of enzymes do their jobs, ranging from
        releasing energy from carbohydrates and fat to breaking down amino acids
        and transporting oxygen and energy-containing nutrients around the body.
      </p>
      <v-card-actions>
        <v-btn block rounded depressed variant="tonal">Buy Now</v-btn>
      </v-card-actions>
    </v-card-text>
  </v-card>
</template>

<script>
export default {
  props: {
    darkCard: {
      type: Boolean,
      default: () => false,
    },
    cardImage: {
      type: String,
      default: () => "",
    },
  },
};
</script>

<style scoped>
.card-img {
  height: 200px;
  width: 100%;
  object-fit: cover;
}
.card-text {
  margin-top: 10px;
  font-size: 12px;
  line-height: 15px;
}
</style>
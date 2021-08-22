<template>
  <v-container class="main-view">
    <v-row class="text-center banner-section" align="center">
      <v-col>
        <h1>Mooch Converter</h1>
        <h2>The only Mooch calculator you'll ever need</h2>
      </v-col>
    </v-row>
    <v-row class="text-center info-section" justify="center">
      <v-col cols="">
        <h3>
          This page is a small tribute to everyone's favorite ex-White House
          Communications Director,
          <a href="https://en.wikipedia.org/wiki/Anthony_Scaramucci"
            >Mr. Anthony Scaramucci</a
          >, also known as "The Mooch". Mr. Scaramucci is known for having been
          unceremoniously fired only ten days into his tenure by the 45th
          president.
          <strong>Thus 1 Mooch can be said to equal exactly 10 days.</strong>
        </h3>
      </v-col>
    </v-row>
    <v-row class="text-center info-section" justify="center">
      <v-col>
        <h3>
          But it doesn't end there. A redditor by the name of u/dbcspace created
          <strong
            >an entire system of measurement based on Mooches - The Moochric
            System</strong
          >
        </h3>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "Main",

  data: () => ({}),
};
</script>

<style>
h1,
h2,
h3 {
  font-weight: 300;
}

.main-view {
}

.banner-section {
  height: 20vh;
}

.info-section {
}
</style>

<template>
  <v-app>
    <v-app-bar color="transparent" elevate-on-scroll absolute dark>
      <img
        height="50"
        contain
        src="https://images.squarespace-cdn.com/content/5134cbefe4b0c6fb04df8065/1540481377494-6F0ZRE16VTIMGIFPVW7K/squarespace-logo-horizontal-black.jpg?format=1000w&content-type=image%2Fjpeg"
      />
      <v-spacer></v-spacer>
      <v-btn text>About</v-btn>
      <v-btn text>Works</v-btn>
      <v-btn text>Services</v-btn>
      <v-btn text>Contact</v-btn>
    </v-app-bar>
    <v-main>
      <Nuxt />
    </v-main>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          icon: 'mdi-apps',
          title: 'Welcome',
          to: '/'
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Inspire',
          to: '/inspire'
        }
      ]
    }
  }
}
</script>

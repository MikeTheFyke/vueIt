<template>
  <div id="app">
    <Header />
    <Scrappy />
    <AddFood />
  </div>
</template>

<script>
import AddFood from './components/AddFood'
import Header from './components/layout/Header'
import Scrappy from './components/Scrappy'

export default {
  name: 'App',
  components: {
    Header,
    AddFood,
    Scrappy,
  },
  data() {
    return {
      foods: [],
    }
  },
  methods: {
  }
}
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family:Arial, Helvetica, sans-serif;
  line-height: 1.4;
  background-color: white;
}

@font-face {
  font-family: "BigBottom";
  src: local("BigBottom"),
   url(./fonts/Big_Bottom_Typeface_Normal.ttf) format("truetype");
}
</style>

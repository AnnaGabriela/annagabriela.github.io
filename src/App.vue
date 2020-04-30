<template>
  <div id="app">
    <home />
  </div>
</template>

<script>
import Home from './components/Home';

export default {
  name: 'app',
  components: {
    Home,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Playfair+Display");
@import url("https://fonts.googleapis.com/css?family=Cookie|Playfair+Display");
@import url("https://fonts.googleapis.com/css?family=Roboto");
@font-face {
  font-family: "DIN";
  src: url("../static/DIN.otf");
}

html {
  background: url("../static/bg.jpeg") no-repeat center center fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}

body {
  width: 100%;
  margin: 0;
  padding: 0;
}
</style>

<template>
  <div id="app">
    <home/>
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
@import url('https://fonts.googleapis.com/css?family=Playfair+Display');
@import url('https://fonts.googleapis.com/css?family=Cookie|Playfair+Display');
@import url('https://fonts.googleapis.com/css?family=Roboto');

html { background: url('../static/img/bg.png'); }

body {
  width: 100%;
  margin: 0;
  padding: 0;
}

</style>
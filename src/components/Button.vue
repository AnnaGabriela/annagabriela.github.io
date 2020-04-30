<template>
  <div class="button">
    <a class="button-text" :href=link target="_blank">
        {{ title }}
    </a>
  </div>
</template>

<script>
export default {
  props: {
    title: String,
    link: String,
  },
};
</script>

<style scoped>
.button {
  width: 80%;
  padding: 8px 0;
  margin: 10px auto;
  border-radius: 5px;
  background-color: #C0467A;
  text-align: center;
}

.button-text {
  font-size: 0.85em;
  font-family: 'Roboto', sans-serif;
  color: white;
  text-decoration: none;
}

@media screen and (min-width: 768px) {
  .button {
    width: 150px;
    display: inline-block;
  }
}

</style>

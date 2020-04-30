<template>
  <nav class="social-media">
      <a href="https://www.linkedin.com/in/annagabrielac/"><i class="fab fa-linkedin" aria-hidden="true"></i></a>
      <a href="https://github.com/AnnaGabriela"><i class="fab fa-github" aria-hidden="true"></i></a>
      <a href="https://medium.com/@annagabrielacarvalho"><i class="fab fa-medium-m" aria-hidden="true"></i></a>
      <a href="http://behance.net/annagabrielac"><i class="fab fa-behance" aria-hidden="true"></i></a>
      <a href="https://www.meetup.com/members/185898381"><i class="fab fa-meetup" aria-hidden="true"></i></a>
      <a href="http://twitter.com/annagmc"><i class="fab fa-twitter" aria-hidden="true"></i></a>
      <a href="http://instagram.com/annagabrielacarv"><i class="fab fa-instagram" aria-hidden="true"></i></a>
  </nav>
</template>

<style scoped>
.social-media {
  text-align: center;
  margin: 30px auto 20px;
}

.social-media .fab,
.social-media .fas,
.social-media .far {
  font-size: 1.5em;
  color: #646363;
  margin: 0 5px;
}

.social-media .fab:hover,
.social-media .fas:hover,
.social-media .far:hover {
  color: #C0467A;
  transition: color .6s;
  -webkit-transition: color .6s;
}

@media screen and (min-width: 768px) {
  .social-media .fab,
  .social-media .fas,
  .social-media .far {
    font-size: 1.7em;
    margin: 0 8px;
  }
}
</style>

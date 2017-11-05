<template>
  <main class="container">
    <img src="../../static/img/profile.png" class="profile-pic" alt="profile image">
    <h1 class="name">Anna Gabriela Carvalho</h1>
    <p class="description">20. Web Developer. Graduate student in Computer Engineering at Polytechnic School of Pernambuco.</p>
    <nav class="social-media">
      <a href="http://facebook.com/annagabrielac"><i class="fa fa-facebook" aria-hidden="true"></i></a>
      <a href="https://www.instagram.com/annagabriela__"><i class="fa fa-instagram" aria-hidden="true"></i></a>
      <a href="https://www.linkedin.com/in/annagabrielac/"><i class="fa fa-linkedin" aria-hidden="true"></i></a>
      <a href="https://github.com/AnnaGabriela"><i class="fa fa-github" aria-hidden="true"></i></a>
      <a href="mailto:agmc0997@gmail.com"><i class="fa fa-envelope-o" aria-hidden="true"></i></a>
      <a href="https://drive.google.com/file/d/0BxmF2MJ1CkB2Z04xcXBrWTlOWEk/view?usp=sharing"><i class="fa fa-file-text-o" aria-hidden="true"></i></a>
    </nav>
  </main>
</template>

<style scoped>
.container {
  position: absolute;
  margin: auto;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  height: 80%;
  background-color: #fff;
}

.profile-pic {
  width: 140px;
  padding: 15px 0;
  margin: 20px auto;
  border-radius: 50%;
  display: block;
}

.profile-pic:hover {
  -ms-transform: rotate(360deg); /* IE 9 */
  -webkit-transform: rotate(360deg); /* Safari */
  transform: rotate(360deg);
  transition: transform 1s;
  -webkit-transition: transform 1s;
}

.name {
  font-family: 'Cookie', cursive;
  font-size: 3em;
  text-align: center;
  margin: 5px;
  font-weight: 300;
}

.description {
  width: 300px;
  font-family: 'Roboto', sans-serif;
  font-size: .8em;
  text-align: center;
  margin: 0 auto;
}

.social-media {
  text-align: center;
  margin-top: 30px;
}

.social-media .fa { 
  font-size: 1.6em;
  color: #000;
  margin: 0 10px;
}

.social-media .fa:hover { 
  color: #ff7665;
  transition: color .6s;
  -webkit-transition: color .6s;
}

@media screen and (min-width: 768px) {
  .container {
    width: 450px;
    height: 280px;
    border-radius: 10px; 
    border: 1.5px dashed #000;
  }

  .profile-pic { 
    margin: -75px auto 0;
  }
}
</style>
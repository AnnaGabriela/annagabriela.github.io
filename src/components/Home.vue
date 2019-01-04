<template>
  <main class="container">
    <img src="../../static/profile.png" class="profile-pic" alt="profile image">
    <h1 class="name">Anna Gabriela Carvalho</h1>
    <p class="description">
      Web developer. 21 years old. Undergraduate student in Computer Science at CESAR School.
    </p>
    <Skills/>
    <SocialMedia/>
  </main>
</template>

<script>
import SocialMedia from '@/components/SocialMedia';
import Skills from '@/components/Skills';

export default {
  components: {
    SocialMedia,
    Skills,
  },
};
</script>


<style scoped>
.container {
  width: 100%;
  height: 80vh;
  position: absolute;
  margin: auto;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background-color: #fff;
}

.profile-pic {
  width: 100px;
  margin: 15px auto;
  border-radius: 50%;
  display: block;
}

.name {
  font-family: 'DIN', 'Cookie', cursive;
  font-size: 2.2em;
  text-align: center;
  margin: 5px;
  font-weight: 300;
}

.description {
  width: 100%;
  font-family: 'DIN', 'Roboto', sans-serif;
  font-size: 0.95em;
  text-align: center;
  margin: 0 auto;
}

@media screen and (min-width: 768px) {
  .container {
    width: 520px;
    height: 340px;
    border-radius: 10px;
  }

  .description { width: 350px; }

  .profile-pic {
    width: 150px;
    padding: 10px 0;
    margin: -90px auto 0;
  }
}
</style>

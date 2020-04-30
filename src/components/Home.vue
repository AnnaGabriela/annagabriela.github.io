<template>
  <main class="container">
    <img src="../../static/profile.png" class="profile-pic" alt="profile image">
    <h1 class="name">Anna Gabriela Carvalho</h1>
    <p class="description">
      Computer Science undergraduate @ CESAR School<br>
      Director @ Women Who Code Recife
    </p>
    <p class="mail">
      annagmcarvalho@gmail.com
    </p>
    <SocialMedia/>
    <div class="buttons">
      <Button title="About Me" link="https://www.notion.so/annagabriela/My-Workspace-4961e3f09ce5429da6fe0f9e002bde68" />
      <Button title="Resume" link="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/a84cc2e9-ccb7-4d6a-b10c-c6a85de2621f/CV_-_Anna_Gabriela_Carvalho.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20200430%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20200430T175514Z&X-Amz-Expires=86400&X-Amz-Signature=58d7c996e40968ef196b81d503b58cb1f892586381dd3371fefefa839113ec59&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22CV%2520-%2520Anna%2520Gabriela%2520Carvalho.pdf%22" />
    </div>
  </main>
</template>

<script>
import SocialMedia from '@/components/SocialMedia';
import Button from '@/components/Button';

export default {
  components: {
    SocialMedia,
    Button,
  },
};
</script>


<style scoped>
.container {
  width: 90%;
  height: 460px;
  position: absolute;
  margin: auto;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background-color: #fff;
  border-radius: 10px;
}

.profile-pic {
  width: 140px;
  margin: 15px auto;
  border-radius: 50%;
  display: block;
}

.name {
  font-family: 'DIN', 'Cookie', cursive;
  font-size: 1.6em;
  text-align: center;
  margin: 5px;
  font-weight: 300;
  color: #C0467A;
}

.description {
  font-family: 'Roboto', sans-serif;
  width: 100%;
  font-size: 0.7em;
  text-align: center;
  margin: 0 auto;
  color: #707070;
}

.mail {
  font-family: 'Roboto', sans-serif;
  width: 100%;
  font-size: 0.7em;
  text-align: center;
  color: #423E37;
  margin: 20px 0;
}

@media screen and (min-width: 768px) {
  .container {
    width: 520px;
    height: 340px;
    border-radius: 10px;
  }

  .name { font-size: 1.9em; }

  .description {
    width: 350px;
    font-size: 0.9em;
  }

  .mail { font-size: 0.9em; }

  .profile-pic {
    width: 130px;
    padding: 10px 0;
    margin: -80px auto 0;
  }

  .buttons {
    width: 60%;
    margin: auto;
    display: flex;
  }
}
</style>

<script setup>

  import AppTitle from './components/AppTitle.vue';

  import AppHero from './components/AppHero.vue';

</script>

<template>

  <div class="background-img">
  </div>
  <div class="container">
    <div class="title">
      <AppTitle></AppTitle>
    </div>
    <div class="hero">
      <AppHero></AppHero>
    </div>
  </div>

</template>

<style>

body{

position: relative;

}

.background-img{
width: 100vw;
height: 100vh;

position: absolute;

background-image: url(../src/assets/Palermo\ Cattedrale.jpg);
background-size: cover;
filter: blur(10px);

}

.container{

display: flex;
justify-content: center;
align-items: center;

z-index: 99;

flex-direction: column;

}

.title {
width: 100%;

z-index: 99;

display: flex;
justify-content: center;
}

.hero {
width: 60%;

z-index: 99;

margin-top: 25px;

display: flex;
justify-content: center;
}

</style>

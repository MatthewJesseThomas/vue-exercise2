<template>
  <div class="home">
    <img class="logo" alt="Vue logo" src="../assets/1493f78c-aa64-4b8f-b4b9-08583d507242.jpg">
    <h1>Welcome to The Book Of Life E-Commerce</h1>
    <br>
    <h2 class="text-white">•Here Are Some Books•</h2>
    <div class="books">
      <img class="love" src="../assets/love-story-9781451687613_hr.jpg" alt="love">
      <img class="motivate" src="../assets/Motivational-Book.gif" alt="motivate">
    </div>
    <div class="books">
      <img class="depressed" src="../assets/The-Nature-Of-Depression.jpg" alt="depressed">
      <img class="happy" src="../assets/Art-Of-Happiness.jpg" alt="happy">
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'HomeView',
  components: {
    
  }
}
</script>
<style>
 .logo {
  height: 10rem;
  width: 10rem;
  }
  .logo:hover {
    scale: 1.1;
  }
  .books{
    margin: auto;
    display: flex;
    align-content: center;
    justify-content: space-around;
  }
  .love{
    height: 30rem;
    width: 30rem;
    margin-top: 2rem;
  }
  .motivate{
    height: 30rem;
    width: 30rem;
    margin-top: 2rem;
  }
  .depressed{
    height: 30rem;
    width: 30rem;
    margin-top: 2rem;
  }
  .happy{
    height: 30rem;
    width: 30rem;
    margin-top: 2rem;
  }
  .home{
    margin-bottom: 8rem;
  }
</style>
<template>
  <div class="home">
    <img class="imgLogo" alt="logo" src="../assets/logo.jpg" />
    <StartingPage msg="BEST Lviv starting page" />
  </div>
</template>

<script>
// @ is an alias to /src
import StartingPage from '@/components/StartingPage.vue';

export default {
  name: 'Home',
  components: {
    StartingPage
  }
};
</script>

<style lang="sass" scoped>
.imgLogo
  width: 250px;
  height: auto;
</style>

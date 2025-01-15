<template>
  <!-- <div id="app"> -->
    <!-- Hier wird die TopCard-Komponente verwendet -->
    <TopCard>
      <h1>Top Card Title</h1>
      <p>Some content inside the card.</p>
    </TopCard>
  <!-- </div> -->
</template>

<script>
import TopCard from './components/TopCard.vue';

export default {
  name: 'App',
  components: {
    TopCard,
  },
};
</script>

<style>
body {
  margin: 0;
}
#app {
  background: radial-gradient(71.11% 100% at 50% 0%, #020204 14.6%, #011F35 100%);
  width: 100vw;
  min-height: 100vh;
  padding:100px;
  box-sizing: border-box;
}
</style>

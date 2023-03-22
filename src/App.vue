<script>
  // importo il componente AppTitle
  import AppTitle from './components/AppTitle.vue';
  // importo il componente AppHero
  import AppHero from './components/AppHero.vue';
  // rendo disponibili i componenti
  export default {
    components: {
      AppTitle,
      AppHero
    }
  }
</script>

<template>
  <!-- uso il componente AppTitle come un tag -->
  <AppTitle></AppTitle>
  <AppHero></AppHero>
</template>

<style scoped>

</style>
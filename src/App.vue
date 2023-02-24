<script>
// Import del componente
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";

// Definizione del componente in pagina
export default {
  components: {
    AppTitle,
    AppHero,
  },
};
</script>

<template>
  <AppTitle />
  <AppHero />
</template>

<style scoped></style>

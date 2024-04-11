
<script>
  import AppHeader from "./components/AppHeader.vue";
  import AppFooter from "./components/AppFooter.vue";
  import AppProductsList from "./components/AppProductsList.vue";

  export default {
    components: {
      AppHeader,
      AppFooter,
      AppProductsList
    }
  }
</script>

<template>

  <AppHeader></AppHeader>

  <main>

    <AppProductsList></AppProductsList>

  </main>

  <AppFooter></AppFooter>

</template>

<style lang="scss">
  @use './style/generic';
</style>
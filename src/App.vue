
<script>
  import AppHeader from "./components/AppHeader.vue";
  import AppFooter from "./components/AppFooter.vue";
  import AppProductsList from "./components/AppProductsList.vue";
  import AppMainNav from "./components/AppMainNav.vue";

  export default {
    components: {
      AppHeader,
      AppFooter,
      AppProductsList,
      AppMainNav
    }
  }
</script>

<template>

  <AppHeader></AppHeader>

  <main>
    <AppProductsList></AppProductsList>
    <AppMainNav></AppMainNav>
  </main>

  <AppFooter></AppFooter>

</template>

<style lang="scss">
  @use './style/generic';
</style>
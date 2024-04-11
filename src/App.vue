
<script>
  import AppHeader from "./components/AppHeader.vue";
  import AppFooter from "./components/AppFooter.vue";

  export default {
    components: {
      AppHeader,
      AppFooter
    }
  }
</script>

<template>

  <AppHeader></AppHeader>
  <AppFooter></AppFooter>

</template>

<style lang="scss">
  @use './style/generic';
</style>
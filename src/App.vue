<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
  export default {
    data () {
      return {

      };
    },
    components: {
      AppHeader,
      AppMain,
      AppFooter
    },
    methods: {

    }
  }
</script>

<template>

  <header>
    <div>
      <img src="../img/dc-logo.png" alt="logo">
    </div>
  </header>

  <main>
    main
  </main>

  <footer>
    footer
  </footer>

</template>

<style lang="scss">
@use "assets/scss/main.scss" as *;
@use "assets/scss/partials/reset";
</style>

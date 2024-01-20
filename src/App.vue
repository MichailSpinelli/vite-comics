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

    <div class="header-left">
      <button>
        CHARACTER
      </button>
      <button>
        CHARACTER
      </button>
      <button>
        CHARACTER
      </button>

    </div>

  </header>

  <main>
    <div class="main-top">
      Content goes here
    </div>

    <div class="main-low">

      <div>
        <a>
          DIGITAL COMICS
        </a>
        <img src="../img/buy-comics-digital-comics.png" alt="comics">
      </div>

      <div>
        <a>
          DIGITAL COMICS
        </a>
        <img src="../img/buy-comics-digital-comics.png" alt="comics">
      </div>

      <div>
        <a>
          DIGITAL COMICS
        </a>
        <img src="../img/buy-comics-digital-comics.png" alt="comics">
      </div>

      <div>
        <a>
          DIGITAL COMICS
        </a>
        <img src="../img/buy-comics-digital-comics.png" alt="comics">
      </div>
    </div>
  </main>

  <footer>
    <div class="footer-top">

      <div class="links">
        <div>
        <h3>
          DC COMICS
        </h3>
        <a href="">
          Character
        </a>
      </div>

      <div>
        <h3>
          DC
        </h3>
        <a href="">
          Terms of use
        </a>
      </div>

      <div>
        <h3>
          SITES
        </h3>
        <a href="">
          DC
        </a>
      </div>
      </div>
     
    </div>

    <div class="footer-low">

    </div>
  </footer>

</template>

<style lang="scss">

@use "assets/scss/main.scss" as *;
@use "assets/scss/partials/reset";

header {
  display: flex;
  justify-content: space-around;
}

.header-left {
  padding: 30px;
}

.main-top {
  background-color: #1C1C1C;
  color: white;
  padding: 50px;
  font-size: 25px;
}

.main-low {
  background-color: #0282F9;
  color: white;
  padding: 50px;
  display: flex;
  justify-content: space-around;
}

.footer-top {
  background-image: url(../img/footer-bg.jpg);
  height: 100px;
}

.links {
  display: flex;
  justify-content: space-around;
}
</style>

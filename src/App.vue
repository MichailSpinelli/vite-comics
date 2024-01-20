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
    <div class="logo">
      <img src="../img/dc-logo.png" alt="logo">
    </div>

    <div class="header-right">
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

      <div class="main-links">
        <div class="main-links-img-container">
          <img src="../img/buy-comics-digital-comics.png" alt="comics">
        </div>
        <span>
          DIGITAL COMICS
        </span>
      </div>

      <div class="main-links">
        <div class="main-links-img-container">
          <img src="../img/buy-comics-merchandise.png" alt="merchandise">
        </div>
        <span>
          DC MERCHANDISE
        </span>
      </div>

      <div class="main-links">
        <div class="main-links-img-container">
          <img src="../img/buy-comics-subscriptions.png" alt="subscription">
        </div>
        <span>
          SUBSCRIPTION
        </span>
      </div>

      <div class="main-links">
        <div class="main-links-img-container">
          <img src="../img/buy-comics-shop-locator.png" alt="shop locator">
        </div>
        <span>
          COMIC SHOP LOCATOR
        </span>
      </div>

      <div class="main-links">
        <div class="main-links-img-container">
          <img src="../img/buy-dc-power-visa.svg" alt="visa">
        </div>
        <span>
          DC POWER VISA
        </span>
      </div>

    </div>
  </main>

  <footer>
    <div class="footer-top">

      <div class="links">

          <h3>
            DC COMICS
          </h3>

          <div class="footer-links">

            <a href="">
            Character
            </a>
            <a href="">
              Character
            </a>
            <a href="">
              Character
            </a>
            <a href="">
              Character
            </a>
            <a href="">
              Character
            </a>

          </div>
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
  padding: 30px;
}

.logo{
  height: 50px;
  width: 50px;
  background-color: red;
}

.logo img {
  max-width: 100%;
}

.main-top {
  background-color: #1C1C1C;
  color: white;
  padding: 30px;
  font-size: 15px;
}

.main-low {
  background-color: #0282F9;
  color: white;
  padding: 50px;
  display: flex;
  justify-content: space-around;
}

.main-low > * {
  font-size: 0.8em;
}

.main-links {
  display: flex;
  justify-content: center;
  align-items: center;
}

.main-links-img-container{
    height: 40px;
    width: 40px;
    margin-right: 10px;
}

.main-links-img-container img{
    width: 100%;
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

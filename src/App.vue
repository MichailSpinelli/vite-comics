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
      <a href="">CHARACTER</a>
      <a href="">CHARACTER</a>
      <a href="">CHARACTER</a>
      <a href="">CHARACTER</a>
      <a href="">CHARACTER</a>
      <a href="">CHARACTER</a>
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

          <div class="links-first">
              <h3>
                DC COMICS
              </h3>
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

          <div class="links-second">
              <h3>
                DC COMICS
              </h3>
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

          <div class="links-third">
              <h3>
                DC COMICS
              </h3>
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

      </div>

    <div class="footer-low">
      
      <div class="footer-low-left">
        <button class="sign-up">
          SIGN-UP NOW!
        </button>
      </div>

      <div class="footer-low-right">
        <span class="follow-us">
          FOLLOW US
        </span>
        <span class="footer-logo">
          <img src="../img/footer-facebook.png" alt="logo-facebook">
        </span>
        <span class="footer-logo">
          <img src="../img/footer-twitter.png" alt="logo-twitter">
        </span>
        <span class="footer-logo">
          <img src="../img/footer-youtube.png" alt="logo-yt">
        </span>
        <span class="footer-logo">
          <img src="../img/footer-pinterest.png" alt="logo-pinterest">
        </span>
        <span class="footer-logo">
          <img src="../img/footer-periscope.png" alt="logo-periscope">
        </span>
      </div>

    </div>

  </footer>

</template>

<style lang="scss">

@use "assets/scss/main.scss" as *;
@use "assets/scss/partials/reset";

a {
  text-decoration: none;
  color: #658687;
}
header {
  display: flex;
  justify-content: space-around;
  padding: 30px;
}

.header-right > a{
  margin-left: 5px;
  margin-right: 5px;
}
.logo{
  height: 50px;
  width: 50px;
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
}


.links-first > a {
  display: block;
  font-size: 0.8em;
}

.links-second {
  margin-left: 30px;
}

.links-third {
  margin-left: 30px;
}

.links-third > a {
  display: block;
  font-size: 0.8em;
}

.links-second > a {
  display: block;
  font-size: 0.8em;
}

.links {
  display: flex;
  padding: 30px;
}

.footer-low{
  display: flex;
  justify-content: space-around;
  background-color: #1C1C1C;
}

.footer-low-right {
  display: flex;
  justify-content: center;
  align-items: center;
}

.sign-up{
  padding: 10px;
  border-color: #0282F9;
  background-color: #1C1C1C;
  color: azure;
}

.follow-us {
  color: #0282F9;
}

.footer-low-left > *{
  margin-top: 20px;
}

.footer-low-right > *{
  margin-top: 20px;
  padding: 5px;
}
</style>

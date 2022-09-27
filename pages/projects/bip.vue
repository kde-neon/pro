<template>
  <!-- Bip information app root -->
  <div class="root">
    <!-- bip home static slide container -->
    <div class="bip-slide">
      <!-- bip logo container -->
      <div class="logo">
        <img class="def" src="../../asset/img/bip-logo.png" alt="bip app logo ⨉ icon" />
      </div>

      <!-- Main information flex box -->
      <div class="flex maininf">
        <!-- bip app main info container -->
        <div class="bip-info-main">
          <!-- bip main info text container -->
          <div class="bip-min-text">
            <h2>HD Quality Calls on BiP!</h2>
            <p>
              Another first from BiP, the leader of innovations! Thanks to the Voice and
              Video Call feature that can be made in HD quality for up to 15 people, you
              can reach all your loved ones, family and friends by talking to them!
            </p>
          </div>

          <!-- bip button container -->
          <div class="down-btn flex">
            <a href="https://" target="_blank" class="ico-btn flex def">
              <div @click.right.prevent="" class="ico">
                <img class="def" src="../../asset/img/appstore.png" alt="app store bip app" >
              </div>
              <span>Android</span>
            </a>
            <a href="https://" target="_blank" class="ico-btn flex def">
              <div @click.right.prevent="" class="ico">
                <img class="def" src="../../asset/img/playstore.png" alt="google play store bip app" >
              </div>
              <span>iPhone</span>
            </a>
          </div>
        </div>

      <!-- bip bable container -->
      <div class="bable-container">
        <div class="bable b1"></div>
        <div class="bable b2"></div>
        <div class="bable b3"></div>
        <div class="bable b4"></div>
        <div class="bable b5"></div>
      </div>

        <!-- bip app preview container -->
        <div class="bip-app-preview">
          <!-- bip app image preview container -->
          <div @click.right.prevent="" class="img">
            <img
              class="def"
              src="../../asset/img/bip-app.png"
              alt="Bip chat application"
            />
          </div>

          <!-- bip app image back card -->
          <div class="bip-card">
            <div class="card-bg r1"></div>
            <div class="card-bg r2"></div>
          </div>
        </div>
      </div>


      <!-- slide left bable conatiner -->
      <div class="slide-left-bable">
        <div class="bable-ee"></div>
        <div class="bable-e"></div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      name: "Bip chat app",
    };
  },
};
</script>
<style scoped>
/* root all style for default element no class */
img {
  width: 100%;
}

a {
  color: #000;
  text-decoration: none;
}

/* bip slide container */
.bip-slide {
  height: 100vh;
}

/* bip logo */
.logo {
  width: 50px;
  height: 50px;
  margin-top: 15px;
  margin-left: 15px;
}

/* Slide main info flex box */
.maininf {
  width: 95%;
  max-width: 1300px;
  margin: 0 auto;
  align-items: center;
  overflow-wrap: break-word;
  justify-content: space-between;
}

@media only screen and (max-width: 768px) {
  .maininf {
    width: 95%;
    flex-direction: column-reverse;
  }
}

/* bip main info container */
.bip-info-main {
  width: 100%;
  z-index: 9;
  position: relative;
  max-width: 500px;
}

/* bip info main paragrap */
.bip-info-main p {
  color: #505050;
  line-height: normal;
}

/* bip main info text container */
.bip-min-text {
  margin-left: 15px;
  text-align: left;
}

/* download button container */
.down-btn {
  width: 95%;
  margin: 20px 0;
  align-items: center;
}

/* download button container span text area */
.down-btn span {
  color: #003b03;
}

/* download button with icon */
.ico-btn {
  width: 110px;
  max-width: 110px;
  margin: 0 10px;
  padding: 10px 25px;
  border-radius: 8px;
  align-items: center;
  background: #bdffdb;
  border: solid 2px #00e68e;
  justify-content: space-around;
}

/* download button icon */
.ico-btn .ico {
  width: 30px;
  height: 30px;
}

/* bip app preview container */
.bip-app-preview {
  width: 100%;
  max-width: 600px;
  position: relative;
}

/* bip app preview image container */
.bip-app-preview .img {
  position: relative;
  z-index: 99;
}

/* bip app preview image background card */
.card-bg {
  width: 130px;
  height: 130px;
  border-radius: 28px;
  position: absolute;
  z-index: 9;
}

/* controll card-bg class 2 */
.r2 {
  top: 10%;
  right: 10%;
  transform: rotate(-20deg);
  background: #c5ffe2;
}

/* controll card-bg class 1 */
.r1 {
  left: 5%;
  bottom: 19%;
  transform: rotate(20deg);
  background: #c7e4ff;
}

/* slide bable container */
.bable-container {
  width: 95%;
  height: 90%;
  max-width: 500px;
  max-height: 300px;
  position: absolute;
}

.bable {
  width: 30px;
  height: 30px;
  z-index: -9;
  position: absolute;
  pointer-events: none;
  border-radius: 50%;
  background: #ddd;
}

.b1,
.b3 {
  top: 10px;
  left: 10px;
  background: #1BC7EB;
}

.b2 {
  top: 15px;
  left: 90%;
  background: #431BEB;
}

.b3 {
  top: 35px;
  left: 80%;
  width: 20px;
  height: 20px;
  background: #EB1BDD;
}

.b4 {
  left: 4%;
  width: 15px;
  height: 15px;
  bottom: -40px;
  background: #8AEB1B;
}

.b5 {
  left: 90%;
  bottom: -90px;
  width: 25px;
  height: 25px;
  background: #EBD61B;
}

</style>

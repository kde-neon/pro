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
            <button class="ico-btn flex">
              <div class="ico">
                <svg width="100%" height="100%" viewBox="0 0 512 512">
                  <path
                    d="M333.6 153.9c-33.6 0-47.8 16.5-71.2 16.5-24 0-42.3-16.4-71.4-16.4-28.5 0-58.9 17.9-78.2 48.4-27.1 43-22.5 124 21.4 193 15.7 24.7 36.7 52.4 64.2 52.7h.5c23.9 0 31-16.1 63.9-16.3h.5c32.4 0 38.9 16.2 62.7 16.2h.5c27.5-.3 49.6-31 65.3-55.6 11.3-17.7 15.5-26.6 24.2-46.6-63.5-24.8-73.7-117.4-10.9-152.9-19.2-24.7-46.1-39-71.5-39z"
                  />
                  <path
                    d="M326.2 64c-20 1.4-43.3 14.5-57 31.6-12.4 15.5-22.6 38.5-18.6 60.8h1.6c21.3 0 43.1-13.2 55.8-30.1 12.3-16.1 21.6-38.9 18.2-62.3z"
                  />
                </svg>
              </div>
              <span>Android</span>
            </button>
            <button class="ico-btn flex">
              <div class="ico">
                <svg width="100%" height="100%" viewBox="0 0 512 512">
                  <path
                    d="M144 268.4V358c0 6.9 4.5 14 11.4 14H184v52c0 13.3 10.7 24 24 24s24-10.7 24-24v-52h49v52c0 7.5 3.4 14.2 8.8 18.6 3.9 3.4 9.1 5.4 14.7 5.4h.5c13.3 0 24-10.7 24-24v-52h27.6c7 0 11.4-7.1 11.4-13.9V192H144v76.4zM408 176c-13.3 0-24 10.7-24 24v96c0 13.3 10.7 24 24 24s24-10.7 24-24v-96c0-13.3-10.7-24-24-24zM104 176c-13.3 0-24 10.7-24 24v96c0 13.3 10.7 24 24 24s24-10.7 24-24v-96c0-13.3-10.7-24-24-24z"
                  />
                  <g>
                    <path
                      d="M311.2 89.1l18.5-21.9c.4-.5-.2-1.6-1.3-2.5-1.1-.8-2.4-1-2.7-.4l-19.2 22.8c-13.6-5.4-30.2-8.8-50.6-8.8-20.5-.1-37.2 3.2-50.8 8.5l-19-22.4c-.4-.5-1.6-.4-2.7.4s-1.7 1.8-1.3 2.5l18.3 21.6c-48.2 20.9-55.4 72.2-56.4 87.2h223.6c-.9-15.1-8-65.7-56.4-87zm-104.4 49.8c-7.4 0-13.5-6-13.5-13.3 0-7.3 6-13.3 13.5-13.3 7.4 0 13.5 6 13.5 13.3 0 7.3-6 13.3-13.5 13.3zm98.4 0c-7.4 0-13.5-6-13.5-13.3 0-7.3 6-13.3 13.5-13.3 7.4 0 13.5 6 13.5 13.3 0 7.3-6.1 13.3-13.5 13.3z"
                    />
                  </g>
                </svg>
              </div>
              <span>iPhone</span>
            </button>
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
  margin: 20px 0;
  align-items: center;
}

/* download button with icon */
.ico-btn {
  width: 200px;
  margin: 0 10px;
  padding: 10px 25px;
  border-radius: 8px;
  align-items: center;
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

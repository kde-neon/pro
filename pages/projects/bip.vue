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
                <img
                  class="def"
                  src="../../asset/img/appstore.png"
                  alt="app store bip app"
                />
              </div>
              <span>iPhone</span>
            </a>
            <a href="https://" target="_blank" class="ico-btn flex def">
              <div @click.right.prevent="" class="ico">
                <img
                  class="def"
                  src="../../asset/img/playstore.png"
                  alt="google play store bip app"
                />
              </div>
              <span>Android</span>
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

    <!-- bip chat secure container -->
    <div class="chat-secure flex">
      <!-- chat secure box with image -->
      <div @click.right.prevent="" class="chat-img">
        <img
          class="def"
          title="Secure chat"
          src="../../asset/img/secure-chat.png"
          alt="bip application secure chat with privecy"
        />

        <!-- card -->
        <div class="card-layer"></div>
      </div>

      <!-- chat secure text area -->
      <div class="chat-text-area">
        <h2>Free and Secure Messaging</h2>
        <p>
          BiP provides you free, secure and entertaining environment for all your
          communication needs such as one-to-one and group messaging, disappearing
          messages, location tracking, buzz and hundreds of local stickers.
        </p>
      </div>
    </div>

    <!-- chat language container cover -->
    <div class="f-right flex">
      <!-- bip chat secure container -->
      <div class="chat-lang flex">
        <!-- chat secure box with image -->
        <div @click.right.prevent="" class="chat-img">
          <img
            class="def"
            title="Secure chat"
            src="../../asset/img/chat-lang.png"
            alt="bip application secure chat with privecy"
          />

          <!-- card -->
          <div class="card-layer"></div>
        </div>

        <!-- chat secure text area -->
        <div class="chat-text-area">
          <h2>Free and Secure Messaging</h2>
          <p>
            BiP provides you free, secure and entertaining environment for all your
            communication needs such as one-to-one and group messaging, disappearing
            messages, location tracking, buzz and hundreds of local stickers.
          </p>
        </div>
      </div>
    </div>

    <!-- Bip feture container -->
    <div class="bip-feture flex">
      <h2>Bip feture</h2>
      <span>some wassam feture of bip</span>
      <br /><br />

      <!-- feture section cover left -->
      <div class="flex bip-feture-cover bfc-left">
        <!-- feture section -->
        <div class="feture-section flex">
          <!-- feture text area -->
          <div class="feture-text-area fta-left">
            <h2>Secure, Encrypted, Transparent</h2>
            <p>
              Your data is encrypted and not shared with anyone. BiP does not impose or
              discriminate on its users in or der to obtain permission.
            </p>
          </div>

          <!-- feture icon contianer -->
          <div class="feture-icon">
            <img
              width="100%"
              class="def"
              src="../../asset/img/securechat.png"
              alt="secure chat"
              title="secure chat message"
            />
          </div>
        </div>
      </div>

      <!-- break div -->
      <div class="line-break"></div>

      <!-- feture section cover right -->
      <div class="flex bip-feture-cover bfc-right">
        <!-- feture section -->
        <div class="feture-section fs-right flex">
          <!-- feture text area -->
          <div class="feture-text-area fta-right">
            <h2>Personalization</h2>
            <p>
              Add the features you use the most to the main menu and have a special BiP
              experience!
            </p>
          </div>

          <!-- feture icon contianer -->
          <div @click.right.prevent="" class="feture-icon">
            <img
              width="100%"
              class="def"
              src="../../asset/img/kisisellestir.png"
              alt="secure chat"
              title="secure chat message"
            />
          </div>
        </div>
      </div>

      <!-- break div -->
      <div class="line-break"></div>

      <!-- feture section cover left -->
      <div class="flex bip-feture-cover bfc-left">
        <!-- feture section -->
        <div class="feture-section flex">
          <!-- feture text area -->
          <div class="feture-text-area fta-left">
            <h2>Fun Stickers</h2>
            <p>
              The most beautiful stickers that will add color to your messages and have
              fun as you use them are in BiP.
            </p>
          </div>

          <!-- feture icon contianer -->
          <div @click.right.prevent="" class="feture-icon">
            <img
              width="100%"
              class="def"
              src="../../asset/img/galeri.png"
              alt="secure chat"
              title="bip chat application feture"
            />
          </div>
        </div>
      </div>

      <!-- break div -->
      <div class="line-break"></div>

      <!-- feture section cover right -->
      <div class="flex bip-feture-cover bfc-right">
        <!-- feture section -->
        <div class="feture-section fs-right flex">
          <!-- feture text area -->
          <div class="feture-text-area fta-right">
            <h2>Uninterrupted Communication with BiP Web</h2>
            <p>
              With BiP Web, your communication will not be interrupted even if your
              phone's battery runs out, and you can continue messaging, as well as making
              audio and video calls.
            </p>
          </div>

          <!-- feture icon contianer -->
          <div @click.right.prevent="" class="feture-icon">
            <img
              width="100%"
              class="def"
              src="../../asset/img/pc.png"
              alt="secure chat"
              title="bip chat application feture"
            />
          </div>
        </div>
      </div>

      <!-- break div -->
      <div class="line-break"></div>

      <!-- feture section cover left -->
      <div class="flex bip-feture-cover bfc-left">
        <!-- feture section -->
        <div class="feture-section flex">
          <!-- feture text area -->
          <div class="feture-text-area fta-left">
            <h2>Share video</h2>
            <p>
              Share high regulation max length video on bip, easy to share and download
              video
            </p>
          </div>

          <!-- feture icon contianer -->
          <div @click.right.prevent="" class="feture-icon">
            <img
              width="100%"
              class="def"
              src="../../asset/img/video.png"
              alt="secure chat"
              title="bip chat application feture"
            />
          </div>
        </div>
      </div>

      <!-- break div -->
      <div class="line-break"></div>

      <!-- feture section cover right -->
      <div class="flex bip-feture-cover bfc-right">
        <!-- feture section -->
        <div class="feture-section fs-right flex">
          <!-- feture text area -->
          <div class="feture-text-area fta-right">
            <h2>channels</h2>
            <p>You can create your channel in BiP and reach large audiences.</p>
          </div>

          <!-- feture icon contianer -->
          <div @click.right.prevent="" class="feture-icon">
            <img
              width="100%"
              class="def"
              src="../../asset/img/channel.png"
              alt="secure chat"
              title="bip chat application feture"
            />
          </div>
        </div>
      </div>

      <!-- break div -->
      <div class="line-break"></div>

      <!-- feture section cover left -->
      <div class="flex bip-feture-cover bfc-left">
        <!-- feture section -->
        <div class="feture-section flex">
          <!-- feture text area -->
          <div class="feture-text-area fta-left">
            <h2>Discover</h2>
            <p>
              With hundreds of services and channels, you can easily handle many things,
              have fun and win gifts.
            </p>
          </div>

          <!-- feture icon contianer -->
          <div @click.right.prevent="" class="feture-icon">
            <img
              width="100%"
              class="def"
              src="../../asset/img/kesfet.png"
              alt="secure chat"
              title="bip chat application feture"
            />
          </div>
        </div>
      </div>

      <!-- break div -->
      <div class="line-break"></div>

      <!-- feture section cover right -->
      <div class="flex bip-feture-cover bfc-right">
        <!-- feture section -->
        <div class="feture-section fs-right flex">
          <!-- feture text area -->
          <div class="feture-text-area fta-right">
            <h2>Money transfer</h2>
            <p>
              Just like sending a message, you can send money from BiP without the need
              for an IBAN or account number.
            </p>
          </div>

          <!-- feture icon contianer -->
          <div @click.right.prevent="" class="feture-icon">
            <img
              width="100%"
              class="def"
              src="../../asset/img/money.png"
              alt="secure chat"
              title="bip chat application feture"
            />
          </div>
        </div>
      </div>

      <!-- Download button -->
      <br /><br />
      <br /><br /><br />
      <button @click="getDownload(true)" class="btn">Download</button>
    </div>

    <transition name="down">
      <!-- Download oppup bip -->
      <div v-show="getdown" class="download-container">
        <!-- Download titile contianer -->
        <div class="title">
          <h2>Download</h2>
        </div>

        <!-- all download container -->
        <!-- bip button container -->
        <div class="down-btn get-more-down flex">
          <!-- Ios download -->
          <a href="https://" target="_blank" class="ico-btn flex def">
            <div @click.right.prevent="" class="ico">
              <img
                class="def"
                src="../../asset/img/appstore.png"
                alt="app store bip app"
              />
            </div>
            <span>iPhone</span>
          </a>

          <!-- Android download -->
          <a href="https://" target="_blank" class="ico-btn flex def">
            <div @click.right.prevent="" class="ico">
              <img
                class="def"
                src="../../asset/img/playstore.png"
                alt="google play store bip app"
              />
            </div>
            <span>Android</span>
          </a>

          <!-- Mac OS download -->
          <a href="https://" target="_blank" class="ico-btn flex def">
            <div @click.right.prevent="" class="ico">
              <svg width="100%" height="100%" viewBox="0 0 512 512">
                <path fill="#00bb01"
                  d="M333.6 153.9c-33.6 0-47.8 16.5-71.2 16.5-24 0-42.3-16.4-71.4-16.4-28.5 0-58.9 17.9-78.2 48.4-27.1 43-22.5 124 21.4 193 15.7 24.7 36.7 52.4 64.2 52.7h.5c23.9 0 31-16.1 63.9-16.3h.5c32.4 0 38.9 16.2 62.7 16.2h.5c27.5-.3 49.6-31 65.3-55.6 11.3-17.7 15.5-26.6 24.2-46.6-63.5-24.8-73.7-117.4-10.9-152.9-19.2-24.7-46.1-39-71.5-39z"
                />
                <path fill="#00bb01"
                  d="M326.2 64c-20 1.4-43.3 14.5-57 31.6-12.4 15.5-22.6 38.5-18.6 60.8h1.6c21.3 0 43.1-13.2 55.8-30.1 12.3-16.1 21.6-38.9 18.2-62.3z"
                />
              </svg>
            </div>
            <span>MacOS</span>
          </a>

          <!-- Windows download -->
          <a href="https://" target="_blank" class="ico-btn flex def">
            <div @click.right.prevent="" class="ico">
              <svg width="80%" height="100%" viewBox="0 0 512 512">
                <path fill="#00bb01"
                  d="M480 265H232v179l248 36V265zM216 265H32v150l184 26.7V265zM480 32L232 67.4V249h248V32zM216 69.7L32 96v153h184V69.7z"
                />
              </svg>
            </div>
            <span>Windows</span>
          </a>
        </div>

        <!-- close download bottom button -->
        <div class="bottom-area flex">
          <button @click="getDownload(false)" class="btn">Close</button>
        </div>
      </div>
    </transition>

    <!-- shadow -->
    <div class="shadow" v-if="shadow"></div>

    <!-- break line for -->
    <br /><br /><br />
    <br /><br /><br />

    <!-- global mobile award container -->
    <div class="award-contianer">

      <!-- Blur background layer -->
      <div class="blur-bg"></div>

      <!-- award image container -->
      <div class="award-img">
        <img width="100%" class="def" src="../../asset/img/global-mobile-awards.png" alt="global mobile awards" >
      </div>
    </div>

    <h4 class="title-center">A Leading Communication and Life Platform BiP, rewarded as "Most Innovative
    Application"!</h4>

  </div>
</template>
<style scoped>

</style>
<script>
export default {
  data() {
    return {
      name: "Bip chat app",
      shadow: false,
      getdown: false,
    };
  },
  methods: {
    getDownload(a) {
      this.shadow = a;
      this.getdown = a;
    },
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

.shadow {
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  position: fixed;
  z-index: 9999;
  background: #0000003f;
  backdrop-filter: blur(5px);
}

/* bip slide container */
.bip-slide {
  height: 100vh;
}

/* bip logo */
.logo {
  width: 50px;
  height: 50px;
  margin-top: 25px;
  margin-left: 25px;
}

/* Slide main info flex box */
.maininf {
  width: 95%;
  max-width: 1300px;
  margin: 0 auto;
  margin-top: 8%;
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
  transform: rotate(20deg);
  -o-transform: rotate(20deg);
  -moz-transform: rotate(20deg);
  -webkit-transform: rotate(20deg);
  background: #c5ffe2;
}

/* controll card-bg class 1 */
.r1 {
  left: 5%;
  bottom: 19%;
  transform: rotate(20deg);
  -o-transform: rotate(20deg);
  -moz-transform: rotate(20deg);
  -webkit-transform: rotate(20deg);
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

/* all type of bable */
.bable {
  width: 30px;
  height: 30px;
  z-index: -9;
  position: absolute;
  pointer-events: none;
  border-radius: 50%;
  background: #ddd;
}

/* bable ease element */
.b1,
.b3 {
  top: 10px;
  left: 10px;
  background: #1bc7eb;
}

/* bable ease element */
.b2 {
  top: 15px;
  left: 90%;
  background: #431beb;
}

/* bable ease element */
.b3 {
  top: 35px;
  left: 80%;
  width: 20px;
  height: 20px;
  background: #eb1bdd;
}

/* bable ease element */
.b4 {
  left: 4%;
  width: 15px;
  height: 15px;
  bottom: -40px;
  background: #8aeb1b;
}

/* bable ease element */
.b5 {
  left: 90%;
  bottom: -90px;
  width: 25px;
  height: 25px;
  background: #ebd61b;
}

/* New section
   New container */

/* all kind of card layer */
.card-layer {
  width: 90%;
  height: 90%;
  max-width: 100px;
  max-height: 100px;
  border-radius: 24px;
  position: absolute;
  bottom: 10px;
  z-index: -9;
  right: 125px;
}

/* chat secure container */
.chat-secure {
  width: 90%;
  max-width: 900px;
  align-items: center;
  flex-direction: column;
  margin: 10rem auto;
}

@media only screen and (min-width: 768px) {
  .chat-secure {
    margin: 10rem 0;
    margin-left: 30px;
    flex-direction: row;
  }
}

/* secure card card layer */
.chat-secure .card-layer {
  transform: rotate(15deg);
  -o-transform: rotate(15deg);
  -moz-transform: rotate(15deg);
  -webkit-transform: rotate(15deg);
  background: #ffe5fb;
}

/* chat secure image */
.chat-img {
  width: 95%;
  min-width: 200px;
  max-width: 600px;
  transform: rotate(-5deg);
  -o-transform: rotate(-5deg);
  -moz-transform: rotate(-5deg);
  -webkit-transform: rotate(-5deg);
}

/* every text chat area */
.chat-text-area {
  width: 100%;
  max-width: 500px;
}

/* chat text area paragrap light dark color */
.chat-text-area p {
  color: #505050;
}

/* language chat container */
.chat-lang {
  width: 90%;
  max-width: 900px;
  align-items: center;
  flex-direction: column;
  margin: 10rem auto;
}

@media only screen and (min-width: 768px) {
  .chat-lang {
    margin: 10rem 0;
    flex-direction: row-reverse;
  }
  .chat-lang .chat-text-area {
    text-align: right;
  }
}

/* chat language card layer */
.chat-lang .card-layer {
  left: 70px;
  transform: rotate(-15deg);
  -o-transform: rotate(-15deg);
  -moz-transform: rotate(-15deg);
  -webkit-transform: rotate(-15deg);
  background: #d6ffef;
}

/* chat language image container */
.chat-lang .chat-img {
  transform: rotate(5deg);
  -o-transform: rotate(5deg);
  -moz-transform: rotate(5deg);
  -webkit-transform: rotate(5deg);
}

/* language chat image drop shadow */
.chat-lang .chat-img img {
  filter: drop-shadow(0px 0px 25px #eeeeee);
  -o-filter: drop-shadow(0px 0px 25px #eeeeee);
  -moz-filter: drop-shadow(0px 0px 25px #eeeeee);
  -webkit-filter: drop-shadow(0px 0px 25px #eeeeee);
}

/* Bip feture container
✨ --> bip center feture intro */

/* bip feture */
.bip-feture {
  margin: 0 auto;
  align-items: center;
  flex-direction: column;
}

/*  feture section*/
.feture-section {
  width: 494px;
  align-items: center;
}

/* bip feture cover */
.bip-feture-cover {
  width: 100%;
  max-width: 894px;
}

/* bip feture cover left side */
.bfc-left {
  justify-content: flex-start;
}

/* bip feture cover right side */
.bfc-right {
  justify-content: flex-end;
}

/* bip feture icon container */
.feture-icon {
  width: 60px;
  min-width: 60px;
  margin: 0 20px;
}

/* bip text area left side */
.fta-left {
  text-align: right;
}

/* bip text area right side */
.fta-right {
  text-align: left;
}

/* bip feture section right */
.fs-right {
  flex-direction: row-reverse;
}

/* bip feture break large line */
.line-break {
  width: 2px;
  height: 50px;
  margin: 10px auto;
  border-radius: 25px;
  background: #e5eeff;
}

/* download app box container */
.download-container {
  top: 50%;
  left: 50%;
  width: 90%;
  padding: 35px;
  position: fixed;
  max-width: 500px;
  z-index: 9999999;
  border-radius: 8px;
  background: #ffffff;
  transform: translate(-50%, -50%) scale(1)
    matrix3d(1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1);
  -o-transform: translate(-50%, -50%) scale(1)
    matrix3d(1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1);
  -moz-transform: translate(-50%, -50%) scale(1)
    matrix3d(1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1);
  -webkit-transform: translate(-50%, -50%) scale(1)
    matrix3d(1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1);
}

/* responsive for small device download box contaienr */
@media only screen and (max-width: 600px) {
  .download-container {
    width: 100%;
    min-width: 100%;
    height: 100%;
    padding: 0;
    margin: 1px;
  }
  .bottom-area {
    bottom: 0%;
    margin: 10px;
    margin-left: -30px;
    position: absolute;
  }
  .down-enter-active,
  .down-enter-from,
  .down-enter-to {
    transform-origin: right;
    -o-transform-origin: right;
    -moz-transform-origin: right;
    -webkit-transform-origin: right;
  }
}

/* get more download contianer box all download button */
.get-more-down {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}

/* get more download button link */
.get-more-down a {
  margin: 10px 10px;
}

/* bottom area container */
.bottom-area {
  width: 100%;
  justify-content: flex-end;
}

/* ✨🎉
Download container animation */
.down-enter-active {
  filter: blur(10px);
  -o-filter: blur(10px);
  -moz-filter: blur(10px);
  -webkit-filter: blur(10px);
  transform-origin: top;
  -o-transform-origin: top;
  -moz-transform-origin: top;
  -webkit-transform-origin: top;
  transition: all 0.4s cubic-bezier(0.004, 0.2, 0.515, 1.2);
  -o-transition: all 0.4s cubic-bezier(0.004, 0.2, 0.515, 1.2);
  -moz-transition: all 0.4s cubic-bezier(0.004, 0.2, 0.515, 1.2);
  -webkit-transition: all 0.4s cubic-bezier(0.004, 0.2, 0.515, 1.2);
  transform: translate(-367%, -50%) scale(1)
    matrix3d(1, 0, 0, 0, -8, 1, 0, 0, 1, 0, 1, 0, 0, 0, 0, 1) !important;
  -o-transform: translate(-367%, -50%) scale(1)
    matrix3d(1, 0, 0, 0, -8, 1, 0, 0, 1, 0, 1, 0, 0, 0, 0, 1) !important;
  -moz-transform: translate(-367%, -50%) scale(1)
    matrix3d(1, 0, 0, 0, -8, 1, 0, 0, 1, 0, 1, 0, 0, 0, 0, 1) !important;
  -webkit-transform: translate(-367%, -50%) scale(1)
    matrix3d(1, 0, 0, 0, -8, 1, 0, 0, 1, 0, 1, 0, 0, 0, 0, 1) !important;
}

.down-enter-from {
  transform-origin: top;
  -o-transform-origin: top;
  -moz-transform-origin: top;
  -webkit-transform-origin: top;
  transform: translate(-137%, -50%) scale(1)
    matrix3d(1, 0, 0, 0, -5, 1, 0, 0, 1, 0, 1, 0, 0, 0, 0, 1) !important;
}

.down-enter-to {
  filter: blur(0px);
  -o-filter: blur(0px);
  -moz-filter: blur(0px);
  -webkit-filter: blur(0px);
  transform-origin: top;
  -o-transform-origin: top;
  -moz-transform-origin: top;
  -webkit-transform-origin: top;
  transform: translate(-20%, -50%) scale(1)
    matrix3d(1, 0, 0, 0, 0, 1, 0, 0, 1, 0, 1, 0, 0, 0, 0, 1) !important;
  -o-transform: translate(-20%, -50%) scale(1)
    matrix3d(1, 0, 0, 0, 0, 1, 0, 0, 1, 0, 1, 0, 0, 0, 0, 1) !important;
  -moz-transform: translate(-20%, -50%) scale(1)
    matrix3d(1, 0, 0, 0, 0, 1, 0, 0, 1, 0, 1, 0, 0, 0, 0, 1) !important;
  -webkit-transform: translate(-20%, -50%) scale(1)
    matrix3d(1, 0, 0, 0, 0, 1, 0, 0, 1, 0, 1, 0, 0, 0, 0, 1) !important;
}

/* ✨ Global award style section */
/* global award container */
.award-contianer {
  width: 90%;
  height: 150px;
  margin: 0 auto;
  max-width: 500px;
  border-radius: 8px;
  background: url(../../asset/img/bg.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  overflow: hidden;
  position: relative;
  box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.466);
}

/* global award image container */
.award-img {
  top: 50%;
  left: 50%;
  width: 40%;
  position: absolute;
  transform: translate(-50%, -50%);
}

/* background blur layer */
.blur-bg {
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  position: absolute;
  backdrop-filter: blur(1px);
}

/* title center */
.title-center {
  max-width: 350px;
  margin: 2rem auto;
  text-align: center;
}
</style>

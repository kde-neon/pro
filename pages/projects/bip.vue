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
            <a href="https://apps.apple.com/us/app/bip-messenger-video-call/id583274826" target="_blank" class="ico-btn flex def">
              <div @click.right.prevent="" class="ico">
                <img
                  class="def"
                  src="../../asset/img/appstore.png"
                  alt="app store bip app"
                />
              </div>
              <span>iPhone</span>
            </a>
            <a href="https://play.google.com/store/apps/details?id=com.turkcell.bip&hl=en_US&gl=US" target="_blank" class="ico-btn flex def">
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
          <a href="https://apps.apple.com/us/app/bip-messenger-video-call/id583274826" target="_blank" class="ico-btn flex def">
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
          <a href="https://play.google.com/store/apps/details?id=com.turkcell.bip&hl=en_US&gl=US" target="_blank" class="ico-btn flex def">
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
          <a href="https://bip.com/downloads/BiP-1.1.0.dmg" target="_blank" class="ico-btn flex def">
            <div @click.right.prevent="" class="ico">
              <svg width="100%" height="100%" viewBox="0 0 512 512">
                <path
                  fill="#00bb01"
                  d="M333.6 153.9c-33.6 0-47.8 16.5-71.2 16.5-24 0-42.3-16.4-71.4-16.4-28.5 0-58.9 17.9-78.2 48.4-27.1 43-22.5 124 21.4 193 15.7 24.7 36.7 52.4 64.2 52.7h.5c23.9 0 31-16.1 63.9-16.3h.5c32.4 0 38.9 16.2 62.7 16.2h.5c27.5-.3 49.6-31 65.3-55.6 11.3-17.7 15.5-26.6 24.2-46.6-63.5-24.8-73.7-117.4-10.9-152.9-19.2-24.7-46.1-39-71.5-39z"
                />
                <path
                  fill="#00bb01"
                  d="M326.2 64c-20 1.4-43.3 14.5-57 31.6-12.4 15.5-22.6 38.5-18.6 60.8h1.6c21.3 0 43.1-13.2 55.8-30.1 12.3-16.1 21.6-38.9 18.2-62.3z"
                />
              </svg>
            </div>
            <span>MacOS</span>
          </a>

          <!-- Windows download -->
          <a href="https://bip.com/downloads/BiP%20Setup%201.1.0.zip" target="_blank" class="ico-btn flex def">
            <div @click.right.prevent="" class="ico">
              <svg width="80%" height="100%" viewBox="0 0 512 512">
                <path
                  fill="#00bb01"
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

    <!-- line break -->
    <br v-for="i in 10" :key="i" />

    <!-- global mobile award container -->
    <div class="award-contianer">
      <!-- Blur background layer -->
      <div class="blur-bg"></div>

      <!-- award image container -->
      <div class="award-img">
        <img
          width="100%"
          class="def"
          src="../../asset/img/global-mobile-awards.png"
          alt="global mobile awards"
        />
      </div>
    </div>

    <!-- National awards container -->
    <div class="title-center">
      <h2>Global Mobile Awards</h2>
      <h4>
        A Leading Communication and Life Platform BiP, rewarded as "Most Innovative
        Application"!
      </h4>
    </div>

    <br /><br /><br /><br />

    <!-- break line for -->
    <div class="line-break"></div>

    <br /><br /><br /><br />

    <!-- fotter download container -->
    <div class="fotter-download">
      <!-- fotter download title -->
      <h2 class="title-center">It free to download and use</h2>

      <!-- Download contianer -->
      <div class="down-btn get-more-down flex">
        <a href="https://apps.apple.com/us/app/bip-messenger-video-call/id583274826" target="_blank" class="ico-btn flex def"
          ><div class="ico">
            <img src="../../asset/img/appstore.png" alt="app store bip app" class="def" />
          </div>
          <span>iPhone</span></a
        >
        <a href="https://play.google.com/store/apps/details?id=com.turkcell.bip&hl=en_US&gl=US" target="_blank" class="ico-btn flex def"
          ><div class="ico">
            <img
              src="../../asset/img/playstore.png"
              alt="google play store bip app"
              class="def"
            />
          </div>
          <span data-v-fa1fbe26="">Android</span></a
        >
      </div>

      <!-- Some Illustration -->
      <div class="illustration-container flex">
        <!-- Illustration one -->
        <div class="illustration-one">
          <svg width="100%" height="100%" viewBox="0 0 653.9 429.3">
            <g id="bafdd12c-8a9e-46bf-abe1-c236a42a8b97" data-name="Layer 2">
              <g id="b02829a6-0ee3-4988-93ac-02c86d6574a1" data-name="Layer 1">
                <g
                  id="e0abaf9e-5c02-4df3-ab37-194ebe86f32f"
                  data-name="freepik--Mountains--inject-66"
                >
                  <path
                    d="M70.4,309.3s18.1-37.6,20-35,1.9,8.4,1.9,8.4,40.6-133.4,49-123.8,27.1,91.5,27.1,91.5,3.9-9.7,8.4-7.1,24.5,59.9,24.5,59.9,21.9-35.4,27.7-33.5,7.7,5.1,7.7,5.1,4.5-8.4,11.6-7.7,10.3,1.9,10.3,1.9,22.5-56.7,28.3-56.1,28.4,55.4,28.4,55.4,21.3-26.4,26.4-21.9,25.1,45.8,25.1,45.8,6.5-11,12.2-9,31.6,49.6,31.6,49.6H58.9l11.5-23.5Z"
                    fill="#b2b2b2"
                  />
                  <path
                    d="M265.5,252.5h0s11.1-21.5,13.1-18.8,7.7,13.5,9.2,9.6.8-8.5,2.3-6.9,3.5,8.8,4.6,8.5,3.1-7.3,3.1-7.3,7.7,21.1,10,18.5a9.8,9.8,0,0,0,1.3-2.2c-7.1-16.3-18.3-40.4-22.1-40.9s-14.3,22.7-21.5,39.4ZM121,214.2c2.7.4,9.6-26.5,11.5-23.8s1.1,6.5,3.5,6.1,5-5.4,5.8-7.3,6.9,25,10.4,23.8,4-9,4.2-11.1c-5.3-19.6-11.2-38.7-15-43.1s-10.9,13.1-19.3,35.3c-1.3,7.5-3,19.8-1.1,20.1Zm202,45.5c-.1,2,.1,4.5,1.8,4.5s6.1-6.9,7.7-7.7,6.5,7.3,8.5,5a16.2,16.2,0,0,0,2.7-5l6.1,5.8,3.7,3.4c-4.8-9-9.5-17.2-11.6-19.1s-12.3,5.9-18.9,13.1Z"
                    fill="#d4d4d4"
                  />
                </g>
                <path
                  id="fc90f1e0-69eb-4db7-9d41-534828ca7d1e"
                  data-name="freepik--Lake--inject-66"
                  d="M381.6,365.4c-13.2,27-20.2,39.5-36.8,47.1s-73.7,16-73.7,16l-10.9.2H106.4S20.1,389.3,0,329.3H390.3s4.4,9.1-8.7,36.1Z"
                  fill="#1cc41c"
                />
                <circle
                  id="af759425-8c22-40e3-bf8d-334aaafef334"
                  data-name="freepik--Sun--inject-66"
                  cx="144.1"
                  cy="41.4"
                  r="34.3"
                  fill="#1cc41c"
                />
                <g
                  id="b1448816-faf4-4dc5-8a11-018efff8e3c2"
                  data-name="freepik--Algae--inject-66"
                >
                  <path
                    d="M279,402.1a6,6,0,0,0-2.1,1.8c-.5.8-.9,1.6-1.3,2.4a25,25,0,0,0-.9,2.5,15.7,15.7,0,0,1-.9,2.3,7.6,7.6,0,0,1-3.7,2.9l-2.4,1a16.3,16.3,0,0,0-2.5,1,4.5,4.5,0,0,0-1.4,1l-1,1.2a19.6,19.6,0,0,0-1.3,2.5l-.3.8c-.2-1.1-.4-2.3-.7-3.4a22.1,22.1,0,0,1-.5-2.5v-.9l.3-1c.6-1.6,1.1-3.4,1.6-5a30,30,0,0,0,1.1-5.2,12.4,12.4,0,0,0-.3-2.7c-.1-.9-.3-1.7-.4-2.5a58.9,58.9,0,0,1-.9-10.3,60.2,60.2,0,0,0,0,10.4,22.8,22.8,0,0,0,.2,2.6,9.6,9.6,0,0,1,0,2.4,26,26,0,0,1-1.6,4.7c-.6,1.6-1.2,3.2-1.9,4.7a5.8,5.8,0,0,0-.5,1.4,4.7,4.7,0,0,0-.1,1.7c.1,1,.2,1.8.3,2.6s.4,3.4.5,5l-.9-2.3V421a18,18,0,0,0-.8-2.1v-.2l-.5-1.2a5.6,5.6,0,0,1-.4-1.2,12.4,12.4,0,0,1-.8-4.6,7.9,7.9,0,0,1,.5-2.2c.3-.8.7-1.5,1.1-2.4a9.8,9.8,0,0,0,.8-2.8v-1.5a1.7,1.7,0,0,0-.1-.7l-.2-.7-1.5-5.2a44,44,0,0,0-1.8-5.1c.4,1.7.8,3.5,1.1,5.2s.7,3.5.9,5.2v1.2c0,.4-.1.8-.1,1.2a8.8,8.8,0,0,1-1,2.2,17.6,17.6,0,0,0-1.4,2.3,9.4,9.4,0,0,0-1,2.8,5,5,0,0,0-.2,1.2l-.6-.7a6.1,6.1,0,0,1-1.5-2.4,9.2,9.2,0,0,1-.4-2.9,47.2,47.2,0,0,1,.5-6.4c.2-2.1.6-4.3.6-6.5a9.5,9.5,0,0,0-.5-3.3,18.8,18.8,0,0,0-1.2-3,21.8,21.8,0,0,0-3.5-5.4,23.5,23.5,0,0,1,3.1,5.6,17.6,17.6,0,0,1,1,3,10.8,10.8,0,0,1,.2,3.1c-.2,2.1-.7,4.2-1,6.3s-.7,4.3-.9,6.5a10.2,10.2,0,0,0,.3,3.5,9.9,9.9,0,0,0,1.7,3.2,44.4,44.4,0,0,1,2.7,3.8v.2l.3,1.4.3,1.3.6,2.6.9,3.6c0,.1-.1.3-.1.4a6.9,6.9,0,0,1-.5,1.3l-.3.6a.8.8,0,0,0-.2.4H264a8.5,8.5,0,0,1-.4-2.3,11.4,11.4,0,0,1,.6-4.5,22.9,22.9,0,0,1,1-2.3,3.7,3.7,0,0,1,1.3-1.5,25.1,25.1,0,0,1,2.3-1.1l2.4-1.3a18.8,18.8,0,0,0,2.3-1.6,5.8,5.8,0,0,0,1.8-2.3,11.2,11.2,0,0,0,.8-2.6,18.2,18.2,0,0,1,.7-2.5,9.4,9.4,0,0,1,1-2.3,7.7,7.7,0,0,1,1.8-1.8,6.5,6.5,0,0,0,1.6-2.1,24.4,24.4,0,0,0,1-2.4A12.4,12.4,0,0,1,279,402.1Zm51.5,0a6,6,0,0,0-2.1,1.8,18.3,18.3,0,0,0-1.3,2.4,12.5,12.5,0,0,0-.9,2.5,9.4,9.4,0,0,1-1,2.3,8.2,8.2,0,0,1-3.7,2.9l-2.4,1a22.4,22.4,0,0,0-2.6,1,4.5,4.5,0,0,0-1.4,1l-1,1.2a19.6,19.6,0,0,0-1.3,2.5l-.3.8c-.2-1.1-.5-2.3-.7-3.4a22.1,22.1,0,0,1-.5-2.5v-.9l.3-1c.6-1.6,1.1-3.4,1.6-5a30,30,0,0,0,1.1-5.2,12.4,12.4,0,0,0-.3-2.7c-.1-.9-.3-1.7-.4-2.5a58.9,58.9,0,0,1-.9-10.3,60.2,60.2,0,0,0,0,10.4c.1.9.1,1.7.2,2.6a9.6,9.6,0,0,1,0,2.4,44.2,44.2,0,0,1-1.5,4.8,39,39,0,0,1-2,4.7,5.8,5.8,0,0,0-.5,1.4,4.7,4.7,0,0,0-.1,1.7c.1,1,.2,1.8.3,2.6s.4,3.4.5,5l-.9-2.3v-.2a18,18,0,0,0-.8-2.1v-.2l-.5-1.2a5.6,5.6,0,0,1-.4-1.2,12.4,12.4,0,0,1-.8-4.6,14.2,14.2,0,0,1,.5-2.2c.3-.8.7-1.5,1.1-2.4a9,9,0,0,0,.8-2.8,3.8,3.8,0,0,0,0-1.5,1.7,1.7,0,0,0-.1-.7l-.2-.7-1.5-5.2a44,44,0,0,0-1.8-5.1c.4,1.7.8,3.5,1.1,5.2l.9,5.2v1.2c0,.4-.1.8-.1,1.2a8.8,8.8,0,0,1-1,2.2,17.6,17.6,0,0,0-1.4,2.3,9.4,9.4,0,0,0-1,2.8c-.1.4-.1.8-.2,1.2l-.6-.7a6.1,6.1,0,0,1-1.5-2.4,9.2,9.2,0,0,1-.4-2.9c0-2.1.2-4.2.4-6.4s.6-4.3.6-6.5a9.5,9.5,0,0,0-.5-3.3,18.8,18.8,0,0,0-1.2-3,21.8,21.8,0,0,0-3.5-5.4,23.5,23.5,0,0,1,3.1,5.6,17.6,17.6,0,0,1,1,3,10.8,10.8,0,0,1,.2,3.1c-.2,2.1-.7,4.2-1,6.3s-.7,4.3-.9,6.5a13.5,13.5,0,0,0,.2,3.5,11.7,11.7,0,0,0,1.7,3.1,44.4,44.4,0,0,1,2.7,3.8v.2l.3,1.4.3,1.3.6,2.6.9,3.6c0,.1-.1.3-.1.4a6.9,6.9,0,0,1-.5,1.3l-.3.6a.8.8,0,0,0-.2.4H315a8.5,8.5,0,0,1-.4-2.3,11.4,11.4,0,0,1,.6-4.5,22.9,22.9,0,0,1,1-2.3,3.7,3.7,0,0,1,1.3-1.5,25.1,25.1,0,0,1,2.3-1.1l2.4-1.3a18.8,18.8,0,0,0,2.3-1.6,5.8,5.8,0,0,0,1.8-2.3,19.8,19.8,0,0,0,.8-2.6,18.2,18.2,0,0,1,.7-2.5,9.4,9.4,0,0,1,1-2.3,7.7,7.7,0,0,1,1.8-1.8,6.5,6.5,0,0,0,1.6-2.1,24.4,24.4,0,0,0,1-2.4,8.2,8.2,0,0,1-2.7,4.3ZM205,409.5a3.7,3.7,0,0,1,1.5,1.3,5.6,5.6,0,0,1,.9,1.7l.7,1.8a12.2,12.2,0,0,0,.7,1.7,5.6,5.6,0,0,0,2.7,2.1l1.7.7,1.9.7,1,.7.7.9a16.2,16.2,0,0,1,1,1.8,1.4,1.4,0,0,1,.2.6c.2-.8.3-1.7.5-2.5s.3-1.2.4-1.8v-.7c-.1-.3-.1-.5-.2-.8a24.7,24.7,0,0,1-1.1-3.6,23.3,23.3,0,0,1-.8-3.8,13.6,13.6,0,0,1,.2-2l.3-1.8a46.2,46.2,0,0,0,.6-7.4,47,47,0,0,1,0,7.5,12.3,12.3,0,0,1-.2,1.9,5.4,5.4,0,0,0,0,1.8,23.5,23.5,0,0,0,1.1,3.5,34.5,34.5,0,0,0,1.4,3.4,4.2,4.2,0,0,1,.4,1,4.9,4.9,0,0,1,.1,1.2,11.1,11.1,0,0,1-.2,1.9c-.1,1.2-.3,2.4-.4,3.6l.6-1.7V423a9.4,9.4,0,0,1,.6-1.5v-.2l.3-.9.3-.9a7.8,7.8,0,0,0,.5-3.4,7.5,7.5,0,0,0-.4-1.6l-.8-1.7a6.6,6.6,0,0,1-.6-2v-2.1c.3-1.3.7-2.5,1.1-3.7a38.2,38.2,0,0,1,1.3-3.6c-.3,1.2-.5,2.5-.8,3.8a25,25,0,0,0-.6,3.8v.9a2.8,2.8,0,0,0,.1.9,7.7,7.7,0,0,0,.7,1.6l1,1.7a11.9,11.9,0,0,1,.8,2,2.8,2.8,0,0,1,.1.9l.5-.5a6.2,6.2,0,0,0,1.1-1.7,7.6,7.6,0,0,0,.3-2.1,35.5,35.5,0,0,0-.3-4.6c-.1-1.5-.4-3.1-.4-4.7a9.9,9.9,0,0,1,.3-2.4,8.5,8.5,0,0,1,.9-2.2,19.9,19.9,0,0,1,2.5-3.9,15.6,15.6,0,0,0-2.2,4,14.2,14.2,0,0,0-.7,2.2,5.5,5.5,0,0,0-.1,2.2,40.4,40.4,0,0,0,.8,4.6c.3,1.6.5,3.1.7,4.7a6.9,6.9,0,0,1-.2,2.5,10.1,10.1,0,0,1-1.2,2.3,28.3,28.3,0,0,0-2,2.8v.2c-.1.3-.1.7-.2,1l-.2.9-.4,1.9-.6,2.6a.4.4,0,0,0,.1.3l.3.9c.1.1.1.3.2.4l.2.3h-8a4.5,4.5,0,0,0,.3-1.6,7.5,7.5,0,0,0-.4-3.3c-.2-.6-.5-1.1-.7-1.6a3.1,3.1,0,0,0-.9-1.1c-.4-.3-1.1-.5-1.6-.8l-1.7-.9-1.7-1.1a5.5,5.5,0,0,1-1.3-1.7,10.6,10.6,0,0,1-.6-1.9,12.1,12.1,0,0,0-.5-1.8l-.6-1.7a5.3,5.3,0,0,0-1.3-1.3,5.7,5.7,0,0,1-1.2-1.5l-.8-1.8a7.5,7.5,0,0,0,2.1,3Zm-56.8-32.6.8.5c-.5.5.2,1.1.6,1.5a6,6,0,0,0,1.5.9c-.6.4.3,1.4.6,1.8l.9.9c-.6.3-.1,1.3.2,1.8a13,13,0,0,0,1,1.5c0,.1.1.2,0,.2s-.1-.1-.1-.2-.9.4-.8,1.1l.3.8c-.6,0-.6.8-.6,1.3a3.7,3.7,0,0,0,.5,1.1c-.7,0-.7.8-.6,1.3a2.4,2.4,0,0,0,.2.8c-.6,0-.7.8-.7,1.3a1.8,1.8,0,0,0,.6,1.3v.3a.4.4,0,0,1-.1-.3c-.7-.8-1.1.4-1,1a2.4,2.4,0,0,0,.2.8c-.6.1-.7.8-.7,1.3a1.6,1.6,0,0,0,.5,1.1c-.7,0-.7.8-.6,1.3a1.3,1.3,0,0,0,.3.8c-.6.1-.6.8-.5,1.3a1.6,1.6,0,0,0,.9,1.2v.4l-.3-.5c-.8-.7-1,.4-.9,1.1a2.2,2.2,0,0,0,.5.8c-.6.2-.4.9-.2,1.4a3.1,3.1,0,0,0,.9,1.1c-.7.1-.3,1-.1,1.5a2.4,2.4,0,0,0,.6.8c-.6.2-.3,1.1,0,1.6a2.5,2.5,0,0,0,1.4,1.3c.1.2.1.4.2.6s-.4-.5-.6-.6-.7.8-.4,1.4a2.7,2.7,0,0,0,.7.8c-.6.3-.1,1.1.2,1.6a2.7,2.7,0,0,0,1.2.9c-.6.3.1,1.2.5,1.6l.9.6c-.5.4.2,1.2.7,1.5a2.4,2.4,0,0,0,2,.6l.6.6-1.2-.5c-1.3-.2-.4,1,.2,1.4l1,.4c-.5.5.4,1.1.9,1.4a2.8,2.8,0,0,0,1.5.4c-.5.5.3,1.1.8,1.3h.1a3.1,3.1,0,0,0,.3,1.3h5.7c.3-.3.6-.6.2-1l.9-.3c.4-.3,1.3-.8.8-1.3a4.2,4.2,0,0,0,1.5-.4c.5-.3,1.3-.9.9-1.4l1-.4c.6-.4,1.6-1.6.2-1.4l-1.2.5.6-.6a2.4,2.4,0,0,0,2-.6c.4-.4,1.2-1.1.7-1.5a2.4,2.4,0,0,0,.9-.6c.4-.4,1.1-1.2.5-1.6a2.7,2.7,0,0,0,1.2-.9c.4-.5.8-1.3.2-1.6a2.7,2.7,0,0,0,.7-.8c.3-.6.7-2.1-.4-1.4l-.6.6c.1-.2.1-.4.2-.6a2.5,2.5,0,0,0,1.4-1.3c.3-.5.6-1.4,0-1.6l.6-.8c.2-.5.6-1.4-.1-1.5a2.4,2.4,0,0,0,.9-1.1c.2-.5.4-1.3-.2-1.4a2.2,2.2,0,0,0,.5-.8c.2-.7,0-1.8-.9-1.1l-.3.5v-.4a1.8,1.8,0,0,0,.9-1.2c.1-.5.1-1.3-.5-1.3l.3-.8c.1-.5,0-1.3-.6-1.3a1.6,1.6,0,0,0,.5-1.1c0-.5,0-1.3-.7-1.3a1.9,1.9,0,0,0,.2-.8c0-.7-.3-1.9-1-1a.4.4,0,0,0-.1.3v-.3a1.6,1.6,0,0,0,.6-1.3c0-.5,0-1.3-.7-1.3a1.9,1.9,0,0,0,.2-.8c0-.5,0-1.3-.7-1.3a2.4,2.4,0,0,0,.6-1.1c.1-.5.1-1.3-.6-1.3s.3-.5.3-.8.1-2.1-.8-1.1a.3.3,0,0,0-.1.2v-.2a13,13,0,0,0,1-1.5c.2-.5.8-1.6.2-1.8l.9-.9c.3-.4,1.2-1.4.6-1.8a4.6,4.6,0,0,0,1.5-.9c.5-.4,1.1-1,.6-1.5l.8-.5c.6-.5,1.1-1.6,0-1.4a3.9,3.9,0,0,0-1.6,1,4.3,4.3,0,0,0,.2-1.1c0-.8-.7-1.8-1.1-.9s-.4,2.4.4,2.7.2-.3.3-.3a.5.5,0,0,0,0,.5c.1.1.2,0,.2.1s-.1.1-.1,0l-.3-.3-1.1,1.4a6.5,6.5,0,0,0,.4-1.3c.1-1.1-.8-1.6-1.2-.7s-1,2.7,0,3.2a4.1,4.1,0,0,1-.7,1.1l-.8,1.2a8.8,8.8,0,0,0,.2-1.6c.1-1.6-.8-1.6-1.2-.6s-.7,3.7.4,3.4.2-.5.3-.6v.4l-.3,1.1-.4,1a7.6,7.6,0,0,0-.1-1.5c-.2-1.5-1.1-1.3-1.3-.3s.2,3.2,1.2,2.8.1-.4.2-.5a.4.4,0,0,0,.1.3v1.5l-.5-.7c-.5-.8-1.4-1.2-1.3-.1a2.1,2.1,0,0,0,1.9,1.9c0,.3.1.6.1.9l-.4-.6c-.4-.5-1.7-1-1.4,0a2.7,2.7,0,0,0,1.9,1.8c.1.3.1.7.2,1v.6a3.1,3.1,0,0,0-.7-.9c-.5-.5-1.8-.9-1.4-.1s1.4,2,2.2,1.8,0-.3,0-.4h.1a5,5,0,0,1,.2,1.2v.4a2.2,2.2,0,0,0-.7-.9c-.5-.5-1.8-1-1.4-.1s1.4,2,2.2,1.8,0-.3,0-.4h0a5.9,5.9,0,0,1,.2,1.3l-.4-.5c-.4-.5-1.8-1.1-1.4-.1a3.4,3.4,0,0,0,2,1.9,1.7,1.7,0,0,1,.1.7c-.1-.1-.2-.3-.4-.4s-1.8-1.1-1.4-.1a3,3,0,0,0,1.9,1.9c.1.5.1,1,.2,1.5h0a3.3,3.3,0,0,0-.6-1c-.4-.5-1.7-1.1-1.4-.1s1.2,2.1,2.1,1.9h0v1.3a2.2,2.2,0,0,0-.5-.8c-.4-.5-1.7-1.2-1.4-.2a2.6,2.6,0,0,0,1.9,2v.8a.5.5,0,0,1-.2-.4c-.4-.5-1.6-1.2-1.4-.2a2.8,2.8,0,0,0,1.5,2c0,.2-.1.4-.1.6v-.3c-.3-.6-1.5-1.2-1.4-.2a3,3,0,0,0,1.2,2.1l-.3,1.5a2.4,2.4,0,0,0-.2-.8c-.3-.8-1.4-1.2-1.3-.2a2.2,2.2,0,0,0,1.3,2.2l-.3,1a1.9,1.9,0,0,0-.2-.7c-.3-.8-1.3-1.4-1.3-.4a2.6,2.6,0,0,0,1.1,2.4c-.1.2-.1.5-.2.7a.4.4,0,0,0-.1-.3c-.2-.8-1.1-1.5-1.2-.4a2.9,2.9,0,0,0,.6,2.4c-.1.1-.1.3-.2.5v-.2c-.1-.7-1-1.5-1.2-.5a3.1,3.1,0,0,0,.3,2.3,4.4,4.4,0,0,1-.8,1.1c0-.2.1-.4.1-.6s-.8-1.6-1.1-.7a2.3,2.3,0,0,0,.2,2.5l-.5.6c0-.2.1-.3.1-.5s-.6-1.6-1-.8a2.3,2.3,0,0,0-.1,2.5l-.4.4h0c.1-.8-.4-1.7-1-.9a2.9,2.9,0,0,0-.5,2.4.5.5,0,0,1-.3.3,1.4,1.4,0,0,0-.2-1.1c.2-.4.4-.8,0-1a2.8,2.8,0,0,0,1-.9c.6-.7,1.3-2.4-.2-1.6l-1.2,1,.5-1a3,3,0,0,0,2-1.5c.4-.6.9-1.6.1-1.9a3.3,3.3,0,0,0,.6-1c.2-.5.7-1.9-.2-1.9a3.1,3.1,0,0,0,.8-1.5c.2-.6.3-1.8-.5-1.8a2,2,0,0,0,.3-1.1c.1-.8-.3-2.5-1.1-1.2a3.2,3.2,0,0,0-.3.9c0-.2-.1-.5-.1-.7a2.7,2.7,0,0,0,.8-1.9c0-.6-.1-1.6-.9-1.6a3.6,3.6,0,0,0,.2-1.1c0-.6-.2-1.7-1-1.6a2.2,2.2,0,0,0,.2-1.4c-.1-.7-.2-1.6-1-1.6a3.4,3.4,0,0,0,.1-1c-.1-.7-.7-2.4-1.4-1.2a1.3,1.3,0,0,0-.1.6l-.2-.5a2.3,2.3,0,0,0,.5-1.8c0-.6-.3-1.6-1-1.6a3.4,3.4,0,0,0,.1-1c-.1-.6-.2-1.7-1-1.6a2.5,2.5,0,0,0,.5-1.5c0-.7,0-1.6-.8-1.6a5.4,5.4,0,0,1,.5-1.1c.5-.9.8-2.4-.5-1.3l-.4.4c0-.1.1-.3.1-.4a6.9,6.9,0,0,0,1.7-1.7c.3-.5,1.2-1.7.4-1.9l1-1c.3-.4,1.2-1.8.3-1.8a5.7,5.7,0,0,0,1.3-1.4c.3-.6.6-1.7-.1-1.8a1.7,1.7,0,0,0,.3-1c0-.8-.4-2.5-1.2-1.3s0,.2-.1.2-.1-.2-.1-.2a2.9,2.9,0,0,0,.4-1.6c-.1-.7-.4-1.7-1.1-1.6a4.1,4.1,0,0,0-.1-1.1c-.2-.6-.7-1.7-1.5-1.4a2.2,2.2,0,0,0-.2-1.6c-.3-.6-.7-1.6-1.4-1.3a4.1,4.1,0,0,0-.1-1.1c-.3-.9-1.1-2-1.5-.6a4.5,4.5,0,0,0,.2,2.3,3.9,3.9,0,0,0-1-.8c-.9-.4-2.1-.1-1.4.8s2.2,1.7,2.9.9-.1-.4-.2-.5a.4.4,0,0,0,.5.2c.2,0,.1-.2.2-.2s0,.1,0,.2l-.5.3a14.7,14.7,0,0,0,1,1.3,3.4,3.4,0,0,0-1.2-.6c-.8-.3-2.4-.1-1.4.7s2.4,1.4,3.4.9a4.7,4.7,0,0,1,.6.9,4.2,4.2,0,0,0,.4,1,3.8,3.8,0,0,0-1.2-.9c-.8-.4-2.4-.3-1.5.4s2.3,1.9,3.1,1.4-.1-.4-.1-.5l.3.3a3.6,3.6,0,0,1,.4.9c0,.3.1.6.1.9a4.3,4.3,0,0,0-.9-1c-.6-.5-2.2-.7-1.6.1s1.8,2.2,2.7,1.9,0-.4,0-.5l.2.3a4.7,4.7,0,0,1,.3,1.7,2.4,2.4,0,0,0-.6-.9c-.5-.6-2-1.2-1.6-.1a3,3,0,0,0,2.2,2.3c-.1.4-.3.8-.4,1.2a1.9,1.9,0,0,0-.2-.8c-.4-1-1.6-1.2-1.6-.1s.1,2.3,1.1,2.6a6.1,6.1,0,0,1-.7,1.4c-.2.4-.4.5-.5.8a3.2,3.2,0,0,0,.1-1.4c-.3-1.3-1.3-1-1.5-.1s-.3,3,.9,2.6.3-.5.4-.5v.2a5.6,5.6,0,0,1-.9,1.7l-.3.5a6.1,6.1,0,0,0,.1-1.4c-.3-1.3-1.3-.9-1.5,0s-.2,3,1,2.5.2-.5.3-.5.1-.2,0,.1l-.6,1.8c-.1-.2-.1-.5-.2-.7s-1.4-1.1-1.5.1a2,2,0,0,0,1.8,2.2h.2a2.9,2.9,0,0,1,.2.9l-.4-.5c-.6-.6-2.1-1.2-1.6,0a3.5,3.5,0,0,0,2.5,2.2l.6,1.9h0l-.9-1.1c-.7-.7-2.2-1-1.6,0s1.9,2.6,2.9,2.2h0a9.8,9.8,0,0,1,.5,1.6,2.8,2.8,0,0,0-.9-1c-.7-.6-2.3-1.1-1.6,0s1.7,2.2,2.9,2.1l.3,1-.4-.4c-.6-.6-2.2-1.1-1.6.1a4.1,4.1,0,0,0,2.6,2.2,1.9,1.9,0,0,1,.2.7l-.3-.3c-.6-.6-2.2-1.1-1.6.1a4.5,4.5,0,0,0,2.5,2.2c.2.5.3,1.1.5,1.7a2.7,2.7,0,0,0-.7-.8c-.7-.7-2.2-1.1-1.6.1a3.1,3.1,0,0,0,2.6,2.1,5.2,5.2,0,0,1,.2,1.1l-.6-.7c-.6-.7-2.1-1.1-1.6.1a3.2,3.2,0,0,0,2.4,2.1c0,.2.1.5.1.8s-.1-.2-.2-.2-2-1-1.6.1a3.5,3.5,0,0,0,1.9,2.2v.4c-.5-.7-1.8-1.1-1.5,0a3.8,3.8,0,0,0,1.6,2.3l-.3,1.5a1.9,1.9,0,0,0-.2-.7c-.4-.8-1.6-1.2-1.5-.1a2.8,2.8,0,0,0,1.2,2.5l-.3.9a4.3,4.3,0,0,0-.1-.5c-.3-1-1.2-1.4-1.4-.3a2.6,2.6,0,0,0,.7,2.6l-.3.6h0c-.2-1-1.1-1.6-1.4-.5a3,3,0,0,0,.1,2.6c0,.2-.1.3-.3.4h0c-.1-.7-.5-1.3-.9-1.2h-.2a2.7,2.7,0,0,0,.6-1c.1-.4.2-1.2-.3-1.3l.3-.8c.1-.6-.1-1.7-.7-.9l-.3.7v-.5a2.7,2.7,0,0,0,.7-1.4c.1-.5,0-1.2-.5-1.1a1.9,1.9,0,0,0,.2-.8c0-.4,0-1.2-.5-1.1a1.7,1.7,0,0,0,.3-1c0-.4-.1-1-.6-1a1.7,1.7,0,0,0,.1-.7c-.1-.6-.6-1.3-.9-.5a.6.6,0,0,0-.1.4c0-.1-.1-.2-.1-.3a1.3,1.3,0,0,0,.3-1.2c0-.4-.3-1-.8-.8v-.6c-.1-.4-.4-1-.9-.8a1.7,1.7,0,0,0,0-1c-.1-.4-.4-.9-.9-.8a1.3,1.3,0,0,0-.1-.6c-.2-.5-.8-1.3-1.1-.4v.1a1.4,1.4,0,0,0,.1-1.1c-.1-.4-.4-.9-.9-.8a1.3,1.3,0,0,0-.1-.6c-.1-.4-.4-1-.9-.8a1.7,1.7,0,0,0,0-1c-.1-.4-.3-1-.8-.8v-.7c-.1-.6-.5-1.6-.9-.6v0l.3-1.4c0-.5.1-1.4-.4-1.4l.3-.9c.1-.4.5-1.4-.1-1.5a4.4,4.4,0,0,0,.8-1.1c.2-.4.5-1.1,0-1.3a2.1,2.1,0,0,0,.4-.6c.3-.5.3-1.5-.4-1a2,2,0,0,0-.8,1.2,2.9,2.9,0,0,0-.2-.9c-.2-.6-1-1.1-1.1-.3s.4,1.9,1.1,1.9.1-.3.1-.3a.6.6,0,0,0,.1.4h-.2a6.5,6.5,0,0,1-.4,1.3,4.1,4.1,0,0,0-.1-1.1c-.3-.9-1-1-1.1-.1s.1,2.3.9,2.4-.1.7-.2,1a4.3,4.3,0,0,0-.2,1.1l-.3-1.3c-.4-1.2-1-.9-1-.1s.6,2.9,1.3,2.3,0-.4,0-.5.1.1.1.3.1.6.1.9v.9a2.1,2.1,0,0,0-.6-1c-.6-1-1.2-.6-1,.2s1.1,2.3,1.7,1.7-.1-.4,0-.5.1.1.1.2a4.9,4.9,0,0,1,.4,1.1l-.6-.4c-.6-.4-1.4-.5-1,.3a1.7,1.7,0,0,0,1.9.8l.4.6-.5-.3c-.5-.2-1.6-.2-1,.4a2,2,0,0,0,2,.7,2.5,2.5,0,0,1,.4.7c.1.2.1.3.2.4l-.8-.5c-.5-.2-1.6-.2-1,.4s1.6,1.1,2.1.6-.1-.2-.1-.3.1,0,.1.1a2.2,2.2,0,0,1,.5.8v.3l-.8-.5c-.5-.2-1.6-.2-1,.4s1.6,1.1,2.1.7-.1-.2-.1-.3l.6.9-.5-.2c-.4-.2-1.6-.2-1,.3a2.6,2.6,0,0,0,2.1.8l.3.5-.4-.2c-.4-.2-1.6-.3-1.1.3a2.8,2.8,0,0,0,2,.8l.6,1h0l-.7-.5c-.5-.3-1.6-.3-1.1.3s1.5,1.2,2.1.8h0l.4.9-.6-.5c-.4-.3-1.6-.4-1.1.3a1.9,1.9,0,0,0,1.9.9,1.4,1.4,0,0,1,.2.6l-.3-.2c-.4-.3-1.5-.4-1.1.3a2.3,2.3,0,0,0,1.7,1v.4l-.2-.2c-.4-.4-1.4-.4-1.1.3a2.3,2.3,0,0,0,1.5,1.2c.1.4.1.8.2,1.2l-.4-.5c-.5-.4-1.4-.5-1.1.2a2,2,0,0,0,1.6,1.3c0,.2.1.5.1.8l-.4-.5c-.4-.5-1.4-.6-1.1.1a1.9,1.9,0,0,0,1.5,1.4,1.3,1.3,0,0,0,.1.6c0-.1-.1-.1-.1-.2s-1.3-.7-1,.1a2.3,2.3,0,0,0,.6,1.6v.4h-.1c-.3-.5-1.2-.8-1-.1a2.6,2.6,0,0,0,.9,1.6c-.1.3-.1.7-.2,1s-.1-.3-.1-.5-1-.9-1-.1a1.9,1.9,0,0,0,.9,1.8c0,.1-.1.2-.1.3h-.2c-.2-.6-.9-1-1-.2a1.7,1.7,0,0,0,0,1,.5.5,0,0,0-.3.5c-.1,0-.3.1-.4.4v.4l-.4-.4a3.2,3.2,0,0,0-.5-2.3c-.7-.9-1.1.2-1,1s-.3-.2-.3-.3a3,3,0,0,0-.5-2.4c-.6-.8-1.1.1-1,.9h0l-.4-.4a2.8,2.8,0,0,0-.1-2.5c-.5-.9-1.1,0-1.1.8a.9.9,0,0,0,.1.5l-.5-.6a2.5,2.5,0,0,0,.2-2.5c-.4-.9-1.1-.1-1.1.7a1.3,1.3,0,0,0,.1.6l-.8-1.1a3.1,3.1,0,0,0,.3-2.3c-.2-1-1-.2-1.2.5v.2c-.1-.1-.1-.3-.2-.5a2.9,2.9,0,0,0,.6-2.4c-.1-1-1-.3-1.3.4s-.1.2-.1.3-.1-.5-.2-.7a2.5,2.5,0,0,0,1.1-2.4c0-1-1-.4-1.3.4a1.9,1.9,0,0,0-.2.7,3.6,3.6,0,0,1-.2-1,2.2,2.2,0,0,0,1.3-2.2c0-1-1-.5-1.3.2a2.4,2.4,0,0,0-.2.8l-.3-1.5a3,3,0,0,0,1.2-2.1c.1-1-1-.4-1.4.2s-.1.2-.2.3-.1-.4-.1-.6a2.8,2.8,0,0,0,1.5-2c.2-1-1-.4-1.4.2a.5.5,0,0,0-.2.4v-.8a2.6,2.6,0,0,0,1.9-1.9c.3-1-1-.4-1.4.2a3.5,3.5,0,0,0-.5.8v-1.3h0c.9.2,1.7-1,2.1-1.9s-1-.4-1.4.1a2.1,2.1,0,0,0-.6,1h0c.1-.5.1-1,.2-1.5a3,3,0,0,0,1.9-1.9c.4-1-1-.4-1.4.1s-.2.3-.4.4v-.7a3.6,3.6,0,0,0,2.1-1.9c.4-1-1-.4-1.4.1l-.4.5a5.9,5.9,0,0,1,.2-1.3h0s-.1.3,0,.4,1.8-.9,2.2-1.8-.9-.4-1.4.1l-.7.9v-.4a5,5,0,0,1,.2-1.2.1.1,0,0,1,.1-.1s-.1.3,0,.4,1.8-.9,2.2-1.8-.9-.5-1.4.1l-.7.9v-.6a3.6,3.6,0,0,1,.2-1,2.6,2.6,0,0,0,2-1.8c.4-1-.9-.5-1.4,0l-.4.6c0-.3.1-.6.1-.9a2,2,0,0,0,1.9-1.9c.1-1.1-.8-.7-1.3.1l-.5.7v-1.5c0-.1.1-.2.1-.3s0,.5.2.5,1.4-1.8,1.2-2.8-1.1-1.2-1.3.3a3.8,3.8,0,0,0-.1,1.5,4.2,4.2,0,0,0-.4-1,2.3,2.3,0,0,1-.3-1.1v-.4c.1.1.1.5.3.6s.8-2.4.4-3.4-1.3-1-1.2.6a8.8,8.8,0,0,0,.2,1.6,8.3,8.3,0,0,0-.8-1.2,10.5,10.5,0,0,0-.7-1.1c1-.5.4-2.3,0-3.2s-1.3-.5-1.2.7a5,5,0,0,0,.4,1.3,7.1,7.1,0,0,1-1-1.4l-.3.3h.1a.5.5,0,0,0,0-.5c.1,0,.2.4.3.3s.7-1.8.4-2.7-1.1.1-1.1.9a2,2,0,0,0,.2,1.1,3.4,3.4,0,0,0-1.6-1c-.1-1,.4.2,1,.7Zm29.9,38.9h.3l-.6.6A1.6,1.6,0,0,1,178.1,415.8Zm-1.1,2.1h.2a.1.1,0,0,0-.1.1l-.4.2.3-.4Zm-5.2,6.1c0,.1-.1.1,0,.2h.3l-1.1.4Zm1-13.4c.1-.1,0,.1,0,0s.3-.1.3-.2l-.3.8c0-.1-.1-.5,0-.6Zm-.1,2.8a.1.1,0,0,0,.1.1h.2a.1.1,0,0,0-.1.1c0,.1-.2.3-.3.4A1.1,1.1,0,0,0,172.7,413.4Zm-2.2-13.8a.4.4,0,0,1-.1-.3c0-.1.2-.2.2-.1s-.1.3-.1.4Zm-.5,26v.3c0,.1.2.1.2.1h-.8Zm-.8-3.6c0,.1,0,.2.1.2h.3a4.8,4.8,0,0,0-1.1.9Zm.1,2.2a2,2,0,0,0,0,1.1l-.9.8c0-.1.1-.3.1-.4v-.3a.5.5,0,0,0-.1-.6c0-.1,0-.1-.1-.2A1.3,1.3,0,0,0,169.3,424.2Zm-1.8.2a.4.4,0,0,0,.1.3h0c-.2.1-.5.2-.6.4A5.6,5.6,0,0,1,167.5,424.4Zm-.6,2.7.3-.2a.4.4,0,0,0,.1.3l-.2.2-.2-.3Zm-.3-7.8h.2a1.4,1.4,0,0,0-.2.6A.4.4,0,0,1,166.6,419.3Zm0,5h.1c0,.1,0,.1.1.2l-.6.8H166V425l.6-.7Zm-4.1,1.6v-.3l.6.5a.7.7,0,0,1-.6-.2h0Zm-1.8-1.7c.1-.1,0-.1,0-.2l.8.7-1.1-.4Zm-5.3-6.1h0l.3.4-.4-.2h-.1c0-.1.1,0,.2,0Zm-1-2.2h0a.5.5,0,0,1,.3.5l-.6-.6Z"
                    fill="#263238"
                  />
                </g>
                <g
                  id="b0101a6b-db6e-4841-88e9-ce64647ecacd"
                  data-name="freepik--Clouds--inject-66"
                >
                  <path
                    d="M408.1,26.5S404.7,9,389.5,2.8s-24.9,1.7-27.1,7.3-2.8,15.3-11.3,11.3-11.9-8.5-22.6-4-7.3,14.1-15.3,15.8-5.1-2.8-13.6-1.7-7.9,6.2-10.2,9-2.3.6-10.2,1.7a25.5,25.5,0,0,0-13,6.2H440.9s4.5-9-7.4-15.8-22,.7-25.4-6.1ZM171.5,64.1s-2.2-11.3-12.1-15.4-16.1,1.1-17.6,4.8-1.8,9.9-7.3,7.3-7.7-5.5-14.6-2.6-4.8,9.2-9.9,10.3-3.3-1.8-8.8-1.1-5.1,4-6.6,5.9-1.5.4-6.6,1.1a16.5,16.5,0,0,0-8.4,4H192.8s2.9-5.9-4.8-10.3-14.3.4-16.5-4Zm165.7,87.4s-1.3-6.5-6.9-8.8-9.2.6-10.1,2.7-1,5.7-4.2,4.2-4.4-3.1-8.4-1.5-2.7,5.2-5.7,5.9-1.9-1-5-.6-2.9,2.3-3.8,3.4-.8.2-3.8.6a9.4,9.4,0,0,0-4.8,2.3h64.9s1.7-3.4-2.7-5.9-8.3.2-9.5-2.3ZM89.5,169.8s-1.3-6.5-6.9-8.8-9.2.6-10.1,2.7-1.1,5.7-4.2,4.2-4.4-3.1-8.4-1.5-2.7,5.2-5.7,5.9-1.9-1.1-5-.6-2.9,2.3-3.8,3.4-.8.2-3.8.6a9.4,9.4,0,0,0-4.8,2.3h64.9s1.7-3.4-2.7-5.9-8.3.2-9.5-2.3Z"
                    fill="#fff"
                    stroke="#adadad"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                  />
                </g>
                <g
                  id="e40f5d71-aaca-43de-bc13-10e4b947ff44"
                  data-name="freepik--Trees--inject-66"
                >
                  <path
                    d="M575,183.5c0,22.6-19.3,41-43.2,41s-43.2-18.3-43.2-41,19.4-55.4,43.2-55.4S575,160.9,575,183.5Z"
                    fill="#1cc41c"
                  />
                  <path
                    d="M575,183.5c0,22.6-19.3,41-43.2,41s-43.2-18.3-43.2-41,19.4-55.4,43.2-55.4S575,160.9,575,183.5Z"
                    fill="#fff"
                    opacity="0.51"
                    style="isolation: isolate"
                  />
                  <path
                    d="M528.1,306.1l.7-88-13.1-19.8,13.1,14.6V197.7l-7.2-23.2,7.7,18.5,1.4-30.2.7,32.8.3,5.4,20.8-19.3-19.9,23.4-.3,7.8,8.6-7.1,8.7-13.1-6.1,12.2,13.5-.6-14.6,2.2-9.5,9.2.6,90.4Z"
                    fill="#787878"
                  />
                  <path
                    d="M646.7,207.2c0,18.3-15.6,33.1-34.9,33.1s-34.9-14.8-34.9-33.1,15.6-44.7,34.9-44.7,34.9,26.4,34.9,44.7Z"
                    fill="#1cc41c"
                  />
                  <path
                    d="M646.7,207.2c0,18.3-15.6,33.1-34.9,33.1s-34.9-14.8-34.9-33.1,15.6-44.7,34.9-44.7,34.9,26.4,34.9,44.7Z"
                    fill="#fff"
                    opacity="0.51"
                    style="isolation: isolate"
                  />
                  <path
                    d="M608.8,306.1l.6-71-10.6-16,10.6,11.8V218.6l-5.8-18.7,6.2,14.9,1.1-24.3.6,26.5.3,4.3,16.8-15.6-16.1,18.9-.3,6.3,7-5.8,6.9-10.5-4.9,9.9,10.9-.6-11.7,1.8-7.7,7.5.5,72.9Z"
                    fill="#787878"
                  />
                  <path
                    d="M508.1,142.9c0,30.1-25.8,54.5-57.5,54.5s-57.5-24.5-57.5-54.5,25.8-73.7,57.5-73.7S508.1,112.8,508.1,142.9Z"
                    fill="#1cc41c"
                  />
                  <path
                    d="M508.1,142.9c0,30.1-25.8,54.5-57.5,54.5s-57.5-24.5-57.5-54.5,25.8-73.7,57.5-73.7S508.1,112.8,508.1,142.9Z"
                    fill="#fff"
                    opacity="0.32"
                    style="isolation: isolate"
                  />
                  <path
                    d="M445.7,306.1l.9-117.2-17.5-26.3L446.6,182V161.8L437.1,131l10.2,24.5,1.8-40.1,1,43.7.4,7.1,27.7-25.7-26.5,31.2-.4,10.3,11.5-9.5,11.5-17.4-8.1,16.3,17.9-.9-19.3,3-12.7,12.3.8,120.3Z"
                    fill="#787878"
                  />
                  <path
                    d="M636.8,103c0,37.5-32.1,67.9-71.6,67.9s-71.6-30.4-71.6-67.9,32.1-91.7,71.6-91.7S636.8,65.6,636.8,103Z"
                    fill="#1cc41c"
                  />
                  <path
                    d="M636.8,103c0,37.5-32.1,67.9-71.6,67.9s-71.6-30.4-71.6-67.9,32.1-91.7,71.6-91.7S636.8,65.6,636.8,103Z"
                    fill="#fff"
                    opacity="0.15"
                    style="isolation: isolate"
                  />
                  <path
                    d="M559.1,306.1l1.1-145.9-21.7-32.7,21.7,24.2V126.6L548.4,88.2l12.8,30.5,2.2-49.9,1.2,54.3.5,8.9,34.5-32-33,38.9-.5,12.8,14.3-11.8,14.2-21.7-10,20.3,22.4-1.1-24.2,3.7-15.7,15.2,1,149.8Z"
                    fill="#263238"
                  />
                </g>
                <g
                  id="fccd09ec-9410-4dfb-b9fc-58de0f945519"
                  data-name="freepik--Plants--inject-66"
                >
                  <path
                    d="M405.4,303.1s1.3-4,2.5-7.2a62.2,62.2,0,0,1,4.8-8.7s-2.8,6.2-3.2,8.7a50.6,50.6,0,0,1-1.7,6.7s1.2-2,3.3-5,4.7-5.2,5-5.8-3.3,5.5-4.3,7.5a14.8,14.8,0,0,0-1.3,3.5l4-3.2,2.3-1.8-4.7,5.7,4.7-1.3-2.3,3.7H399.8l-5.9-6.5,6.5,4.3s-.3.2-1.5-3-2.8-6.5-2.8-6.5a18.7,18.7,0,0,1,4.2,5.4l2.8,4.5a27.3,27.3,0,0,1,0-7c.5-3.8.8-7.2.8-7.2l1.5,13.2Zm40.8,0s1.3-4,2.5-7.2a62.2,62.2,0,0,1,4.8-8.7s-2.8,6.2-3.2,8.7a50.6,50.6,0,0,1-1.7,6.7s1.2-2,3.3-5,4.7-5.2,5-5.8-3.3,5.5-4.3,7.5a14.8,14.8,0,0,0-1.3,3.5l4-3.2,2.3-1.8-4.7,5.7,4.7-1.3-2.3,3.7H440.6l-5.8-6.5,6.5,4.3s-.3.2-1.5-3-2.8-6.5-2.8-6.5a18.7,18.7,0,0,1,4.2,5.4l2.8,4.5a27.3,27.3,0,0,1,0-7c.5-3.8.8-7.2.8-7.2l1.4,13.2Zm71.4,0s1.3-4,2.5-7.2a62.2,62.2,0,0,1,4.8-8.7s-2.8,6.2-3.2,8.7a50.6,50.6,0,0,1-1.7,6.7s1.2-2,3.3-5,4.7-5.2,5-5.8-3.3,5.5-4.3,7.5a14.8,14.8,0,0,0-1.3,3.5l4-3.2,2.3-1.8-4.7,5.7,4.7-1.3-2.3,3.7H512.1l-5.8-6.5,6.5,4.3s-.3.2-1.5-3-2.8-6.5-2.8-6.5a18.7,18.7,0,0,1,4.2,5.4l2.8,4.5a27.3,27.3,0,0,1,0-7c.5-3.8.8-7.2.8-7.2l1.3,13.2Z"
                    fill="#1cc41c"
                  />
                  <path
                    d="M503.8,303.1s1.3-4,2.5-7.2a62.2,62.2,0,0,1,4.8-8.7s-2.8,6.2-3.2,8.7a50.6,50.6,0,0,1-1.7,6.7s1.2-2,3.3-5,4.7-5.2,5-5.8-3.3,5.5-4.3,7.5a14.8,14.8,0,0,0-1.3,3.5l4-3.2,2.3-1.8-4.7,5.7,4.7-1.3-2.3,3.7H498.2l-5.8-6.5,6.5,4.3s-.3.2-1.5-3-2.8-6.5-2.8-6.5a18.7,18.7,0,0,1,4.2,5.4l2.9,4.5a27.3,27.3,0,0,1,0-7c.5-3.8.8-7.2.8-7.2l1.3,13.2Z"
                    fill="#1cc41c"
                  />
                  <path
                    d="M489.9,303.1s1.3-4,2.5-7.2a62.2,62.2,0,0,1,4.8-8.7s-2.8,6.2-3.2,8.7a50.6,50.6,0,0,1-1.7,6.7s1.2-2,3.3-5,4.7-5.2,5-5.8-3.3,5.5-4.3,7.5a14.8,14.8,0,0,0-1.3,3.5l4-3.2,2.3-1.8-4.7,5.7,4.7-1.3-2.3,3.7H484.3l-5.8-6.5,6.5,4.3s-.3.2-1.5-3-2.8-6.5-2.8-6.5a18.7,18.7,0,0,1,4.2,5.4l2.8,4.5a27.3,27.3,0,0,1,0-7c.5-3.8.8-7.2.8-7.2l1.4,13.2Z"
                    fill="#1cc41c"
                  />
                  <path
                    d="M476.1,303.1s1.3-4,2.5-7.2a62.2,62.2,0,0,1,4.8-8.7s-2.8,6.2-3.2,8.7a50.6,50.6,0,0,1-1.7,6.7s1.2-2,3.3-5,4.7-5.2,5-5.8-3.3,5.5-4.3,7.5a14.8,14.8,0,0,0-1.3,3.5l4-3.2,2.3-1.8-4.7,5.7,4.7-1.3-2.3,3.7H470.5l-5.8-6.5,6.5,4.3s-.3.2-1.5-3-2.8-6.5-2.8-6.5a18.7,18.7,0,0,1,4.2,5.4l2.8,4.5a27.3,27.3,0,0,1,0-7c.5-3.8.8-7.2.8-7.2l1.4,13.2Z"
                    fill="#1cc41c"
                  />
                  <path
                    d="M462.2,303.1s1.3-4,2.5-7.2a62.2,62.2,0,0,1,4.8-8.7s-2.8,6.2-3.2,8.7a50.6,50.6,0,0,1-1.7,6.7s1.2-2,3.3-5,4.7-5.2,5-5.8-3.3,5.5-4.3,7.5a14.8,14.8,0,0,0-1.3,3.5l4-3.2,2.3-1.8-4.7,5.7,4.7-1.3-2.3,3.7H456.6l-5.8-6.5,6.5,4.3s-.3.2-1.5-3-2.8-6.5-2.8-6.5a18.7,18.7,0,0,1,4.2,5.4l2.8,4.5a27.3,27.3,0,0,1,0-7c.5-3.8.8-7.2.8-7.2l1.4,13.2Zm73.7-.7s1.7-5,3.2-9,6.1-11,6.1-11-3.6,7.8-4,11a60.7,60.7,0,0,1-2.1,8.4s1.5-2.5,4.2-6.3,5.9-6.5,6.3-7.4-4.2,6.9-5.5,9.5a23.5,23.5,0,0,0-1.7,4.4l5-4,3-2.3-5.9,7.1,5.9-1.7-3,4.6H528.9l-7.4-8.2,8.2,5.5s-.4.2-1.9-3.8-3.6-8.2-3.6-8.2a22.8,22.8,0,0,1,5.3,6.7l3.6,5.7a33.2,33.2,0,0,1,0-8.9c.6-4.8,1-9,1-9l1.8,16.9Zm90.2,0s1.7-5,3.2-9,6.1-11,6.1-11-3.6,7.8-4,11a57.3,57.3,0,0,1-2.1,8.4s1.5-2.5,4.2-6.3,5.9-6.5,6.3-7.4-4.2,6.9-5.5,9.5a23.5,23.5,0,0,0-1.7,4.4l5-4,3-2.3-5.9,7.1,5.9-1.7-3,4.6H619.1l-7.4-8.2,8.2,5.5s-.4.2-1.9-3.8-3.6-8.2-3.6-8.2a22.8,22.8,0,0,1,5.3,6.7l3.6,5.7a33.2,33.2,0,0,1,0-8.9c.6-4.8,1.1-9,1.1-9l1.7,16.9Z"
                    fill="#1cc41c"
                  />
                  <path
                    d="M608.6,302.4s1.7-5,3.2-9,6.1-11,6.1-11-3.6,7.8-4,11a57.3,57.3,0,0,1-2.1,8.4s1.5-2.5,4.2-6.3,5.9-6.5,6.3-7.4-4.2,6.9-5.5,9.5a23.5,23.5,0,0,0-1.7,4.4l5.1-4,2.9-2.3-5.9,7.1,5.9-1.7-2.9,4.6H601.7l-7.4-8.2,8.2,5.5s-.4.2-1.9-3.8-3.6-8.3-3.6-8.3a22.8,22.8,0,0,1,5.3,6.7l3.6,5.7a33.2,33.2,0,0,1,0-8.9c.6-4.8,1-9,1-9l1.7,17Z"
                    fill="#1cc41c"
                  />
                  <path
                    d="M591.1,302.4s1.7-5,3.2-9,6.1-11,6.1-11-3.6,7.8-4,11a57.3,57.3,0,0,1-2.1,8.4s1.5-2.5,4.2-6.3,5.9-6.5,6.3-7.4-4.2,6.9-5.5,9.5a23.5,23.5,0,0,0-1.7,4.4l5-4,3-2.3-5.9,7.1,5.9-1.7-3,4.6H584.1l-7.4-8.2,8.2,5.5s-.4.2-1.9-3.8-3.6-8.2-3.6-8.2a22.8,22.8,0,0,1,5.3,6.7l3.6,5.7a33.2,33.2,0,0,1,0-8.9c.6-4.8,1.1-9,1.1-9l1.7,16.9Z"
                    fill="#1cc41c"
                  />
                  <path
                    d="M573.6,302.4s1.7-5,3.2-9,6.1-11,6.1-11-3.6,7.8-4,11a57.3,57.3,0,0,1-2.1,8.4s1.5-2.5,4.2-6.3,5.9-6.5,6.3-7.4-4.2,6.9-5.5,9.5a23.5,23.5,0,0,0-1.7,4.4l5.1-4,2.9-2.3-5.9,7.1,5.9-1.7-2.9,4.6H566.7l-7.4-8.2,8.2,5.5s-.4.2-1.9-3.8-3.5-8.2-3.5-8.2a22.8,22.8,0,0,1,5.3,6.7l3.6,5.7a33.2,33.2,0,0,1,0-8.9c.6-4.8,1-9,1-9l1.6,16.9Z"
                    fill="#1cc41c"
                  />
                  <path
                    d="M556.1,302.4s1.7-5,3.2-9,6.1-11,6.1-11-3.6,7.8-4,11a57.3,57.3,0,0,1-2.1,8.4s1.5-2.5,4.2-6.3,5.9-6.5,6.3-7.4-4.2,6.9-5.5,9.5a23.5,23.5,0,0,0-1.7,4.4l5-4,3-2.3-5.9,7.1,5.9-1.7-3,4.6H549.1l-7.4-8.2,8.2,5.5s-.4.2-1.9-3.8-3.6-8.2-3.6-8.2a22.8,22.8,0,0,1,5.3,6.7l3.6,5.7a33.2,33.2,0,0,1,0-8.9c.6-4.8,1.1-9,1.1-9l1.7,16.9Z"
                    fill="#1cc41c"
                  />
                  <path
                    d="M566.8,302.1s1.9-5.6,3.5-10S577,280,577,280s-3.9,8.6-4.4,12.1a78.9,78.9,0,0,1-2.3,9.3s1.6-2.8,4.6-7,6.5-7.2,7-8.1-4.6,7.6-6,10.4a20.5,20.5,0,0,0-1.8,4.9l5.6-4.4,3.2-2.5-6.5,7.9,6.5-1.9-3.2,5.1H559.3l-8.1-9,9,6s-.5.2-2.1-4.2a87,87,0,0,0-4-9,24.4,24.4,0,0,1,5.8,7.4l4,6.3a39.4,39.4,0,0,1,0-9.7c.7-5.3,1.2-10,1.2-10l1.7,18.5Zm-408.1,5.4a.5.5,0,0,0-.7-.3l-.6.3c-1.4-.5-4.2-.5-8.8,0-3.2,2.6-14.5,11.2-13.9,9.6s7.7-5.9,9.1-8.9c-2.8.4-6,1-9.8,1.8-4.3,2.5-8.2,9.7-10,11.1s1.2-5.7,2-9.1l-3.9,1.3c-2.7,2.5-5.7,5.9-6,8.2s-3.5,12.1-4.2,8.7,1.4-10.3,1.6-13.5l-2.9,1.4c-1.8,1.7-3.6,2.7-6.6,8.4-4.1,7.6-3.7,12.2-5.1,15.4s-1.4-12.2-1.7-16.1a.9.9,0,0,0-.1-.5c-3,1.7-5.8,3.5-8.6,5.4-1.8,8.6,1,22.5.1,24.7s-5.2-9.1-5.7-16.2a7,7,0,0,0-1.1-3.7l-2.7,2.1c4.9-18.8,20-29.4,22-30.8l-20,13.1,7.7-17.5a53.2,53.2,0,0,0,13.8-1.6c4.6-1.3,8-5.1,12-11.6-4.9-.1-16.1,1.6-18.6.4s13.4-2.2,20.3-3.2c1.2-2,2.4-4.2,3.7-6.5-7.4-.5-17.5-.9-19.3-1.3s2.5-1.7,8.1-2.5c3.9-.5,10.7-2.1,15-3.1,1.1-2,2.3-3.9,3.6-5.8-5.4,0-17,1.3-14.1-.2s12.4-2,16.4-3.2c1.3-1.9,2.6-3.7,4-5.4-5.6.3-15.1.8-15.3.3s15-3.4,18.2-4l3.6-4.2a73.5,73.5,0,0,0-8.2-1c-2.1,0,8.1-2.9,13-4.3l3.1-3.1a1.7,1.7,0,0,0,.8-1.5.4.4,0,0,0,.2-.5.4.4,0,0,0-.6-.2l-.5.2c-1-.3-3.1-.4-6.5,0s-10.7,8.3-10.3,7,5.7-4.4,6.7-6.5l-7.2,1.3c-3.2,1.9-6.1,7.2-7.4,8.2s.9-4.2,1.5-6.8l-2.9,1c-2,1.9-4.2,4.4-4.4,6.1s-2.6,9-3.1,6.5,1-7.6,1.2-10l-2.2,1a17.3,17.3,0,0,0-4.9,6.2c-3,5.6-2.8,9-3.8,11.4s-1.1-9-1.3-11.9a.4.4,0,0,0-.1-.3l-6.4,4c-1.4,6.4.7,16.6.1,18.2s-3.9-6.7-4.2-12a5,5,0,0,0-.8-2.7,66.4,66.4,0,0,0-5.5,4.5c-.6,4.1.3,9.2,2,14.8,1.2,4.1,2,7.5,1.9,8.7l-.3.4a2.4,2.4,0,0,1-.8-.9c-1.8-2.7-5.3-16.3-6.1-19.7-2.5,2.8-4,5.3-4,7.3-.2,6.5,2.5,16.4,4.2,22.1L70.5,315.1l9.1-83-23,91.3-14-45.3,4.6,40.8c-.3-1.1-.7-2.3-1.1-3.6-.9,1.1-2,2.7-3.2,4.4l-1.4-2c1.3-2,2.6-4,3.4-5.5-.8-2.1-1.7-4.5-2.8-7-5,5.5-11.6,13.1-13,14.3s.2-3,3.1-7.9,5.1-9.6,7-13.6c-.8-2.1-1.6-4.3-2.3-6.4-3.3,4.2-9.7,14.1-9,10.9s6.1-10.9,7.8-14.8c-.6-2.2-1.2-4.4-1.7-6.5-3.2,4.5-8.8,12.3-9.3,12.1s6.7-13.9,8.2-16.7c-.4-1.9-.8-3.7-1.1-5.4a53.9,53.9,0,0,0-5.9,5.8c-1.3,1.7,2.8-8.1,4.7-12.9-.3-2-.4-3.5-.5-4.3s-.3-1.4-.7-1.6-.1-.4-.3-.5a.4.4,0,0,0-.5.3.7.7,0,0,0-.1.5c-.9.6-2.2,2.2-4,5.1,0,3-.2,13.5-.9,12.4s.1-7.2-.9-9.4l-3.5,6.5c-.5,3.7,1.8,9.2,1.8,10.9s-2.7-3.3-4.3-5.4c-.4.9-.7,1.9-1.1,2.9.2,2.7.8,6,2,7.2s5.4,7.6,3.1,6.5-5.3-5.6-7.1-7.2l-.6,2.3a17.1,17.1,0,0,0,1.8,7.7c2.5,5.9,5.3,7.8,6.5,10.1s-7.7-4.8-10.1-6.5l-.3-.2q-.6,3.8-.9,7.5c4.2,5.1,13.4,9.8,14.3,11.4s-7.7-1.2-12-4.2A5.4,5.4,0,0,0,9.7,315c-.1,2.5,0,4.9.1,7.1,2.8,3,7.4,5.5,12.8,7.7s10.4,4.9,6.9,4.5-16-6-19.1-7.6c.6,3.6,1.7,6.4,3.2,7.7,6.2,5.3,19.5,10.4,23.2,11.8l.4.8,2,25.8L21,358.9,44,400l-6.7-.4.3-2c.4-3.6-1.3-7.2-4.8-11.9-1.5,3.5-3.6,11.9-5.1,13.4h-.4c-.3-1.4,2.9-10.8,4-15.4l-3.6-4.6c-2.5,5.2-5.7,12.2-6.5,13.4s-.5-2.3.6-6.5,1.6-8.2,2.2-11.6l-3.1-4.2c-1.5,3.8-4,12.5-4.2,10s2.1-9.4,2.5-12.6c-1-1.5-1.8-3-2.7-4.4-1.4,4.1-3.8,11-4.2,11s1.9-11.7,2.4-14.1l-2-3.8a42.9,42.9,0,0,0-3.1,5.5c-.6,1.5.2-6.6.7-10.5A23.8,23.8,0,0,1,9,348.2c-.2-.6-.5-1-.8-1a.3.3,0,1,0-.6,0v.4a13,13,0,0,0-1.8,4.6c.6,2.2,2.8,10,2,9.4s-1.5-5.3-2.7-6.7c-.4,1.6-.8,3.4-1.2,5.5s3.4,6.4,3.7,7.6-2.8-1.9-4.4-3c-.1.8-.1,1.5-.2,2.4s1.9,4.3,3.1,4.9,5.7,4.5,3.7,4.1-5.1-3-6.8-3.7a10.9,10.9,0,0,0,.1,1.8,13.3,13.3,0,0,0,3,5.3c3.1,3.8,5.6,4.6,7,6s-6.7-1.9-8.9-2.5c-.1,0-.2,0-.2-.1.3,1.9.6,3.8,1,5.7,4.2,2.8,12.1,4.3,13,5.2s-5.9.8-9.8-.5a4.1,4.1,0,0,0-2.2-.2,53.6,53.6,0,0,0,1.6,5.2c2.7,1.6,6.7,2.4,11.1,2.9s8.8,1.3,6.1,1.8-13.2-1-15.8-1.4c1.2,2.6,2.6,4.4,4.1,5,5.7,2.5,16.7,3.4,19.7,3.6l2.2,2.3L28,414l11.9,15.3H56.4l70.8-.5,8.2-6.5-16.7-2.8-9.1,3.5.7-7-10.4,7.7V412.6l-8.4,5.6,2.1-9.8-14.6,7,11.3-24.3a48.8,48.8,0,0,0,5.5-1.2c6.2-1.8,10.8-7,16.2-15.6-3.4-.1-9.1.5-14.3.9h-.1c-4.8.3-9.1.4-10.7-.3-3.8-1.8,18.1-3,27.4-4.3,1.6-2.7,3.2-5.6,5-8.9-10-.6-23.6-1.2-26.1-1.7-4.1-.8,3.4-2.3,11-3.4,5.3-.7,14.5-2.8,20.2-4.1,1.5-2.7,3.2-5.3,4.8-7.8-7.3,0-23,1.7-19-.3s16.7-2.8,22.2-4.4c1.8-2.5,3.6-5,5.4-7.3-7.5.4-20.4,1-20.7.4s20.3-4.6,24.6-5.4l4.8-5.8a102,102,0,0,0-11.1-1.4c-2.8,0,10.9-4,17.6-5.9,1.9-2,3.3-3.5,4.1-4.2s1.3-1.5,1.1-2a.7.7,0,0,0,.5-.9ZM35.9,412.5l-2.1-2.2V410l2.5,2.4Zm-1-82.6c-1.7.9,1.2-3.9,4.6-9l.5,3C38,326.7,36.1,329.3,34.9,329.9Zm3.8,15.6c.9-1.1,2.6-3.1,4.3-5.5l2.6,14.5S41.1,347.9,38.7,345.5Zm28.5,39,1.3-4.4.6,1.8Zm10.1-13.6a90.6,90.6,0,0,1-3.4-10l1.5-6c.5,2.1,1,4.3,1.7,6.6s1.4,5.2,1.9,7.2l-1.7,2.2Zm23.8-64.3.2-.2Zm174.6,9.2c.1-.1.2-.2.2-.3S275.8,315.5,275.7,315.8Z"
                    fill="#263238"
                  />
                  <path
                    d="M287.4,321.4l-2.3,1.8-3.9,3.1a14,14,0,0,1,1.3-3.4c.8-1.6,3.3-5.8,4-7.1a60.6,60.6,0,0,0-4.7,5.4c-2.1,2.9-3.3,4.9-3.3,4.9a47.4,47.4,0,0,0,1.6-6.5c.3-2.5,3.1-8.5,3.1-8.5s-3.6,5.4-4.7,8.5-1.7,4.7-2.1,6.1H276l-.3-3.4.9-1-.9.7-.5-5.4.6-1-.6.7-.3-2.9s-.1,1.5-.4,3.7a42.3,42.3,0,0,0-3.4,4l-.5.6-1.3-1.8a.9.9,0,0,1,.1-.5c.3-2.5,3.1-8.5,3.1-8.5a71.5,71.5,0,0,0-4.4,7.6l-1-.9.7,1.5c0,.1-.1.2-.1.3s-1,2.9-1.5,4.1l-1.3-.9L266,324l-.8,2.5-1.3-13.1s-.3,3.3-.8,7a26.6,26.6,0,0,0,0,6.9l-2.8-4.4a16,16,0,0,0-4.1-5.2s1.6,3.3,2.8,6.4a9,9,0,0,0,1.3,2.8l-6.2-4,5.7,6.4h25.3l2.3-3.6-4.6,1.3Zm-13.6,5h-.5l-.5-.8.8-1a6.2,6.2,0,0,1,.2,1.7Zm.5-8.2-.3,2.4c-.1,1-.2,2-.2,3l-1.5,1.2-.9-1.4.2-.5c.5-1,1.7-3,2.7-4.7Zm-4,8.1a1.5,1.5,0,0,1,.2-.6c0,.1.1.2.1.3l-.3.3Zm-1.4-4.5.6,1.5-1.2,1.8h-.2l.8-3.2Zm-1.2,4.3v0Zm8.4.3.2-.4-.2.6Z"
                    fill="#263238"
                  />
                  <path
                    d="M286.5,315.8l.2-.3ZM164.6,312a.6.6,0,0,0,.1-.4C164.7,311.5,164.7,311.6,164.6,312Z"
                    fill="#263238"
                  />
                  <path
                    d="M172.9,319.2l-1.6,2.3-2.8,4a31.2,31.2,0,0,1,.9-4.4c.6-2,2.4-7.5,2.9-9.1-.5,1.1-2,3.6-3.4,7s-2.3,6.3-2.3,6.3.9-5.2,1.2-8.4A100.1,100.1,0,0,1,170,306a105.6,105.6,0,0,0-3.4,10.9c-.6,2.8-1.2,6.1-1.5,7.8h-.3l-.2-4.3.6-1.4-.6.9-.4-6.9c.2-.5.3-.9.4-1.2a3.9,3.9,0,0,0-.4.9L164,309s-.1,1.9-.3,4.7-1.7,3.4-2.4,5.1l-.3.8-.9-2.3v-.6a100.5,100.5,0,0,1,2.3-10.9s-2.1,5.7-3.1,9.8a7.5,7.5,0,0,0-.7-1.2l.5,1.9v.4c-.4,1.7-.7,3.7-1.1,5.3l-.9-1.1.8,1.6c-.4,1.9-.6,3.2-.6,3.2l-.9-16.8s-.2,4.2-.6,9a64.6,64.6,0,0,0,0,8.8l-2-5.7a23.5,23.5,0,0,0-2.9-6.7s1.2,4.2,2,8.2a21.1,21.1,0,0,0,.9,3.6l-4.5-5.3,4.1,8.2h18.1l1.6-4.6-3.3,1.7Zm-9.6,6.5-.3.2-.3-1,.6-1.3a7.4,7.4,0,0,0,0,2.1Zm.2-10.6c-.1,1-.1,2-.2,3.1s-.1,2.7-.1,3.9l-1.1,1.5-.6-1.8c.1-.2.1-.4.2-.6s1.1-4,1.8-6.1Zm-2.8,10.4a4.5,4.5,0,0,1,.1-.8c0,.2.1.3.1.4l-.2.4Zm-1-5.8c.1.6.3,1.3.4,1.9s-.6,1.7-.9,2.3l-.2-.2a29.6,29.6,0,0,0,.7-4Zm-.8,5.6v0Zm6,.3.2-.5a4.5,4.5,0,0,0-.1.8v-.3Z"
                    fill="#263238"
                  />
                  <path
                    d="M172.3,312c.1-.1.1-.2.1-.4S172.4,311.6,172.3,312Zm125.2,9.2c0-.1.1-.1.1-.2Z"
                    fill="#263238"
                  />
                  <path
                    d="M304.6,324.5l-1.4,1.1-2.4,1.9a9,9,0,0,1,.8-2.1c.5-1,2-3.5,2.4-4.3a22.2,22.2,0,0,0-2.8,3.3c-1.3,1.8-2,3-2,3a26,26,0,0,0,1-4,28.2,28.2,0,0,1,1.9-5.1,32,32,0,0,0-2.9,5.1c-.5,1.3-1,2.9-1.3,3.7h-.2l-.2-2,.5-.6-.5.4-.3-3.2.3-.6-.4.4-.2-1.8s-.1.9-.2,2.2l-2,2.4-.3.4a7.6,7.6,0,0,0-.8-1.1v-.3a28.2,28.2,0,0,1,1.9-5.1,30,30,0,0,0-2.6,4.6l-.6-.5.4.9v.2l-.9,2.5-.8-.5.7.8-.5,1.5-.8-7.9s-.2,2-.5,4.2a14.1,14.1,0,0,0,0,4.1l-1.7-2.7a8.4,8.4,0,0,0-2.5-3.1s1,2,1.7,3.8a5.3,5.3,0,0,0,.8,1.7l-3.8-2.5,3.5,3.8H303l1.4-2.2-2.8.8,3-3.3Zm-8.2,3h-.3l-.3-.5.5-.6a4.6,4.6,0,0,1,.1,1Zm.3-5a7.7,7.7,0,0,1-.2,1.5,10.9,10.9,0,0,0-.1,1.8l-.9.7-.5-.8c0-.1.1-.2.1-.3l1.6-2.9Zm-2.4,5a1.6,1.6,0,0,1,.1-.4c0,.1.1.1.1.2l-.2.2Zm-.8-2.8a3.6,3.6,0,0,0,.4.9l-.7,1.1H293l.5-1.9Zm-.8,2.7h0Zm5,.1v-.2a1,1,0,0,0-.1.4v-.2Zm6.4-6.3c0-.1.1-.1.1-.2S304.2,321,304.1,321.2Zm35.9,0c0-.1.1-.1.1-.2S340.1,321,340,321.2Z"
                    fill="#263238"
                  />
                  <path
                    d="M347,324.5l-1.4,1.1-2.4,1.9a18,18,0,0,1,.8-2.1c.5-1,2-3.5,2.4-4.3a30.4,30.4,0,0,0-2.8,3.3c-1.3,1.8-2,3-2,3a26,26,0,0,0,1-4,28.2,28.2,0,0,1,1.9-5.1,32,32,0,0,0-2.9,5.1c-.5,1.3-1,2.9-1.3,3.7h-.2l-.2-2,.5-.6-.5.4-.3-3.2.4-.6-.4.4-.2-1.8s-.1.9-.2,2.2l-2.1,2.4-.3.4a7.6,7.6,0,0,0-.8-1.1v-.3a28.2,28.2,0,0,1,1.9-5.1,30,30,0,0,0-2.6,4.6l-.6-.5.4.9v.2l-.9,2.5-.8-.5.7.8-.5,1.5-.8-7.9s-.2,2-.5,4.2a14.1,14.1,0,0,0,0,4.1l-1.7-2.7a8.4,8.4,0,0,0-2.5-3.1s1,2,1.7,3.8a5.3,5.3,0,0,0,.8,1.7l-3.8-2.5,3.5,3.8h15.2l1.4-2.2-2.8.8,3-3.3Zm-8.1,3h-.3l-.3-.5.5-.6c0,.5.1.8.1,1Zm.2-5c-.1.5-.1,1-.2,1.5a10.9,10.9,0,0,0-.1,1.8l-.9.7-.5-.8v-.3l1.6-2.9Zm-2.4,5a1.6,1.6,0,0,1,.1-.4v.2l-.2.2Zm-.8-2.8.4.9-.7,1.1h-.2l.5-1.9Zm-.7,2.7h0Zm5,.1v0Zm6.3-6.3c0-.1.1-.1.1-.2Zm-24.2,0c0-.1.1-.1.1-.2S322.4,321,322.3,321.2Z"
                    fill="#263238"
                  />
                  <path
                    d="M329.4,324.5l-1.4,1.1-2.4,1.9a18,18,0,0,1,.8-2.1c.5-1,2-3.5,2.4-4.3a22.2,22.2,0,0,0-2.8,3.3c-1.3,1.8-2,3-2,3a26,26,0,0,0,1-4,28.2,28.2,0,0,1,1.9-5.1,32,32,0,0,0-2.9,5.1c-.5,1.3-1,2.9-1.3,3.7h-.2l-.2-2,.5-.6-.5.4-.3-3.2.3-.6-.4.4-.2-1.8s-.1.9-.2,2.2l-2,2.4-.3.4a7.6,7.6,0,0,0-.8-1.1v-.3a28.2,28.2,0,0,1,1.9-5.1,30,30,0,0,0-2.6,4.6l-.6-.5.4.9v.2l-.9,2.5-.8-.5.7.8-.4,1.5-.8-7.9s-.2,2-.5,4.2a14.1,14.1,0,0,0,0,4.1l-1.7-2.7a8.4,8.4,0,0,0-2.5-3.1s1,2,1.7,3.8a5.3,5.3,0,0,0,.8,1.7l-3.8-2.5,3.5,3.8h15.2l1.4-2.2-2.8.8,2.9-3.3Zm-8.2,3h-.3l-.3-.5.5-.6a4.6,4.6,0,0,1,.1,1Zm.3-5a7.7,7.7,0,0,1-.2,1.5,10.9,10.9,0,0,0-.1,1.8l-.9.7-.5-.8c0-.1.1-.2.1-.3l1.6-2.9Zm-2.4,5a1.6,1.6,0,0,1,.1-.4c0,.1.1.1.1.2l-.2.2Zm-.8-2.7a3.6,3.6,0,0,0,.4.9l-.7,1.1h-.2c.1-.5.3-1.2.5-1.9Zm-.8,2.6h0Zm5,.2v-.2a1,1,0,0,0-.1.4v-.2Zm6.4-6.4c0-.1.1-.1.1-.2S329,321,328.9,321.2Zm-133.8,0V321C195.3,320.9,195.2,321,195.1,321.2Z"
                    fill="#263238"
                  />
                  <path
                    d="M202.2,324.5l-1.4,1.1-2.4,1.9a18,18,0,0,1,.8-2.1c.5-1,2-3.5,2.4-4.3a22.2,22.2,0,0,0-2.8,3.3c-1.3,1.8-2,3-2,3a26,26,0,0,0,1-4,28.2,28.2,0,0,1,1.9-5.1,32,32,0,0,0-2.9,5.1c-.5,1.3-1,2.9-1.3,3.7h-.2l-.2-2,.5-.6-.5.4-.3-3.2.4-.6-.4.4-.2-1.8s-.1.9-.2,2.2l-2.1,2.4-.3.4a7.6,7.6,0,0,0-.8-1.1v-.3a28.2,28.2,0,0,1,1.9-5.1,30,30,0,0,0-2.6,4.6l-.6-.5.4.9c0,.1-.1.1-.1.2l-.9,2.5-.8-.5.7.8-.5,1.5-.8-7.9s-.2,2-.5,4.2a14.1,14.1,0,0,0,0,4.1l-1.7-2.7a8.4,8.4,0,0,0-2.5-3.1s1,2,1.7,3.8a5.3,5.3,0,0,0,.8,1.7l-3.8-2.5,3.4,3.8h15.2l1.4-2.2-2.8.8,3.1-3.3Zm-8.2,3h-.3l-.3-.5.5-.6A4.6,4.6,0,0,1,194,327.5Zm.3-5c-.1.5-.1,1-.2,1.5a10.9,10.9,0,0,0-.1,1.8l-.9.7-.5-.8a.4.4,0,0,0,.1-.3l1.6-2.9Zm-2.4,5a1.6,1.6,0,0,1,.1-.4v.2l-.2.2Zm-.8-2.8a3.6,3.6,0,0,0,.4.9l-.7,1.1h-.2Zm-.8,2.7h0Zm5,.1v-.2a1,1,0,0,0-.1.4v-.2Zm6.4-6.3c0-.1.1-.1.1-.2S201.8,321,201.7,321.2Z"
                    fill="#263238"
                  />
                </g>
                <g
                  id="f4b1197c-a7bc-4b85-a17d-638703d10a96"
                  data-name="freepik--Ground--inject-66"
                >
                  <path
                    d="M653,319.7l-2.3,25.9a90.9,90.9,0,0,1-90.5,82.7H265.3c28-3.8,65.5-11.6,83.3-27.1,27.4-23.9,32.3-46.4,33.7-48.5s5.6-10.5,5.6-10.5l-6.3,4.2v-4.9l2.1-7.7-8.4,2.8-2.1-8.4-2.5,2.5-3.9,3.9s-2.1-5.6-2.1-9.1,3.5-7.7,3.5-7.7l-12,2.8s3-3.3,6.6-6.8a94,94,0,0,1,7.4-6.6c5.7-4.2,24.7-1.4,24.7-1.4H652.4c.6,8.7.6,13.9.6,13.9Z"
                    fill="#b2b2b2"
                    stroke="#263238"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                  />
                  <path
                    d="M395.7,344.2l-7.6,27.9L405,354.8l2.6,14.6,13.9-15.3,27.2-17.2,7.2,4.7,4.8-13.2,33-4.8,9.2-5.2-99.2,9.3Z"
                    fill="#263238"
                  />
                  <path
                    d="M653.3,327.3c-.2,2.8-.4,4.9-.4,5.6-2.1,28.9-13.7,58-37,76.2-1.7,1.4-3.5,2.6-5.3,3.9a91,91,0,0,1-50.4,15.2H363.1l4.7-3.6L383.1,411l13.6-14.9s11.9-7.2,11.9-5.5.5,26.4.5,26.4l17.4-20.4,9.4-38.3L450.8,343v12.3l6.8-5.1,11.9-8.9,17.4-7.2-6,9.8,25.4-15.6,6.2-9.3,7.1-5.3,27-8.1h106c1.9.3,1.3,13.7.7,21.7Z"
                    fill="#263238"
                  />
                  <path
                    d="M482.7,325.2l11-1.6,18.8-4.6-6.2,9.3s17.1-11.4,22.6-13.4a139.6,139.6,0,0,1,14.4-4.1l8.2-3.4,13.7-1.8H395.1s-19-2.8-24.6,1.4a65.9,65.9,0,0,0-7.4,6.6c-3.6,3.5-6.6,6.8-6.6,6.8l12-2.8s-3.5,4.2-3.5,7.7,2.1,9.1,2.1,9.1l3.9-3.9,2.5-2.5,2.1,8.4,8.4-2.8-2.1,7.7v4.9l6.3-4.2,2.6,11.4,10.2-7.9h15.7l-2.4,5.5,18.9-5.5,6.3-2.4,13.2-9.4,8-5.6,2.4,7.9,11-7.9,8.6-2.9Z"
                    fill="#1cc41c"
                    stroke="#263238"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                  />
                  <path
                    d="M332.4,428.3l13-6,9.4-10.7-4.1,3.4-4.2,2.1-7.7,3.9h-1.1l-3.9.6-12.2,1.9-10.4,4.7Z"
                    fill="#263238"
                  />
                </g>
                <g
                  id="b26875bd-2f43-48be-99e6-bccceef05a32"
                  data-name="freepik--Worms--inject-66"
                >
                  <path
                    d="M506.5,404.2a9.1,9.1,0,0,1-5.8-2.4l-1.5-1.4a10.8,10.8,0,0,0-3.9-2.8c-2.9-1-5.7,1-7.2,3.4a1.5,1.5,0,1,1-2.6-1.4.1.1,0,0,1,.1-.1c2.1-3.5,6.2-6.2,10.7-4.7a14.6,14.6,0,0,1,5,3.5,14.9,14.9,0,0,0,1.4,1.2c1.7,1.4,4.2,2.7,6.7.5a4.7,4.7,0,0,0,1.3-5.2,8.6,8.6,0,0,0-5.9-5.8,17.3,17.3,0,0,0-3.2-.3,29.8,29.8,0,0,1-4.3-.5c-2.7-.6-5.9-2.6-6.5-6a1.5,1.5,0,0,1,2.9-.7v.2c.3,2,2.4,3.1,4.2,3.6a24.7,24.7,0,0,0,3.8.5l3.5.4a11.4,11.4,0,0,1,8.3,7.9,7.8,7.8,0,0,1-2.2,8.3,7.6,7.6,0,0,1-4.8,1.8Z"
                    fill="#c2c2c2"
                  />
                  <path
                    d="M504.9,389l1,.3,1.6-2.6-1-.4Zm-3.4-.4h1l.5-3h-1Zm-5.2-.8.7-2.9-.9-.4-.7,3Zm13.4.3-2.1,2.2.8.7,2.1-2.2Zm3.4,12a3.6,3.6,0,0,0,.4-.9l-2.7-1.5a4.2,4.2,0,0,1-.4,1Zm-25.3-3.2,1.8,2.4.8-.6-1.8-2.4C488.3,396.4,488.1,396.7,487.8,396.9Zm.5,4,.6-.8-2.2-2-.6.8Zm21.9-7.6,2.8-1a4.1,4.1,0,0,0-.5-.9l-2.9,1,.6.9Zm-11.8-5h1l.4-3h-1Zm1.2,8.4-.9-.7-.7,3.2a3,3,0,0,1,.8.8l.8-3.3Zm3.5,6.6,1.1-2.8-.9-.5-1.1,2.8Zm3.8-2.1h-1l-.4,3h1Zm3.8,1.6-1.3-2.8-.8.6,1.3,2.7.8-.5Zm.1-7.9a3.6,3.6,0,0,1,.2,1l3,.3a3.4,3.4,0,0,0-.1-1l-3.1-.3Zm-14.3,0h-.2l-.9-.2.3,3.2,1,.6-.2-3.5Zm5.6,4.1-.8-.7-1.5,2.6.8.7Zm-9.6-4.5-1,.2,1.1,2.8h1Zm.4-8.7,2.3-1.9a4.6,4.6,0,0,1-.7-.7l-2.3,1.9Z"
                    fill="#263238"
                  />
                  <path
                    d="M529.3,418.6c-2.5,0-6.8-1.5-7.5-7.3a7.7,7.7,0,0,1,3.7-7.4,9.4,9.4,0,0,1,10.2.3,23.6,23.6,0,0,1,5.9,5.9c1.8,2.4,2.6,3.3,3.8,3.1,3-.4,3.8-4.4,3.8-4.4a1.5,1.5,0,1,1,3,.6c0,.2-1.2,6.1-6.3,6.9-3.2.4-5-2-6.7-4.3a20.6,20.6,0,0,0-5-5.2,6.6,6.6,0,0,0-7-.2,4.6,4.6,0,0,0-2.3,4.5c.5,4.4,3.8,4.6,4.5,4.6a1.5,1.5,0,0,1,1.5,1.5,1.5,1.5,0,0,1-1.6,1.4Z"
                    fill="#c2c2c2"
                  />
                  <path
                    d="M526.8,406.7l-2.5-1.8-.7.7,2.4,1.8A2.7,2.7,0,0,1,526.8,406.7ZM525,409a4.7,4.7,0,0,1,.5-1l-3.2-.3-.3,1Zm7-6.3h-1l.2,3,1,.2Zm-9.4,11.4,2.8-1.1-.3-1-2.8,1.1A1.7,1.7,0,0,0,522.6,414.1Zm3.9.5-2.5,1.7a2.7,2.7,0,0,0,.8.7l2.7-1.9-1-.5Zm-4.7-4.5v1h3v-1Zm6.5-4.2,1-.3-1.3-2.8-1,.3Zm15.6,6.9-.8-.7-1,3.1.9.5.9-2.9Zm4.1-1.2,1.8,2.6.7-.8-1.8-2.7Zm-.6,4.2-.5-3.1-.9.4.5,3Zm-11-11.2-.7-.5h-.2l-.9,3,.8.6,1-3Zm3.2,7.9,1.6-2.9-.7-.9-1.6,2.8.2.2Zm-2.7-3.4.7.8,1.7-2.6-.7-.7-1.7,2.5Z"
                    fill="#263238"
                  />
                  <path
                    d="M599.1,381.1c1.4-2,5.1-4.8,10.2-2.1a7.8,7.8,0,0,1,4.1,7.1,9.7,9.7,0,0,1-5.9,8.4,21,21,0,0,1-8.2,1.6c-3,.1-4.2.3-4.7,1.5-1.3,2.8,1.6,5.6,1.6,5.6a1.4,1.4,0,0,1-.1,2.1,1.5,1.5,0,0,1-2,0c-.2-.2-4.5-4.4-2.2-9.1,1.4-2.9,4.4-3,7.3-3.2a19.4,19.4,0,0,0,7.1-1.3,6.4,6.4,0,0,0,4.1-5.7,4.7,4.7,0,0,0-2.4-4.4c-3.9-2-6,.6-6.3,1.1a1.5,1.5,0,0,1-2.1.4,1.3,1.3,0,0,1-.5-2Z"
                    fill="#c2c2c2"
                  />
                  <path
                    d="M610.4,385.6l2.9-1a3.6,3.6,0,0,0-.2-1l-2.8,1A3.4,3.4,0,0,0,610.4,385.6Zm-1-2.8a4.1,4.1,0,0,1,.5.9l2-2.5-.6-.8Zm1.3,9.4.7-.8-2.6-1.5a2.7,2.7,0,0,1-.8.7l2.7,1.6ZM606.5,378l-.7,2.9,1,.2.7-2.9Zm-2.6,3v-3.1l-1,.3v3.3l1-.5Zm6.4-1.4-.8-.5-1.7,2.5h.2l.7.5Zm-.1,7.7-.3,1,3.1.4a3.6,3.6,0,0,0,.2-1Zm-14.5,9.2,1.1-.3-2-2.6-.9.4,1.8,2.5Zm-1.2,4h-3.1l.3,1H595A3.1,3.1,0,0,1,594.5,400.5Zm-3.1-2.8,2.9,1.3a3.6,3.6,0,0,1,.2-1l-2.7-1.2a1.2,1.2,0,0,0-.4.9Zm15.3-3,.8-.3h.2l-2-2.4-1,.4Zm-8.4-1.6,1.5,2.9h1.1l-1.5-2.9h-1.1Zm4.5-.4h-1l1.2,2.9,1-.2Z"
                    fill="#263238"
                  />
                </g>
                <g
                  id="fc56671e-c777-454a-b6df-1dbbdc247f52"
                  data-name="freepik--Roots--inject-66"
                >
                  <path
                    d="M624.8,347.2a43.4,43.4,0,0,1-7.1-3.7c-2.3-1.4-4.5-2.9-6.7-4.5a47.3,47.3,0,0,0-8-4.3l-1.3-.3a5.8,5.8,0,0,0-2.3.2,20,20,0,0,0-3.7,2.2,21.1,21.1,0,0,1-3.3,1.8,15.1,15.1,0,0,1-3.7.7,34,34,0,0,1-7.8-.3l-2.4-.4a17.1,17.1,0,0,1-2-1.8,26.9,26.9,0,0,1-3-3.7,25.9,25.9,0,0,1-3.7-8.9c-.3-1.3-.5-2.7-.7-4l1.8.5a26,26,0,0,0,5.6.3,47.8,47.8,0,0,0,5.3-.6,47,47,0,0,0,5.1-1.2l2.2-.5a2.6,2.6,0,0,1,1.7.7c1.2.9,2.1,2.4,3.5,3.6a5.7,5.7,0,0,0,1.3.8l.8.2h.7l2.5-.2,5.1-.3-5.1-.3H597a2.8,2.8,0,0,1-1.9-.9c-1.1-1.1-1.7-2.8-3.1-4.1a4.2,4.2,0,0,0-2.8-1.4,14.2,14.2,0,0,0-2.9.2,42.3,42.3,0,0,1-5,.5,40.1,40.1,0,0,1-4.9,0,17,17,0,0,1-4.5-.8l-1.9-.8-.7-.5-.2-.2-.5-1.5c0-.2-.2-.9-.2-1.2a59.4,59.4,0,0,0-.5-7.2l-8.9.2c-.1,1.5-.4,4-.6,5.5s-.6.7-.8,1.5l-.3,1.1-.4,1.2a6.6,6.6,0,0,1-.9,1.9,2.7,2.7,0,0,1-1.2.9,6.1,6.1,0,0,1-1.9,0l-2.5-.6a26.1,26.1,0,0,0-5.5-.8,9.7,9.7,0,0,0-5.7,1.6,12.1,12.1,0,0,0-3.8,4.3c-.5.8-.9,1.6-1.3,2.4a12.8,12.8,0,0,1-1.1,2,11.1,11.1,0,0,1-4.1,2.3l-5,1.6c-3.3,1-6.7,1.8-10.1,3.2a9.2,9.2,0,0,0-2.4,1.3l-2,1.7-3.9,3.6c-.6.6-1.3,1.2-1.9,1.9a15.6,15.6,0,0,1-2,1.6,33.5,33.5,0,0,1-4.5,2.7l4.6-2.5a11.6,11.6,0,0,0,2.1-1.6l1.9-1.8,4-3.3,2.1-1.6a9.1,9.1,0,0,1,2.2-1.1c3.2-1.1,6.7-1.8,10.1-2.6l5.1-1.4,2.6-.9a7,7,0,0,0,2.5-1.7,10.7,10.7,0,0,0,1.6-2.5,25.3,25.3,0,0,1,1.3-2.2,10.4,10.4,0,0,1,3.2-3.4c2.5-1.6,5.9-.9,9.1,0l2.6.7a7.4,7.4,0,0,0,3.3.1,5.8,5.8,0,0,0,3.5-2.4l-.3,5.8v1.6c-.1.1-.1.3-.2.5-1.3,3-3.9,5.2-6.8,7.4a38.1,38.1,0,0,0-4.3,3.7A16.3,16.3,0,0,0,544,342a18.3,18.3,0,0,0-1.4,5.7,8.4,8.4,0,0,0-3.1,1.2,9.2,9.2,0,0,0-3.1,3.4c-.2.3-.3.7-.5,1l-.4,1-.7,1.9c-.5,1.3-.9,2.6-1.5,3.8a16.8,16.8,0,0,1-2,3.4,18.5,18.5,0,0,1-2.8,2.8c-1,.8-2.3,1.4-3.4,2.2l-3.3,2.4,3.5-2.1c1.2-.7,2.4-1.1,3.6-1.9a20.8,20.8,0,0,0,3.2-2.7,16.6,16.6,0,0,0,2.5-3.4c.7-1.2,1.2-2.5,1.8-3.7l.9-1.8.5-.9.5-.8a6.1,6.1,0,0,1,2.5-2.3l1.6-.5h.2a24.6,24.6,0,0,0,.2,2.8,44.1,44.1,0,0,1,.2,10.9,22.4,22.4,0,0,1-4.2,9.9c-1,1.5-2.2,2.9-3.3,4.4a5.8,5.8,0,0,0-1.2,2.5l-.4,2.7.5-2.7a5.6,5.6,0,0,1,1.3-2.4c1.1-1.4,2.4-2.8,3.6-4.2a23.4,23.4,0,0,0,4.9-10,46.5,46.5,0,0,0,.4-11.2c-.1-3.6.1-7.2,1.7-10.2a15,15,0,0,1,3-4,33.2,33.2,0,0,1,4.2-3.2,37.3,37.3,0,0,0,4.6-3.5l.2-.2c0,.4-.1.7-.1,1.1a24.6,24.6,0,0,1-1.1,4.5c-.2.8-.5,1.5-.7,2.4a13.3,13.3,0,0,0-.3,2.8,11.4,11.4,0,0,0,.6,2.5s3.5,5.2,4.5,6.4a12.3,12.3,0,0,1,2.1,3.9,9.8,9.8,0,0,1,.2,4.5,14.1,14.1,0,0,1-1.1,4.5c-.3.7-.7,1.4-1,2.2a10.5,10.5,0,0,0-.6,2.4,40,40,0,0,0,0,4.9l.2,4.8.2-4.8a25.9,25.9,0,0,1,.4-4.8,8.1,8.1,0,0,1,.7-2.2,22.5,22.5,0,0,1,1.2-2.1,13.6,13.6,0,0,0,1.5-4.7,12.5,12.5,0,0,0,.1-5.1,13.3,13.3,0,0,0-2.1-4.7l-1.5-2.2a20.7,20.7,0,0,0,3.5.3c2.5,0,5.4.6,7.2,2.3a4,4,0,0,1,1,1.5,13.3,13.3,0,0,1,.5,1.9,31.2,31.2,0,0,1,.6,4.1,15.8,15.8,0,0,0,.9,4.2,6.9,6.9,0,0,0,1,1.9l1.2,1.8-1-1.9a6.4,6.4,0,0,1-.8-1.9,30.5,30.5,0,0,1-.5-4.1c-.1-1.4-.1-2.8-.3-4.3a17,17,0,0,0-.4-2.2,7.2,7.2,0,0,0-1.2-2.1,10.1,10.1,0,0,0-3.9-2.5,16.4,16.4,0,0,0-4.5-1,27,27,0,0,1-3.9-.8l-1.5-.4a5.4,5.4,0,0,1-.6-2.5,10.2,10.2,0,0,1,1.2-4.1,44.2,44.2,0,0,0,1.5-4.8,40.1,40.1,0,0,0,.8-5l.3-3.1c.5-1.3.9-2.6,1.3-3.9s.5-1.8.6-2.6c.3,2,.7,3.9,1.2,5.9a35.2,35.2,0,0,0,1.9,5.1,27.8,27.8,0,0,0,2.8,4.7,28.5,28.5,0,0,0,2.3,2.6s2.7,3.4,4.4,3.6l1.2.8a13.4,13.4,0,0,1,3.6,3.1,9.8,9.8,0,0,1,1.8,4.2,40.2,40.2,0,0,1,.6,5c.1,1.7.3,3.4.4,5.1s.2,3.4.4,5.2a21.7,21.7,0,0,0,1.3,5c.6,1.6,1.1,3.2,1.6,4.9a28.1,28.1,0,0,0,1.6,4.9,28.3,28.3,0,0,1-1.3-5c-.4-1.7-.8-3.3-1.3-5a21,21,0,0,1-.9-5c-.1-1.7-.1-3.4-.1-5.1s0-3.4-.1-5.2-.1-3.4-.3-5.2a11.3,11.3,0,0,0-3.9-7.4,37.5,37.5,0,0,0,6.7-.2,21.3,21.3,0,0,0,4.2-1,17.2,17.2,0,0,0,3.7-2.2,13,13,0,0,1,3.1-2.1,5,5,0,0,1,3.4.1h.2c.4,1.2.8,2.5,1.3,3.7a56.2,56.2,0,0,0,2.5,5.6,66.3,66.3,0,0,1,4.3,11.2h0l2.1,2.5,1.2,1.2a4.2,4.2,0,0,0,1.4.9,4,4,0,0,1-1.2-1,6.4,6.4,0,0,1-1-1.3l-1.7-2.6c-.3-2-.8-4-1.2-6a57.6,57.6,0,0,0-1.8-5.9c-.8-1.9-1.4-3.7-2-5.6a6.5,6.5,0,0,0-.4-1.3l3.5,2c2.3,1.4,4.6,2.9,7,4.2a49.5,49.5,0,0,0,7.4,3.4c2.5.9,5.4,1.5,8,.6-2.4.9-5.1.2-7.6-.8Z"
                    fill="#c2c2c2"
                  />
                  <path d="M569.1,315l-.6-2.3a21.7,21.7,0,0,0,.7,2.4Z" fill="#c2c2c2" />
                </g>
              </g>
            </g>
          </svg>
        </div>

        <!-- illustration two -->
        <div class="illustration-two">
          <svg
            width="100%"
            height="100%"
            version="1.1"
            id="Layer_1"
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            x="0px"
            y="0px"
            viewBox="0 0 500 500"
            style="enable-background: new 0 0 500 500"
            xml:space="preserve"
          >
            <style type="text/css">
              .st0 {
                fill: #0eea4c;
              }
              .st1 {
                opacity: 0.6;
              }
              .st2 {
                fill: #ffffff;
              }
              .st3 {
                opacity: 0.3;
                fill: #ffffff;
                enable-background: new;
              }
              .st4 {
                fill: #263238;
              }
              .st5 {
                opacity: 0.5;
                fill: #ffffff;
                enable-background: new;
              }
              .st6 {
                fill: #263238;
                stroke: #263238;
                stroke-linecap: round;
                stroke-linejoin: round;
              }
              .st7 {
                fill: none;
                stroke: #263238;
                stroke-linecap: round;
                stroke-linejoin: round;
              }
              .st8 {
                fill: #0eea4c;
                stroke: #263238;
                stroke-linecap: round;
                stroke-linejoin: round;
              }
              .st9 {
                fill: #ffffff;
                stroke: #263238;
                stroke-linecap: round;
                stroke-linejoin: round;
              }
              .st10 {
                clip-path: url(#SVGID_2_);
              }
              .st11 {
                fill: #323232;
              }
            </style>
            <path
              class="st0"
              d="M211.6,169.5c-6.4-3.5-9.3-0.6-11.6-3.5s6.4-10.4-11-18c0,0-1.2-16.2-24.9-16.8s-17.4,16.2-23.8,20.3
	s-8.1-2.3-14.5,1.7s-3.5,12.2-8.7,13.3s-12.2-5.2-18.5-1.2s-6.4,7.6-9.3,7.6s-8.7-2.3-12.2,0s-7.5,5.2-7.5,5.2h146.6
	C216.3,178.2,218,173,211.6,169.5L211.6,169.5z M277.8,121.7c-3.2-1.7-4.6-0.3-5.8-1.7s3.2-5.2-5.5-9c0,0-0.6-8.1-12.5-8.4
	s-8.7,8.1-11.9,10.2s-4.1-1.2-7.3,0.9s-1.7,6.1-4.4,6.7s-6.1-2.6-9.3-0.6s-3.2,3.8-4.6,3.8s-4.4-1.2-6.1,0s-3.8,2.6-3.8,2.6h73.4
	C280.1,126,281,123.4,277.8,121.7z M347.8,156.6c-3.2-1.7-4.6-0.3-5.8-1.7s3.2-5.2-5.5-9c0,0-0.6-8.1-12.5-8.4s-8.7,8.1-11.9,10.2
	s-4.1-1.2-7.3,0.9s-1.7,6.1-4.4,6.7s-6.1-2.6-9.3-0.6s-3.2,3.8-4.6,3.8s-4.4-1.2-6.1,0s-3.8,2.6-3.8,2.6h73.4
	C350.1,161,351,158.4,347.8,156.6L347.8,156.6z"
            />
            <g class="st1">
              <path
                class="st2"
                d="M211.6,169.5c-6.4-3.5-9.3-0.6-11.6-3.5s6.4-10.4-11-18c0,0-1.2-16.2-24.9-16.8s-17.4,16.2-23.8,20.3
		s-8.1-2.3-14.5,1.7s-3.5,12.2-8.7,13.3s-12.2-5.2-18.5-1.2s-6.4,7.6-9.3,7.6s-8.7-2.3-12.2,0s-7.5,5.2-7.5,5.2h146.6
		C216.3,178.2,218,173,211.6,169.5L211.6,169.5z M277.8,121.7c-3.2-1.7-4.6-0.3-5.8-1.7s3.2-5.2-5.5-9c0,0-0.6-8.1-12.5-8.4
		s-8.7,8.1-11.9,10.2s-4.1-1.2-7.3,0.9s-1.7,6.1-4.4,6.7s-6.1-2.6-9.3-0.6s-3.2,3.8-4.6,3.8s-4.4-1.2-6.1,0s-3.8,2.6-3.8,2.6h73.4
		C280.1,126,281,123.4,277.8,121.7z M347.8,156.6c-3.2-1.7-4.6-0.3-5.8-1.7s3.2-5.2-5.5-9c0,0-0.6-8.1-12.5-8.4s-8.7,8.1-11.9,10.2
		s-4.1-1.2-7.3,0.9s-1.7,6.1-4.4,6.7s-6.1-2.6-9.3-0.6s-3.2,3.8-4.6,3.8s-4.4-1.2-6.1,0s-3.8,2.6-3.8,2.6h73.4
		C350.1,161,351,158.4,347.8,156.6L347.8,156.6z"
              />
            </g>
            <path
              class="st0"
              d="M49.8,309.8c0,0,14.4,1.4,21.7,10.4c0,0,7.7-10.4,21.6-10.1c9.9-11.9,8.2-29.6-3.7-39.4s-29.6-8.2-39.4,3.7
	C41.4,284.6,41.3,299.5,49.8,309.8L49.8,309.8z"
            />
            <path
              class="st3"
              d="M49.8,309.8c0,0,14.4,1.4,21.7,10.4c0,0,7.7-10.4,21.6-10.1c9.9-11.9,8.2-29.6-3.7-39.4s-29.6-8.2-39.4,3.7
	C41.4,284.6,41.3,299.5,49.8,309.8L49.8,309.8z"
            />
            <path class="st4" d="M71,266.1l-0.5,72.2h2.4C72.9,338.3,71,266.1,71,266.1z" />
            <path
              class="st4"
              d="M71.7,317.4c0,0,4.9-8.8,13.6-11.4c0,0-9.2,2.2-13.9,9.7L71.7,317.4z M71.7,292.6c0,0,4.9-8.8,13.6-11.4
	c0,0-9.2,2.2-13.9,9.7L71.7,292.6z M71.7,305c0,0,4.9-8.8,13.6-11.4c0,0-9.2,2.2-13.9,9.7L71.7,305z M71,299c0,0-4.7-8.8-13.1-11.4
	c0,0,8.9,2.2,13.4,9.7L71,299z M71,311.1c0,0-4.7-8.8-13.1-11.4c0,0,8.9,2.2,13.4,9.7L71,311.1z"
            />
            <path
              class="st0"
              d="M94.4,304.3c0,0,17.2,1.7,25.9,12.3c0,0,9.2-12.3,25.7-12.1c11.7-14.2,9.8-35.2-4.4-47
	c-14.2-11.7-35.2-9.8-47,4.4C84.5,274.3,84.4,292,94.4,304.3L94.4,304.3z"
            />
            <path
              class="st5"
              d="M94.4,304.3c0,0,17.2,1.7,25.9,12.3c0,0,9.2-12.3,25.7-12.1c11.7-14.2,9.8-35.2-4.4-47
	c-14.2-11.7-35.2-9.8-47,4.4C84.5,274.3,84.4,292,94.4,304.3L94.4,304.3z"
            />
            <path class="st4" d="M119.7,252.3l-0.6,86.1h2.9L119.7,252.3L119.7,252.3z" />
            <path
              class="st4"
              d="M120.6,313.4c0,0,5.8-10.4,16.2-13.6c0,0-11,2.6-16.5,11.6L120.6,313.4z M120.6,283.9c0,0,5.8-10.4,16.2-13.6
	c0,0-11,2.6-16.5,11.6L120.6,283.9z M120.6,298.6c0,0,5.8-10.4,16.2-13.6c0,0-11,2.6-16.5,11.6L120.6,298.6z M119.7,291.4
	c0,0-5.6-10.4-15.7-13.6c0,0,10.6,2.6,15.9,11.6L119.7,291.4z M119.7,305.9c0,0-5.6-10.4-15.7-13.6c0,0,10.6,2.6,15.9,11.6
	L119.7,305.9z"
            />
            <path
              class="st0"
              d="M140.5,314.3c0,0,12.2,1.2,18.3,8.7c4.5-5.4,11.2-8.6,18.2-8.5c8.3-10,6.9-24.9-3.1-33.3
	c-10-8.3-24.9-6.9-33.3,3.1C133.5,293,133.4,305.5,140.5,314.3L140.5,314.3z"
            />
            <path
              class="st5"
              d="M140.5,314.3c0,0,12.2,1.2,18.3,8.7c4.5-5.4,11.2-8.6,18.2-8.5c8.3-10,6.9-24.9-3.1-33.3
	c-10-8.3-24.9-6.9-33.3,3.1C133.5,293,133.4,305.5,140.5,314.3L140.5,314.3z"
            />
            <path class="st4" d="M158.4,277.4l-0.4,60.9h2.1L158.4,277.4z" />
            <path
              class="st4"
              d="M159.1,320.7c0,0,4.1-7.4,11.5-9.6c0,0-7.8,1.8-11.7,8.2L159.1,320.7z M159.1,299.8c0,0,4.1-7.4,11.5-9.6
	c0,0-7.8,1.8-11.7,8.2L159.1,299.8z M159.1,310.2c0,0,4.1-7.4,11.5-9.6c0,0-7.8,1.8-11.7,8.2L159.1,310.2z M158.4,305.1
	c0,0-4-7.4-11.1-9.6c0,0,7.5,1.9,11.3,8.2L158.4,305.1z M158.4,315.4c0,0-4-7.4-11.1-9.6c0,0,7.5,1.9,11.3,8.2L158.4,315.4z"
            />
            <path
              class="st0"
              d="M372.1,309.8c0,0,14.4,1.4,21.7,10.4c0,0,7.7-10.4,21.6-10.1c9.9-11.9,8.2-29.6-3.7-39.4
	c-11.9-9.9-29.6-8.2-39.4,3.7C363.7,284.6,363.6,299.5,372.1,309.8L372.1,309.8z"
            />
            <path
              class="st3"
              d="M372.1,309.8c0,0,14.4,1.4,21.7,10.4c0,0,7.7-10.4,21.6-10.1c9.9-11.9,8.2-29.6-3.7-39.4
	c-11.9-9.9-29.6-8.2-39.4,3.7C363.7,284.6,363.6,299.5,372.1,309.8L372.1,309.8z"
            />
            <path class="st4" d="M393.3,266.1l-0.5,72.2h2.4L393.3,266.1z" />
            <path
              class="st4"
              d="M394,317.4c0,0,4.9-8.8,13.6-11.4c0,0-9.2,2.2-13.9,9.7L394,317.4z M394,292.6c0,0,4.9-8.8,13.6-11.4
	c0,0-9.2,2.2-13.9,9.7L394,292.6z M394,305c0,0,4.9-8.8,13.6-11.4c0,0-9.2,2.2-13.9,9.7L394,305z M393.3,299c0,0-4.7-8.8-13.1-11.4
	c0,0,8.9,2.2,13.4,9.7L393.3,299z M393.3,311.1c0,0-4.7-8.8-13.1-11.4c0,0,8.9,2.2,13.4,9.7L393.3,311.1z"
            />
            <path
              class="st0"
              d="M400.6,300.1c0,0,19.3,1.9,29.1,13.9c0,0,10.3-13.9,28.9-13.6c13.2-16,11-39.6-5-52.8c-16-13.2-39.6-11-52.8,5
	C389.4,266.4,389.3,286.3,400.6,300.1L400.6,300.1z"
            />
            <path
              class="st5"
              d="M400.6,300.1c0,0,19.3,1.9,29.1,13.9c0,0,10.3-13.9,28.9-13.6c13.2-16,11-39.6-5-52.8c-16-13.2-39.6-11-52.8,5
	C389.4,266.4,389.3,286.3,400.6,300.1L400.6,300.1z"
            />
            <path class="st4" d="M429,241.6l-0.6,96.7h3.3L429,241.6L429,241.6z" />
            <path
              class="st4"
              d="M430,310.3c0,0,6.5-11.7,18.2-15.3c0,0-12.4,2.9-18.6,13L430,310.3z M430,277.1c0,0,6.5-11.7,18.2-15.3
	c0,0-12.4,2.9-18.6,13L430,277.1z M430,293.7c0,0,6.5-11.7,18.2-15.3c0,0-12.4,2.9-18.6,13L430,293.7z M429,285.6
	c0,0-6.3-11.7-17.6-15.3c0,0,11.9,2.9,17.9,13L429,285.6z M429,301.9c0,0-6.3-11.7-17.6-15.3c0,0,11.9,2.9,17.9,13L429,301.9z"
            />
            <path class="st6" d="M408.3,143.5l30.7,4.8v-24l-30.7,4.8V143.5z" />
            <path
              class="st7"
              d="M394.1,134l-10.3,204.3h20.7L394.1,134L394.1,134z M394.3,134.3v-13 M383.1,134.5h22.2"
            />
            <path
              class="st7"
              d="M399.4,240.1h-10.7l8-49.2h-5.2L399.4,240.1L399.4,240.1z"
            />
            <path class="st8" d="M385.2,130.1l-0.8,4.5l-21.2-2.2l1.3-7.6L385.2,130.1z" />
            <path
              class="st6"
              d="M384.3,133.5l0.8,4.5l-20.7,5.2l-1.3-7.6L384.3,133.5L384.3,133.5z"
            />
            <path
              class="st8"
              d="M384.6,137l2.3,4l-17.6,12l-3.8-6.6L384.6,137L384.6,137z"
            />
            <path
              class="st6"
              d="M386.1,140.1l3.5,3l-12.5,17.3l-5.9-4.9L386.1,140.1L386.1,140.1z"
            />
            <path class="st8" d="M388.6,142.6l4.3,1.6l-5.8,20.5l-7.2-2.6L388.6,142.6z" />
            <path
              class="st6"
              d="M391.7,144.1h4.6l1.5,21.2h-7.7L391.7,144.1L391.7,144.1z"
            />
            <path class="st8" d="M395.2,144.4l4.3-1.6l8.7,19.4l-7.2,2.6L395.2,144.4z" />
            <path
              class="st6"
              d="M398.6,143.5l3.5-3l14.8,15.3l-5.9,4.9L398.6,143.5L398.6,143.5z"
            />
            <path
              class="st8"
              d="M401.5,141.5l2.3-4l19.2,9.3l-3.8,6.6L401.5,141.5L401.5,141.5z"
            />
            <path
              class="st6"
              d="M403.5,138.6l0.8-4.5l21.2,2.2l-1.3,7.6L403.5,138.6L403.5,138.6z"
            />
            <path class="st8" d="M404.4,135.2l-0.8-4.5l20.7-5.2l1.3,7.6L404.4,135.2z" />
            <path
              class="st6"
              d="M404.1,131.7l-2.3-4l17.6-11.9l3.8,6.6L404.1,131.7L404.1,131.7z"
            />
            <path class="st8" d="M402.6,128.6l-3.5-3l12.5-17.3l5.9,4.9L402.6,128.6z" />
            <path
              class="st6"
              d="M400.1,126.1l-4.3-1.6l5.8-20.5l7.2,2.6L400.1,126.1z M387.2,127.2l-2.3,4l-19.2-9.3l3.8-6.7L387.2,127.2z"
            />
            <path
              class="st8"
              d="M390.1,125.2l-3.5,3l-14.8-15.3l5.9-4.9C377.6,107.9,390.1,125.2,390.1,125.2z"
            />
            <path
              class="st6"
              d="M393.4,124.3l-4.3,1.6l-8.7-19.5l7.2-2.6L393.4,124.3L393.4,124.3z"
            />
            <path
              class="st8"
              d="M396.9,124.6h-4.6l-1.5-21.3h7.7L396.9,124.6L396.9,124.6z"
            />
            <path
              class="st6"
              d="M397,134.3c0-1.5-1.2-2.7-2.7-2.7c-1.5,0-2.7,1.2-2.7,2.7c0,1.5,1.2,2.7,2.7,2.7S397,135.8,397,134.3L397,134.3
	z M297,271.8h99v66.5h-99V271.8z"
            />
            <path
              class="st8"
              d="M299.3,338.3H166.7v-66.7l24.5-62.5l40.9-19.9l42.1,20l25.2,62.3L299.3,338.3L299.3,338.3z"
            />
            <path
              class="st9"
              d="M160.9,279l-2.9-4l6.9-5l24.6-62.7l42.6-20.7l43.9,20.8l25.3,62.5l6.9,4.4l-2.7,4.2l-7.8-5l-0.3-0.5l-24.8-61.7
	l-40.4-19.2l-39.1,19l-24.4,62.3L160.9,279L160.9,279z"
            />
            <path class="st8" d="M222,214h22v56.2h-22V214z" />
            <path class="st9" d="M210,278.2h46v60.2h-46V278.2z" />
            <path
              class="st8"
              d="M195.3,268.2h75.3v4h-75.3V268.2z M195.3,210h75.3v4h-75.3V210z"
            />
            <path
              class="st4"
              d="M220.3,309.8l-7.8-22.8v45.6L220.3,309.8L220.3,309.8z M229.2,283.5h-15.5l7.8,22.8L229.2,283.5z M221.4,313.2
	l-7.8,22.8h15.5L221.4,313.2z M222.6,309.8l7.8,22.8V287L222.6,309.8L222.6,309.8z M252.2,283.5h-15.5l7.8,22.8L252.2,283.5z
	 M243.2,309.8l-7.6-22.4v44.9L243.2,309.8z M245.6,309.8l7.9,23.2v-46.3L245.6,309.8z M244.4,313.2l-7.8,22.8h15.5L244.4,313.2z
	 M404.1,274.2l-6.9-4.4l-25.3-62.5l-43.9-20.8h-96l43.9,20.8l25.3,62.5l6.9,4.4h86.7l6.6,4.2L404.1,274.2z"
            />
            <g>
              <defs>
                <polygon
                  id="SVGID_1_"
                  points="404.1,274.2 397.2,269.9 371.9,207.4 328.1,186.6 232.1,186.6 275.9,207.4 301.2,269.9
			308.1,274.2 394.8,274.2 401.4,278.4 		"
                />
              </defs>
              <clipPath id="SVGID_2_">
                <use xlink:href="#SVGID_1_" style="overflow: visible" />
              </clipPath>
              <g class="st10">
                <path
                  class="st5"
                  d="M404.1,274.2l-6.9-4.4l-25.3-62.5l-43.9-20.8h-96l43.9,20.8l25.3,62.5l6.9,4.4h86.7l6.6,4.2L404.1,274.2z"
                />
                <path class="st5" d="M275.9,207.4h96l-43.9-20.8h-96L275.9,207.4z" />
              </g>
            </g>
            <path
              class="st7"
              d="M404.1,274.2l-6.9-4.4l-25.3-62.5l-43.9-20.8h-96l43.9,20.8l25.3,62.5l6.9,4.4h86.7l6.6,4.2L404.1,274.2z"
            />
            <path class="st9" d="M308.1,274.2h96l-2.7,4.2h-96L308.1,274.2z" />
            <path
              class="st2"
              d="M308.1,289.5h4.8v7.7h-4.8V289.5z M313.9,289.5h4.8v7.7h-4.8V289.5z M308.1,298.2h4.8v6.8h-4.8V298.2z
	 M313.9,298.2h4.8v6.8h-4.8V298.2z M327.8,289.5h4.8v7.7h-4.8V289.5z M333.5,289.5h4.8v7.7h-4.8V289.5z M327.8,298.2h4.8v6.8h-4.8
	V298.2z M333.5,298.2h4.8v6.8h-4.8V298.2z M360.1,289.5h4.8v7.7h-4.8V289.5z M365.9,289.5h4.8v7.7h-4.8V289.5z M360.1,298.2h4.8v6.8
	h-4.8V298.2z M365.9,298.2h4.8v6.8h-4.8V298.2z M379.8,289.5h4.8v7.7h-4.8V289.5z M385.5,289.5h4.8v7.7h-4.8V289.5z M379.8,298.2
	h4.8v6.8h-4.8V298.2z M385.5,298.2h4.8v6.8h-4.8V298.2z M341.7,280.7h14v6.7h-14V280.7z"
            />
            <path
              class="st9"
              d="M443.7,319.7v3.7h-11v-3.7h-2.8v3.7H419v-3.7h-2.8v3.7h-11v-3.7h-2.8v3.7h-11v-3.7h-2.7v3.7h-11v-3.7H375v3.7
	h-11v-3.7h-2.8v3.7h-11v-3.7h-2.8v3.7h-11v-3.7h-2.7v3.7h-11v-3.7H320v24.7h2.8v-8.2h11v8.2h2.7v-8.2h11v8.2h2.8v-8.2h11v8.2h2.8
	v-8.2h11v8.2h2.8v-8.2h11v8.2h2.7v-8.2h11v8.2h2.8v-8.2h11v8.2h2.8v-8.2h11v8.2h2.8v-8.2h11v8.2h2.7v-24.7H443.7z M322.8,332.9v-6.4
	h11v6.4H322.8z M336.6,332.9v-6.4h11v6.4H336.6z M350.3,332.9v-6.4h11v6.4H350.3z M364,332.9v-6.4h11v6.4H364z M377.8,332.9v-6.4h11
	v6.4H377.8z M391.5,332.9v-6.4h11v6.4H391.5z M405.2,332.9v-6.4h11v6.4H405.2z M419,332.9v-6.4h11v6.4H419z M432.7,332.9v-6.4h11
	v6.4H432.7z"
            />
            <path class="st7" d="M320.1,344.4h126.3" />
            <path
              class="st0"
              d="M351.2,334.1c0,0,0.4-2,0.4-2.1c0.5-1.4,2.2-3.9,3.9-3.9c1.1,0,2,1,1.9,2.1c0,0.1,0,0.1,0,0.2
	c-0.3,1.2-1,2.2-2.1,2.8C354,333.7,352.6,334,351.2,334.1L351.2,334.1z"
            />
            <path
              class="st0"
              d="M348,320.8c1.6,0.6,2.4,3.5,2.3,5c0,0.1-0.3,2.1-0.3,2.1c0.1,0.5,0.3,1,0.4,1.5c0.2,1,0.5,2.1,0.7,3.4
	c0.2,1.3,0.4,2.7,0.5,4.1c0.1,1.5,0,3.1-0.2,4.6c0,0,0,0,0,0.1c0.2-0.5,0.8-1.7,0.9-1.8c0.8-1.2,3.1-3.2,4.8-2.7
	c1.1,0.3,1.6,1.5,1.3,2.5c0,0.1,0,0.1-0.1,0.2c-0.6,1.1-1.6,1.8-2.8,2.1c-1.4,0.2-2.8,0.1-4.1-0.1c-0.2,1.5-0.6,3.1-1,4.6
	c-0.2,0.9-0.5,1.8-0.8,2.6l0.4-0.8c0.8-1.2,3.1-3.2,4.8-2.7c1.1,0.3,1.6,1.5,1.3,2.5c0,0.1,0,0.1-0.1,0.2c-0.6,1.1-1.6,1.8-2.8,2.1
	c-1.3,0.2-2.7,0.2-4-0.1l-0.3,1c-0.6,1.6-1.1,3.2-1.6,4.8c-0.2,0.6-0.3,1.1-0.5,1.7c0.2-0.3,0.3-0.6,0.3-0.7
	c0.8-1.2,3.1-3.2,4.8-2.7c1.1,0.3,1.6,1.5,1.3,2.5c0,0.1,0,0.1-0.1,0.2c-0.6,1.1-1.6,1.8-2.8,2.1c-1.3,0.2-2.6,0.2-3.9-0.1
	c-0.1,0.6-0.3,1.1-0.4,1.7c-0.1,0.4-0.2,0.8-0.2,1.1s-0.1,0.8-0.2,1.1c-0.1,0.7-0.2,1.5-0.2,2.2c0,0.5-0.1,1-0.1,1.5
	c0.2-0.5,0.5-1.6,0.6-1.7c0.6-1.2,1.5-2.2,2.6-2.9c0.1-0.1,0.1-0.3,0.2-0.4c0.6-0.9,1.9-1.2,2.8-0.5c0,0,0.1,0.1,0.1,0.1
	c1.3,1.1,1,4.1,0.4,5.5c0,0.1-0.5,0.9-0.8,1.4l0.7-0.8c0.5-0.6,0.9-1.1,1.5-1.7l0.8-0.9c0.3-0.3,0.6-0.6,0.9-0.9
	c0.7-0.6,1.4-1.3,2.1-1.9c-1.1-0.8-2-1.8-2.7-2.9c-0.6-1.1-0.7-2.3-0.3-3.5c0.5-1,1.7-1.4,2.7-1c0.1,0,0.1,0.1,0.2,0.1
	c1.4,0.9,1.6,3.9,1.2,5.4c0,0.1-0.4,1.1-0.6,1.6c0.4-0.4,0.9-0.7,1.3-1.1c1.3-1,2.7-2,4-3l1.2-0.9c-1.1-0.8-2.1-1.9-2.9-3
	c-0.6-1.1-0.7-2.3-0.3-3.5c0.5-1,1.7-1.4,2.7-1c0,0,0.1,0,0.1,0.1c1.4,0.9,1.6,3.9,1.2,5.4c0,0.1-0.6,1.6-0.7,1.9
	c0.9-0.7,1.8-1.4,2.7-2.1c1.2-1,2.3-2,3.3-3.1c-1.1-0.8-2.1-1.9-2.9-3c-0.6-1-0.7-2.3-0.3-3.5c0.5-1,1.7-1.4,2.7-1
	c0.1,0,0.1,0.1,0.2,0.1c1.4,0.9,1.5,3.9,1.2,5.4c0,0.1-0.4,1.2-0.7,1.7l0.1,0c1-1.1,1.9-2.3,2.7-3.6c0.5-0.7,0.8-1.4,1.2-2.1
	c-1.2-0.7-2.2-1.6-3.1-2.6c-0.7-1-1-2.2-0.7-3.4c0.4-1,1.5-1.6,2.5-1.3c0.1,0,0.1,0,0.2,0.1c1.5,0.7,2,3.7,1.8,5.2
	c0,0.1-0.2,0.9-0.4,1.5c0.2-0.3,0.3-0.6,0.5-0.9c0.5-1.1,1-2.2,1.4-3.2c0.2-0.5,0.4-1,0.5-1.5c-0.7-1.2-1.2-2.4-1.5-3.7
	c-0.2-1.2,0.1-2.4,0.8-3.4c0.8-0.8,2.1-0.7,2.8,0.1c0,0,0.1,0.1,0.1,0.1c1,1.3,0,4.2-0.8,5.4c-0.1,0.1-1.4,1.6-1.5,1.6
	c-0.1,0.5-0.3,0.9-0.5,1.5c-0.4,1-0.8,2-1.3,3.2c-0.5,1.3-1.2,2.5-1.9,3.6c-0.8,1.3-1.7,2.6-2.7,3.7c0.4-0.3,1.6-0.9,1.7-1
	c1.4-0.6,4.4-0.9,5.5,0.3c0.7,0.9,0.6,2.1-0.3,2.8c0,0-0.1,0.1-0.1,0.1c-1.1,0.6-2.3,0.7-3.5,0.2c-1.2-0.6-2.4-1.4-3.4-2.4
	c-1,1.2-2.2,2.3-3.4,3.3c-0.7,0.6-1.4,1.2-2.1,1.7l0.8-0.4c1.4-0.6,4.4-0.9,5.5,0.3c0.7,0.9,0.6,2.1-0.3,2.8c0,0-0.1,0.1-0.1,0.1
	c-1.1,0.6-2.3,0.7-3.5,0.2c-1.2-0.6-2.3-1.3-3.3-2.3l-0.8,0.6c-1.3,1-2.7,2-4,3.1c-0.5,0.4-0.9,0.8-1.3,1.1l0.6-0.4
	c1.4-0.6,4.4-0.9,5.5,0.3c0.7,0.9,0.6,2.1-0.3,2.8c0,0-0.1,0.1-0.1,0.1c-1.1,0.6-2.3,0.7-3.5,0.2c-1.2-0.6-2.3-1.3-3.2-2.2
	c-0.4,0.4-0.9,0.8-1.3,1.2s-0.5,0.5-0.8,0.8l-0.8,0.9c-0.5,0.6-1,1.1-1.4,1.7c-0.3,0.4-0.6,0.8-0.9,1.1c0.5-0.4,1.3-1.1,1.4-1.1
	c1.3-0.8,4.2-1.6,5.5-0.5c0.8,0.7,0.9,2,0.1,2.8c0,0-0.1,0.1-0.1,0.1c-1,0.7-2.2,1-3.4,0.7c-1.3-0.4-2.6-1-3.7-1.8
	c-0.5,0.6-0.9,1.2-1.4,1.8c-1.5,2-2.6,3.8-3.4,5l-0.1,0.1l-1-0.5l0.2-0.2c0.8-1.2,2-3,3.6-5c0.5-0.6,1-1.3,1.6-2
	c-0.6-0.6-1.1-1.3-1.6-2c-1.3,0.3-2.6,0.5-3.9,0.5c0,0.8-0.1,1.6-0.1,2.3c-0.1,2.5-0.1,4.6-0.1,6.1v0.2l-1.1-0.5
	c0-1.5,0-3.4,0.2-5.8c0-0.8,0.1-1.7,0.2-2.5c-1.3-0.3-2.6-0.8-3.8-1.5c-1-0.7-1.6-1.8-1.8-3c0-1.1,0.9-2,2-2c0.1,0,0.1,0,0.2,0
	c1.7,0.2,3,2.9,3.3,4.4c0,0.1,0.1,1,0.1,1.7c0-0.4,0.1-0.7,0.1-1.1c0.1-0.7,0.2-1.5,0.3-2.2l0.2-1.1c0.1-0.4,0.2-0.8,0.2-1.2
	c0.2-0.9,0.5-1.8,0.7-2.7c-1.3-0.1-2.6-0.4-3.9-0.9c-1.1-0.5-1.9-1.5-2.2-2.7c-0.2-1.1,0.6-2.1,1.7-2.3c0.1,0,0.1,0,0.2,0
	c1.7,0,3.5,2.4,3.9,3.8c0,0.1,0.3,1.1,0.4,1.7c0.2-0.5,0.3-1.1,0.5-1.6c0.5-1.6,1.1-3.2,1.7-4.8c0.2-0.5,0.4-1,0.5-1.5
	c-1.4-0.1-2.7-0.4-4-0.9c-1.1-0.5-1.9-1.5-2.2-2.7c-0.2-1.1,0.6-2.1,1.7-2.3c0.1,0,0.1,0,0.2,0c1.7,0,3.5,2.4,4,3.8
	c0,0.1,0.4,1.6,0.4,2c0.4-1.1,0.8-2.1,1.1-3.2c0.4-1.4,0.8-2.9,1.1-4.4c-1.4-0.1-2.7-0.4-4-0.9c-1.1-0.5-1.9-1.5-2.2-2.7
	c-0.2-1.1,0.6-2.1,1.7-2.3c0.1,0,0.1,0,0.2,0c1.7,0,3.5,2.4,3.9,3.8c0,0.1,0.3,1.2,0.4,1.8h0.1c0.2-1.5,0.3-3,0.3-4.5
	c0-0.8-0.1-1.6-0.2-2.4c-1.3,0-2.7-0.1-4-0.5c-1.1-0.4-2-1.3-2.5-2.5c-0.3-1.1,0.4-2.2,1.4-2.4c0.1,0,0.1,0,0.2,0
	c1.6-0.2,3.7,2,4.3,3.4c0,0.1,0.3,0.9,0.5,1.4c0-0.4-0.1-0.7-0.1-1c-0.2-1.3-0.4-2.4-0.6-3.4c-0.1-0.6-0.3-1.1-0.4-1.6
	c-1.2-0.6-2.3-1.3-3.3-2.3c-0.8-0.9-1.2-2.1-1.1-3.3C345.8,321.1,346.8,320.5,348,320.8C347.9,320.7,348,320.7,348,320.8L348,320.8z
	"
            />
            <path
              class="st0"
              d="M378.2,346.5c-1.4-0.3-2.7-0.7-3.9-1.4c0,0,1.4-1.5,1.5-1.5c1.2-0.9,4-2,5.4-1.1c0.9,0.6,1.1,1.9,0.5,2.8
	c0,0-0.1,0.1-0.1,0.1C380.6,346.3,379.4,346.7,378.2,346.5z M363,379.3c0,0-8-19.1-12.4-18.3s7.6,30.5,7.6,30.5s-14-26.3-23.5-26.3
	s3.5,29.1,15.5,38.8c0,0-19-20.5-30.1-16.1s22.2,25.2,22.2,25.2s-19.3-6.1-17.1-1.4s8.2,5.5,8.2,5.5l-21.9,1.1h76.1l-17.1-1.7
	c0,0,17.8-8.9,13-12.5s-15.2,4.2-15.2,4.2s18.1-20,14.6-27.4s-19,13.6-19,13.6s12.7-26.9,10.1-31.6S363,379.3,363,379.3z"
            />
            <path class="st7" d="M365.5,380.3c-7,20.6-7,35.2-7,35.2s8.2,0.3,16.8-6" />
            <path class="st7" d="M362,391.4c-1.4-6.2-3.3-12.2-5.7-18.1" />
            <path
              class="st7"
              d="M341.4,379.3l17.8,26.3c0,0,12.1-10.1,16.2-15.9 M358.8,412c0,0-18.7-8.9-26.3-14"
            />
            <path
              class="st0"
              d="M63.8,328.6l0.2-1c0.2-0.6,1-1.8,1.8-1.8c0.5,0,0.9,0.4,0.9,0.9c0,0,0,0.1,0,0.1c-0.1,0.5-0.5,1-1,1.3
	C65.1,328.4,64.5,328.6,63.8,328.6L63.8,328.6z"
            />
            <path
              class="st0"
              d="M62.4,322.5c0.7,0.3,1.1,1.6,1,2.3c0,0-0.1,1-0.2,1c0,0.2,0.1,0.4,0.2,0.7c0.1,0.5,0.2,1,0.3,1.5
	c0.1,0.6,0.2,1.2,0.2,1.9c0,0.7,0,1.4-0.1,2.1c0.1-0.2,0.4-0.8,0.4-0.8c0.4-0.6,1.4-1.4,2.2-1.2c0.5,0.1,0.7,0.6,0.6,1.1
	c0,0,0,0.1,0,0.1c-0.3,0.5-0.7,0.9-1.3,1c-0.6,0.1-1.3,0.1-1.9,0c-0.1,0.7-0.3,1.4-0.5,2.1c-0.1,0.4-0.2,0.8-0.4,1.2l0.2-0.4
	c0.4-0.6,1.4-1.5,2.2-1.2c0.5,0.1,0.8,0.6,0.7,1.1c0,0,0,0.1,0,0.1c-0.3,0.5-0.7,0.9-1.3,1c-0.6,0.1-1.2,0.1-1.8,0
	c-0.1,0.1-0.1,0.3-0.2,0.5c-0.2,0.7-0.5,1.5-0.7,2.2c-0.1,0.2-0.2,0.5-0.2,0.8l0.2-0.3c0.4-0.6,1.4-1.5,2.2-1.2
	c0.5,0.1,0.7,0.7,0.6,1.1c0,0,0,0.1,0,0.1c-0.3,0.5-0.7,0.8-1.3,1c-0.6,0.1-1.2,0.1-1.8,0c-0.1,0.3-0.1,0.5-0.2,0.8
	s-0.1,0.3-0.1,0.5s0,0.4-0.1,0.5c0,0.3-0.1,0.7-0.1,1s0,0.4,0,0.7c0.1-0.2,0.2-0.7,0.2-0.8c0.3-0.5,0.7-1,1.2-1.3
	c0-0.1,0.1-0.1,0.1-0.2c0.3-0.4,0.8-0.5,1.2-0.3c0,0,0.1,0,0.1,0.1c0.6,0.5,0.4,1.9,0.2,2.5l-0.4,0.7l0.3-0.4l0.7-0.8l0.3-0.4
	c0.1-0.1,0.3-0.2,0.4-0.4c0.3-0.3,0.6-0.6,1-0.9c-0.5-0.4-0.9-0.8-1.2-1.3c-0.4-0.5-0.5-1.1-0.3-1.7c0.2-0.5,0.7-0.7,1.2-0.4
	c0,0,0,0,0.1,0c0.7,0.4,0.7,1.8,0.6,2.4c0,0-0.2,0.5-0.3,0.8l0.6-0.5c0.6-0.5,1.2-0.9,1.8-1.4l0.6-0.4c-0.5-0.4-0.9-0.8-1.3-1.4
	c-0.3-0.5-0.3-1.1-0.2-1.6c0.2-0.5,0.8-0.7,1.2-0.4c0,0,0,0,0.1,0c0.7,0.4,0.7,1.8,0.5,2.4c0,0-0.3,0.7-0.3,0.9
	c0.4-0.3,0.8-0.6,1.2-0.9c0.5-0.4,1-0.9,1.5-1.4c-0.5-0.4-1-0.8-1.3-1.4c-0.3-0.5-0.3-1.1-0.2-1.6c0.2-0.5,0.8-0.7,1.2-0.4
	c0,0,0,0,0.1,0c0.7,0.4,0.7,1.8,0.6,2.4c0,0-0.2,0.5-0.3,0.8c0.5-0.5,0.9-1.1,1.2-1.7c0.2-0.3,0.4-0.6,0.6-1c-0.5-0.3-1-0.7-1.4-1.2
	c-0.3-0.4-0.4-1-0.3-1.5c0.2-0.5,0.7-0.7,1.1-0.6c0,0,0.1,0,0.1,0c0.7,0.3,0.9,1.7,0.8,2.4c0,0-0.1,0.4-0.2,0.7l0.2-0.4
	c0.2-0.5,0.4-1,0.6-1.5c0.1-0.2,0.2-0.5,0.2-0.7c-0.3-0.5-0.6-1.1-0.7-1.7c-0.1-0.5,0.1-1.1,0.4-1.5c0.4-0.3,0.9-0.3,1.3,0
	c0,0,0,0,0.1,0.1c0.5,0.6,0,1.9-0.4,2.5c0,0-0.7,0.7-0.7,0.7c-0.1,0.2-0.1,0.4-0.2,0.7c-0.2,0.4-0.3,0.9-0.6,1.5
	c-0.3,0.6-0.5,1.1-0.9,1.7c-0.3,0.6-0.8,1.2-1.2,1.7c0.2-0.1,0.7-0.4,0.8-0.5c0.6-0.3,2-0.4,2.5,0.2c0.3,0.4,0.3,0.9-0.1,1.3
	c0,0-0.1,0-0.1,0.1c-0.5,0.3-1.1,0.3-1.6,0.1c-0.6-0.3-1.1-0.6-1.6-1.1c-0.4,0.6-0.9,1.1-1.4,1.6l-1,0.8l0.3-0.2
	c0.6-0.3,2-0.4,2.5,0.2c0.3,0.4,0.3,0.9-0.1,1.3c0,0-0.1,0-0.1,0.1c-0.5,0.3-1.1,0.3-1.6,0.1c-0.5-0.3-1.1-0.6-1.5-1l-0.4,0.3
	c-0.6,0.5-1.2,0.9-1.8,1.4c-0.2,0.2-0.4,0.3-0.6,0.5l0.3-0.2c0.6-0.3,2-0.4,2.5,0.2c0.3,0.4,0.3,0.9-0.1,1.3c0,0-0.1,0-0.1,0.1
	c-0.5,0.3-1.1,0.3-1.6,0.1c-0.5-0.3-1-0.6-1.5-1c-0.2,0.2-0.4,0.4-0.6,0.5s-0.2,0.2-0.4,0.4l-0.3,0.4l-0.6,0.8l-0.4,0.5l0.6-0.5
	c0.6-0.4,1.9-0.7,2.5-0.2c0.4,0.3,0.4,0.9,0.1,1.3c0,0,0,0-0.1,0.1c-0.4,0.3-1,0.5-1.6,0.3c-0.6-0.2-1.2-0.5-1.7-0.8l-0.6,0.8
	c-0.7,0.9-1.2,1.7-1.6,2.3v0.1l-0.5-0.2l0.1-0.1c0.4-0.6,0.9-1.4,1.6-2.3c0.2-0.3,0.5-0.6,0.7-0.9c-0.3-0.3-0.5-0.6-0.7-0.9
	c-0.6,0.2-1.2,0.2-1.8,0.2c0,0.4,0,0.7-0.1,1v2.9l-0.5-0.2c0-0.7,0-1.6,0.1-2.6c0-0.4,0-0.8,0.1-1.2c-0.6-0.1-1.2-0.4-1.7-0.7
	c-0.5-0.3-0.7-0.8-0.8-1.4c0-0.5,0.4-0.9,0.9-0.9c0,0,0.1,0,0.1,0c0.8,0.1,1.4,1.3,1.5,2c0,0,0,0.5,0.1,0.8v-0.5
	c0-0.3,0.1-0.7,0.1-1c0-0.2,0-0.3,0.1-0.5s0.1-0.4,0.1-0.5c0.1-0.4,0.2-0.8,0.3-1.2c-0.6,0-1.2-0.2-1.8-0.4c-0.5-0.2-0.9-0.7-1-1.2
	c-0.1-0.5,0.3-1,0.8-1c0,0,0.1,0,0.1,0c0.8,0,1.6,1.1,1.8,1.7c0,0,0.1,0.5,0.2,0.8c0.1-0.2,0.2-0.5,0.2-0.8c0.2-0.7,0.5-1.4,0.8-2.2
	l0.2-0.7c-0.6,0-1.2-0.2-1.8-0.4c-0.5-0.2-0.9-0.7-1-1.2c-0.1-0.5,0.3-0.9,0.8-1c0,0,0,0,0,0c0.8,0,1.6,1.1,1.8,1.7
	c0,0,0.2,0.7,0.2,0.9c0.2-0.5,0.3-1,0.5-1.5c0.2-0.7,0.4-1.3,0.5-2c-0.6,0-1.3-0.2-1.8-0.4c-0.5-0.2-0.9-0.7-1-1.2
	c-0.1-0.5,0.3-1,0.8-1c0,0,0.1,0,0.1,0c0.8,0,1.6,1.1,1.8,1.7c0,0,0.1,0.6,0.2,0.8c0.1-0.7,0.1-1.4,0.1-2.1c0-0.4,0-0.7-0.1-1.1
	c-0.6,0-1.2,0-1.8-0.2c-0.5-0.2-0.9-0.6-1.1-1.1c-0.1-0.5,0.2-1,0.6-1.1c0,0,0.1,0,0.1,0c0.8-0.1,1.7,0.9,2,1.5c0,0,0.2,0.4,0.2,0.6
	v-0.5c-0.1-0.6-0.2-1.1-0.3-1.5l-0.2-0.7c-0.6-0.3-1.1-0.6-1.5-1c-0.4-0.4-0.5-1-0.5-1.5c0-0.5,0.5-0.9,1-0.8
	C62.3,322.5,62.3,322.5,62.4,322.5L62.4,322.5z"
            />
            <path
              class="st0"
              d="M76.2,334.3c-0.6-0.1-1.2-0.3-1.8-0.6c0,0,0.6-0.7,0.7-0.7c0.5-0.4,1.8-0.9,2.4-0.5c0.4,0.3,0.5,0.9,0.2,1.3
	c0,0,0,0.1-0.1,0.1C77.3,334.2,76.7,334.4,76.2,334.3L76.2,334.3z M69.2,349.2c0,0-3.6-8.7-5.6-8.3s3.4,13.9,3.4,13.9
	s-6.3-12-10.7-12s1.6,13.2,7.1,17.7c0,0-8.7-9.3-13.7-7.3s10.1,11.5,10.1,11.5S51,361.8,52,364s3.8,2.5,3.8,2.5l-10,0.5h34.7
	l-7.8-0.8c0,0,8.1-4,5.9-5.7s-6.9,1.9-6.9,1.9s8.2-9.1,6.6-12.5s-8.7,6.2-8.7,6.2s5.8-12.2,4.6-14.4S69.2,349.2,69.2,349.2
	L69.2,349.2z"
            />
            <path
              class="st7"
              d="M70.4,349.7c-1.8,5.1-2.9,10.5-3.2,16c2.8-0.1,5.4-1,7.7-2.7"
            />
            <path class="st7" d="M68.8,354.7c-0.7-2.8-1.5-5.6-2.6-8.2" />
            <path
              class="st7"
              d="M59.4,349.2l8.1,12c0,0,5.5-4.6,7.4-7.2 M67.3,364.1c0,0-8.5-4-12-6.4 M95.2,344.1h92.4"
            />
            <path class="st11" d="M133.5,322.3h1.9l-0.3,16.4h-2.5L133.5,322.3z" />
            <path
              class="st4"
              d="M101.2,335.9h16.2l1.8,2.3h65.4v-9h-82.1C102.5,329.1,101.2,335.9,101.2,335.9z"
            />
            <path
              class="st9"
              d="M94,321.6l0.1,12.5c0.1,0.6,0.6,1.1,1.2,1.3c1.2,0.1,2.4,0.2,3.7,0.1l3-5.5c0.5-1.5,1.9-2.4,3.4-2.5
	c2.7-0.1,14.8,0.6,14.8,0.6c1,0.4,1.8,1.3,2.1,2.4c0.5,1.9,0.3,7.6,0.3,7.6l11.1,0.3l0.4-16L94,321.6z"
            />
            <path
              class="st4"
              d="M180.6,337.6c0-3.7-3-6.8-6.8-6.8s-6.8,3-6.8,6.8c0,3.7,3,6.8,6.8,6.8c0,0,0,0,0,0
	C177.6,344.4,180.6,341.4,180.6,337.6L180.6,337.6z"
            />
            <path
              class="st9"
              d="M179.3,337.6c0-3-2.4-5.4-5.4-5.4s-5.4,2.4-5.4,5.4s2.4,5.4,5.4,5.4c0,0,0,0,0,0
	C176.8,343,179.3,340.6,179.3,337.6z"
            />
            <path
              class="st9"
              d="M177.3,337.6c0-1.9-1.5-3.5-3.5-3.5c-1.9,0-3.5,1.5-3.5,3.5c0,1.9,1.5,3.5,3.5,3.5c0,0,0,0,0,0
	C175.8,341.1,177.3,339.5,177.3,337.6L177.3,337.6z"
            />
            <path
              class="st9"
              d="M175.7,337.6c0-1-0.8-1.8-1.8-1.8s-1.8,0.8-1.8,1.8c0,1,0.8,1.8,1.8,1.8c0,0,0,0,0,0
	C174.9,339.4,175.7,338.6,175.7,337.6z"
            />
            <path
              class="st4"
              d="M119,337.6c0-3.7-3-6.8-6.7-6.8s-6.8,3-6.8,6.8c0,3.7,3,6.8,6.8,6.8c0,0,0,0,0,0C116,344.4,119,341.4,119,337.6
	z"
            />
            <path
              class="st9"
              d="M117.7,337.6c0-3-2.4-5.4-5.4-5.4c-3,0-5.4,2.4-5.4,5.4c0,3,2.4,5.4,5.4,5.4c0,0,0,0,0,0
	C115.2,343,117.6,340.6,117.7,337.6z"
            />
            <path
              class="st9"
              d="M115.7,337.6c0-1.9-1.5-3.5-3.5-3.5s-3.5,1.5-3.5,3.5c0,1.9,1.5,3.5,3.5,3.5c0,0,0,0,0,0
	C114.2,341.1,115.7,339.6,115.7,337.6C115.7,337.6,115.7,337.6,115.7,337.6z"
            />
            <path
              class="st9"
              d="M114,337.6c0-1-0.8-1.8-1.8-1.8s-1.8,0.8-1.8,1.8s0.8,1.8,1.8,1.8h0C113.2,339.4,114,338.6,114,337.6z
	 M138.7,311.1c0,0-2.8,0.1-2.8,0.5c0.1,0.4,0.2,0.8,0.4,1.1l-1.8,9.3c-0.2,0.9-0.3,1.8-0.3,2.8c0,0.9-0.3,13.4-0.3,13.4
	c0.2,0.4,0.6,0.7,1.1,0.7c0.9,0.1,28,0.5,28,0.5c0.6-0.3,1.1-0.7,1.4-1.1c0.8-0.9,4.5-5.7,8.9-7c2.9-1,6.1-0.5,8.6,1.4
	c1.1,1,1.2,4.5,1.3,5.2s1.4,0.7,1.6,0.7s1.9-0.2,2.3-0.7c0.3-0.7,0.5-1.5,0.6-2.3c0-0.2-0.1-0.5-0.2-0.7l1.2-5.2c0,0,0.3-1-0.1-1.2
	s-1.1-0.3-1.3-0.8s0.6-1.5,0-2.2s-2.4-1.5-3.8-1.8s-9.4-0.9-9.4-0.9l-12.7-0.7l-3.2-5l-2.8-4.3c0.2-0.3,0.1-0.6-0.1-0.8
	c0,0,0,0-0.1,0c-0.6-0.4-2.1-0.5-5.2-0.7S138.7,311.1,138.7,311.1L138.7,311.1z"
            />
            <path
              class="st9"
              d="M136.4,338.5l0.3-13.8c0,0-0.3-0.6,0.4-1.7c0.5-0.6,1-1.2,1.6-1.7l1.1-7.3c0.1-1,0.9-1.7,1.9-1.8
	c1.8-0.2,11.8,0.2,11.8,0.2l4.1,9.6c0.4,1.1,0.5,2.3,0.5,3.5c-0.1,1.9-0.6,13.5-0.6,13.5L136.4,338.5z M155.3,311.8
	c-0.6-0.4-2.1-0.5-5.2-0.7s-11.4,0-11.4,0s-2.8,0.1-2.8,0.5c0,0.2,0.1,0.3,0.1,0.5h19.5C155.5,312,155.4,311.9,155.3,311.8
	L155.3,311.8z"
            />
            <path
              class="st9"
              d="M151.6,313.3l-8.7-0.1c-0.8,0-1.5,0.6-1.6,1.3c-0.4,1.4-1,6.4-1,6.4s0,0.7,1,0.7s13.8,0.3,13.8,0.3
	c0.5,0,0.9-0.3,1-0.8c0,0,0-0.1,0-0.1c0-0.9-3-7.2-3-7.2S152.8,313,151.6,313.3L151.6,313.3z"
            />
            <path
              class="st4"
              d="M155,321.9l-4.3-0.1l1.3-8.6h0.2c0.5,0,0.9,0.3,1,0.7c0.4,0.7,3,6,3,6.8c0,0.6-0.5,1.1-1.1,1.1
	C155.1,321.9,155,321.9,155,321.9z M151.3,321.4l3.7,0.1c0.1,0,0.7,0,0.7-0.6s-1.8-4.4-3-6.7v0c0-0.1-0.1-0.2-0.3-0.3L151.3,321.4z"
            />
            <path
              class="st9"
              d="M151.9,313.3l-1.3,8.6h0.6l1.3-8.5C152.3,313.2,152.1,313.2,151.9,313.3z M158.2,317l-2.8-4.3
	c0,0-0.9,0-0.5,1.1s3,7.2,3,7.2c0.4,0.4,0.9,0.6,1.4,0.7c0.8,0.1,1.6,0.2,2.4,0.2v-0.1h-0.3L158.2,317z"
            />
            <path
              class="st4"
              d="M94.1,323.2l39.9,0.9l0-1.7L94,321.6C94,321.6,94,323.2,94.1,323.2z"
            />
            <path
              class="st2"
              d="M134.1,322.7l-40.9-1c-0.2,0-0.4-0.2-0.4-0.4c0-0.2,0.2-0.4,0.4-0.4l40.9,1c0.2,0,0.4,0.2,0.4,0.4
	C134.5,322.5,134.3,322.7,134.1,322.7L134.1,322.7z"
            />
            <path
              class="st7"
              d="M134.1,322.7L134.1,322.7l-40.9-1c-0.2,0-0.4-0.2-0.4-0.4c0-0.2,0.2-0.4,0.4-0.4l40.9,1c0.2,0,0.4,0.2,0.4,0.4
	C134.5,322.5,134.3,322.7,134.1,322.7L134.1,322.7z"
            />
            <path
              class="st9"
              d="M96.3,337.9l4.8,1l2.2-7.1c0,0,0.3-1.4,3.3-1.7s8.6-0.3,10.7,0.3s2.4,2.4,2.8,4.4s0.1,4.8,0.7,5.1
	s3.6,0.1,4.2-0.1s1.2-8,1-10s-2.4-4.2-5.6-4.3s-12.5-0.4-16.7,0.2s-5.7,2.4-6.3,5C96.9,333.1,96.5,335.5,96.3,337.9L96.3,337.9z
	 M187.1,337.9c0.3-0.7,0.5-1.5,0.6-2.3c0-0.2-0.1-0.5-0.2-0.7l1.2-5.2c0,0,0.3-1-0.1-1.2c-0.2-0.1-0.5-0.2-0.7-0.3
	c-4.4-0.3-14.9-0.9-19.1,1.2c-4.7,2.2-9.5,8.5-10.7,10.1l4.9,0.1c0.6-0.3,1.1-0.7,1.4-1.1c0.8-0.9,4.5-5.7,8.9-7
	c2.9-1,6.1-0.5,8.6,1.4c1.1,1,1.2,4.5,1.3,5.2s1.4,0.7,1.6,0.7S186.7,338.4,187.1,337.9L187.1,337.9z"
            />
            <path
              class="st9"
              d="M187.4,334.9h1.6l0.1,0.1c0.4,0.4,0.6,1.1,0.4,1.6l-0.4,1.4c-0.2,0.6-0.8,1-1.4,0.9l-1.4-0.2
	C185.8,337.3,186.3,335.7,187.4,334.9L187.4,334.9z"
            />
            <path
              class="st4"
              d="M139.9,322.8c0,0,0.1,0.5-0.2,0.6c-0.4,0.1-0.9,0-1.1-0.3c-0.3-0.3-0.1-0.7,0.6-0.7S139.9,322.8,139.9,322.8
	L139.9,322.8z"
            />
            <path
              class="st4"
              d="M138.4,322.7c1.5-0.3,3.1-0.3,4.6,0.1c-0.2,0.1-0.4,0.2-0.6,0.2C142.2,322.9,137.8,322.9,138.4,322.7z"
            />
          </svg>
        </div>
      </div>
    </div>

    <br /><br /><br /><br /><br /><br /><br /><br />
  </div>
</template>
<style scoped>
.fotter-download {
  position: relative;
}

.fotter-download .down-btn {
  width: 100% !important;
  margin: 0 !important;
}

.illustration-container {
  top: -120px;
  width: 100%;
  height: 400px;
  align-items: center;
  position: absolute;
  margin: 0 auto;
  z-index: -9;
  justify-content: space-around;
}
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

h4 {
  color: #505050;
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
  -o-transform: translate(-50%, -50%);
  -moz-transform: translate(-50%, -50%);
  -webkit-transform: translate(-50%, -50%);
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

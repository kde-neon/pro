<template>
  <!-- Home view -->
  <div keep-scroll-postion class="Home-view">
    <!-- Home enter front page -->
    <div class="full-card bg">
      <!-- app logo -->
      <div class="app-logo">
        <svg width="100%" viewBox="0 0 53.264 31">
          <path
            d="M53.188 11.735a3.08 3.08 0 0 0-.6-.957 19.716 19.716 0 0 0-2.867-2.469.254.254 0 0 0-.392.12l-.246.7a.253.253 0 0 0 .089.288 13.772 13.772 0 0 1 2.187 1.878.2.2 0 0 1-.2.3 22.5 22.5 0 0 1-2.312-.67 35.24 35.24 0 0 1-1.423-.555 6.231 6.231 0 0 0-.649-8.319 6.4 6.4 0 0 0-8.182-.534 6.294 6.294 0 0 0-2.124 2.721 31.282 31.282 0 0 1-1.214-.921 13.081 13.081 0 0 1-2.025-1.815c-.115-.146.047-.351.23-.309a29.723 29.723 0 0 1 2.951.989.23.23 0 0 0 .235-.042l.581-.528a.224.224 0 0 0-.068-.377A14.77 14.77 0 0 0 32.821 0a1.29 1.29 0 0 0-1.219.544c-.4.7.371 1.842 2.36 3.495a48.726 48.726 0 0 0 7.141 4.813c4.578 2.569 8.952 4.238 10.882 4.238a1.229 1.229 0 0 0 1.156-.476 1.017 1.017 0 0 0 .047-.879Zm-7.874.089a51.584 51.584 0 0 1-4.845-2.344c-1.575-.884-3.108-1.91-4.416-2.8a.313.313 0 0 0-.178-.058.322.322 0 0 0-.319.309c0 .063-.005.126-.005.183a6.2 6.2 0 0 0 1.857 4.442 6.391 6.391 0 0 0 7.952.821.3.3 0 0 0 .141-.288.3.3 0 0 0-.187-.265Z"
            fill="#f0f"
          />
          <text
            transform="translate(0 26)"
            fill="#fff"
            font-size="23"
            font-family="HelveticaRounded-Bold, Helvetica Rounded"
            font-weight="700"
          >
            <tspan x="0" y="0">Ziku</tspan>
          </text>
        </svg>
      </div>

      <!-- intro image -->
      <div @click.right.prevent="" class="intro-img flex">
        <img class="def" width="100%" src="../asset/img/intro.webp" alt="intro image" />
      </div>

      <!-- Service -->
      <div class="service">
        <!-- Entery text -->
        <div class="flex text">
          <h2 class="in-2">Hi, I’m Parvez Ahmed.</h2>

          <!-- love icon -->
          <div class="love-top-sml icon-sml flex">
            <svg width="100%" viewBox="0 0 512 512">
              <path
                fill="red"
                d="M352 56h-1c-39.7 0-74.8 21-95 52-20.2-31-55.3-52-95-52h-1c-61.9.6-112 50.9-112 113 0 37 16.2 89.5 47.8 132.7C156 384 256 456 256 456s100-72 160.2-154.3C447.8 258.5 464 206 464 169c0-62.1-50.1-112.4-112-113z"
              />
            </svg>
          </div>
        </div>
        <p>
          I create web based
          <u
            style="color: #00ff5a; cursor: pointer"
            title="Short: Don't create bad product."
            >Halal</u
          >
          front end user interface by using latest technology.
        </p>
      </div>
    </div>

    <!-- Info container -->
    <info />

    <!-- Tools container -->
    <tools />

    <!-- Projects -->
    <project />

    <!-- Fotter container -->
    <fotter />
  </div>
</template>
<script>
export default {
  name: "Home",
  data() {
    return {
      scp: 0,
    };
  },
  mounted() {
    var top = 0;

    // Get inner text and splite by span
    // Add every element a class
    var anm = document.querySelector(".anm-text");
    var anmText = anm.innerText.split(" ");

    anm.innerHTML = "";
    anmText.forEach((i) => {
      anm.innerHTML += `<span class="anw">${i}&nbsp;</span>`;
    });

    // Info --> animated word one by one function
    function anm_word(classAdd, clas, time) {
      var time = time ? time : 30;
      var anmWord = document.querySelectorAll(clas);
      for (var i = 0; i < anmWord.length; i++) {
        (function (speed, i) {
          setTimeout(function () {
            if(classAdd){
              anmWord[i].classList.add("on");
            }else {
              anmWord[i].classList.remove("on");
            }
          }, speed);
        })(i * time, i);
      }
    }

    // Info component all selector
    let info = document.getElementById("info");
    let infoPosition = info.getBoundingClientRect().bottom - window.innerHeight;
    let infoImg = document.querySelector(".info-img")
    let anmTitle = document.querySelector(".anmTitle");

    // Tool info component all selector
    let tool = document.querySelector(".img-tool");
    let toolInfo = document.querySelector(".tool-info");
    let toolPosition = tool.getBoundingClientRect().bottom - window.innerHeight;

    window.onscroll = () => {
      top = window.pageYOffset;

      // if clint view info component
      if (infoPosition < top) {
        anm_word(true, ".anw");
        anm_word(false, ".buble", 100)
        infoImg.classList.add("on");
        anmTitle.classList.add("on")
      }else {
        anm_word(false, ".anw");
        anm_word(true, ".buble", 100);
        infoImg.classList.remove("on");
        anmTitle.classList.remove("on")
      }

      // if clint view tool component
      if(toolPosition < top){
        anm_word(false, ".tool-box")
        tool.classList.remove("on")
        toolInfo.classList.remove("on");
      }else {
        anm_word(true, ".tool-box")
        tool.classList.add("on")
        toolInfo.classList.add("on");
      }
    };
  },
  middleware: ["scroll"],
};
</script>
<style>
.service {
  left: 20px;
  bottom: 80px;
  position: absolute;
}

.anw {
  opacity: 0;
  display: inline-block;
  transform: translateY(80px);
  transition: all 0.3s ease;
}

.anw.on {
  opacity: 1;
  transform: translateY(0px);
}

@media only screen and (min-width: 768px) {
  .service {
    left: 0;
    width: 100%;
    text-align: center !important;
  }
  .service .text {
    position: relative;
    display: inline-block;
    z-index: 9999;
    justify-content: center !important;
  }
  .love-top-sml {
    right: 0;
    width: 25px;
    height: 25px;
    z-index: -9;
    margin-top: -30px;
    position: absolute;
  }
}
</style>

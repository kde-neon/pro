<template>
  <div class="project-container">
    <br />
    <!-- Project title -->
    <h3 class="proTitle">My some porjects</h3>
    <p class="proWord">Hover on card for show details and wheel to show more project</p>
    <br /><br />

    <!-- Projects card container -->
    <div ref="slide" class="project-card-container flex">
      <div
        @click.right.prevent=""
        @wheel.prevent="slide"
        v-for="(obj, i) in projects"
        :key="i"
        class="card flex project on"
      >
        <!-- img -->
        <div class="img">
          <img
            width="100%"
            v-bind:src="require(`@/asset/img/${obj.img}`)"
            :alt="obj.title"
          />
        </div>

        <!-- Download down side -->
        <div class="info-card">
          <h3>{{ obj.name }}</h3>

          <!-- More info card -->
          <div class="more-info">
            <span>{{ obj.details }}</span>
            <NuxtLink class="def" :to="obj.to">
              <div class="icon-border flex">
                <div class="icon flex">
                  <svg width="100%" height="100%" viewBox="0 0 384 512">
                    <path
                      fill="#fff"
                      d="M361 215c14.3 8.8 23 24.3 23 41s-8.7 32.2-23 40.1l-287.97 176c-14.82 9.9-33.37 10.3-48.51 1.8A48.02 48.02 0 0 1 0 432V80a48.02 48.02 0 0 1 24.52-41.87 48.019 48.019 0 0 1 48.51.91L361 215z"
                    />
                  </svg>
                </div>
              </div>
            </NuxtLink>
          </div>
        </div>
      </div>
    </div>

    <!-- Just for project of view -->
    <div id="projectView"></div>
  </div>
</template>
<script>
export default {
  name: "project",
  data() {
    return {
      projects: [
        {
          name: "Chat Bot",
          details: "small chat bot for web app",
          to: "/projects/bip",
          img: "project-i.jpg",
        },
        {
          name: "Landging page",
          details: "Landging page with css",
          to: "/about",
          img: "project-ii.jpg",
        },
      ],
    };
  },

  methods: {
    slide(e) {
      e.preventDefault();
      var slide = this.$refs.slide;
      const race = 35;
      if (e.deltaY > 0) {
        slide.scrollLeft += race;
      } else {
        slide.scrollLeft -= race;
      }
    },
  },
};
</script>
<style scoped>
.project-container {
  width: 90%;
  margin: 20vh auto;
}

.proWord {
  width: 95%;
  max-width: 400px;
  display: inline-block;
  overflow-wrap: break-word;
}

.project {
  filter: blur(0px);
  transition: all 0.4s ease;
}

.project.on {
  filter: blur(30px);
  transform: translateX(400px) scale(0);
  transform-origin: right;
}


@media only screen and (max-width: 320px) {
  .project-container {
    width: 99%;
  }
}

.project-card-container {
  overflow: auto;
  scrollbar-width: none;
}

.project-card-container::-webkit-scrollbar {
  display: none;
  scrollbar-width: none;
}

/* Poroject card container */
.project-card-container .card {
  padding: 5px;
  width: 300px;
  height: 150px;
  min-width: 300px;
  margin: 5px 6px;
  border-radius: 4px;
  overflow: hidden;
  position: relative;
  border: solid 2px transparent;
}

.project-card-container .img {
  width: 100%;
  top: 0;
  left: 0;
  bottom: 0;
  z-index: -1;
  position: absolute;
}

.project-card-container .info-card {
  width: 100%;
  left: 0px;
  bottom: -55px;
  color: #dfdfdf;
  line-height: 40px;
  position: absolute;
  padding: 20px 20px;
  font-family: sans-serif;
  transition: all 0.3s ease;
  background: linear-gradient(to top, black, transparent);
}

.project-card-container .info-card h3 {
  color: #ffffff !important;
}

.project-card-container .card:hover {
  border-color: #0066ff;
}

.project-card-container .card:hover .info-card {
  bottom: 0;
  line-height: 25px;
}

.project-card-container .card:hover .img img {
  filter: blur(2px);
  -webkit-filter: blur(2px);
  -moz-filter: blur(2px);
  -o-filter: blur(2px);
}

.project-card-container .card:hover .icon-border {
  right: 65px;
}

/* Preview icon border */
.icon-border {
  right: -5px;
  bottom: 15px;
  width: 30px;
  height: 30px;
  padding: 5px;
  position: absolute;
  border-radius: 50%;
  align-items: center;
  justify-content: center;
  transition: all 0.3s ease-in-out;
  border: dashed 3px #ffffff;
}

.icon-border .icon {
  width: 30px;
  height: 30px;
  background: #0066ff;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
}

.icon-border .icon svg {
  width: 15px;
  height: 15px;
}

.icon-border:hover {
  transition: all 0.2s ease-in-out;
  animation: rotate 10s linear infinite;
}

.icon-border:hover:active {
  background: #0066ff;
}

.icon-border:hover svg {
  transition: all 0.2s ease-in-out;
  animation: rotateNg 10s linear infinite;
}

@keyframes rotate {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}


@keyframes rotateNg {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(-360deg);
  }
}
</style>

<template>
  <div class="info-container">
    <!-- Container -->
    <div id="info" class="asset-3d">
      <!-- container object -->
      <div class="object flex mt-10px">
        <!-- Asset image -->
        <div @click.right.prevent="" class="asset-img info-img">
          <img class="full def" src="../asset/img/Crean.webp" alt="Crean png" />
        </div>

        <!-- buble small and big for animation -->
        <div class="pa b-s rou buble on">
          <svg viewBox="0 0 200 200" >
            <path
              fill="rgb(255, 0, 102)"
              d="M46.7,-38.7C57.9,-23.3,62.5,-4,59.4,15.2C56.4,34.3,45.6,53.3,29.5,60.9C13.5,68.5,-7.9,64.6,-29.1,56C-50.4,47.5,-71.5,34.3,-74.9,17.6C-78.4,0.8,-64.2,-19.5,-48.7,-35.9C-33.3,-52.3,-16.7,-64.8,0.6,-65.3C17.8,-65.7,35.6,-54.1,46.7,-38.7Z"
              transform="translate(100 100)"
            />
          </svg>
        </div>
        <div class="pa b-l rou buble on">
          <svg viewBox="0 0 200 200">
            <path
              fill="rgb(251, 255, 0)"
              d="M64.9,-45.8C78.8,-34.2,81.3,-7.5,73.1,12.1C65,31.7,46.2,44.4,27,52.2C7.7,60,-12.1,63,-32.5,57.2C-53,51.3,-74.3,36.5,-79.5,17.1C-84.8,-2.4,-74.2,-26.5,-58.3,-38.5C-42.3,-50.5,-21.2,-50.3,2.1,-52C25.4,-53.7,50.9,-57.3,64.9,-45.8Z"
              transform="translate(100 100)"
            />
          </svg>
        </div>
        <div class="pa b-m b-right rou buble on">
          <svg viewBox="0 0 200 200" >
            <path
              fill="rgb(0, 238, 255)"
              d="M64.1,-49.1C80.1,-31.1,88.1,-4.6,82.3,18.1C76.6,40.7,57.1,59.5,34.8,69C12.4,78.5,-12.8,78.8,-33.9,69.1C-54.9,59.4,-71.7,39.8,-75.6,18.5C-79.5,-2.8,-70.4,-25.9,-55.6,-43.7C-40.9,-61.5,-20.4,-74,1.8,-75.4C24.1,-76.9,48.1,-67.2,64.1,-49.1Z"
              transform="translate(100 100)"
            />
          </svg>
        </div>
        <div class="pa b-m rou buble on">
          <svg viewBox="0 0 200 200" >
            <path
              fill="#0084ff"
              d="M36.8,-17.9C47.7,-2.4,56.5,17.7,50,34.8C43.5,51.8,21.8,66,-3,67.7C-27.8,69.5,-55.5,58.8,-62.9,41.1C-70.3,23.5,-57.4,-1.1,-43.5,-18.3C-29.6,-35.5,-14.8,-45.3,-0.9,-44.8C12.9,-44.3,25.9,-33.3,36.8,-17.9Z"
              transform="translate(100 100)"
            />
          </svg>
        </div>
      </div>

      <!-- Hi -->
      <center class="inf">
        <h2 class="anmTitle">I create</h2>
        <p class="anm-text">
          Front end single page app & progressive web app & I do design. I have more then
          3 years experience, I did some big project those take to finish month after
          month. I love my work. The creativity and enthusiasm of my choice.
        </p>
        <br />
      </center>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      scp: 0,
    };
  },

  // Component name
  name: "info",
};
</script>
<style scoped>
.info-container {
  margin: 30vh 0;
}

/* round animate buble */
.b-s {
  width: 20px;
  height: 20px;
  transform: translate(-80px, -90px);
}

.b-m {
  width: 30px;
  height: 30px;
  transform: translate(80px, 90px);
}

.b-l {
  width: 35px;
  height: 35px;
  transform: translate(-120px, 15px);
}

.b-right {
  transform: translate(100px, -40px);
}

.buble {
  filter: blur(0px);
  opacity: 1;
  transition: all .4s ease-in-out;
}

.buble.on {
  opacity: 0;
  filter: blur(10px);
  transition: all .4s ease;
  transform: translateY(500px);
}

.info-img {
  opacity: 0;
  filter: blur(10px);
  transition: all .4s ease;
  transform: translateY(400px);
}

.info-img.on {
  opacity: 1;
  filter: blur(0px);
  transform: translateY(0px);
}

/* Animated title */
.anmTitle {
  opacity: 0;
  filter: blur(20px);
  transform: scale(0);
  transition: all .4s ease;
}

.anmTitle.on {
  opacity: 1;
  filter: blur(0px);
  transform: scale(1);
}

.asset-img {
  width: 130px;
  height: 130px;
  border-radius: 50%;
  background: #6f00ff;
}

.inf {
  width: 95%;
  margin-top: 30px;
  max-width: 500px;
  margin: 25px auto;
  font-family: ziku !important;
}
</style>

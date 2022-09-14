<template>
  <div class="info-container">
    <!-- Container -->
    <div class="asset-3d">
      <!-- container object -->
      <div class="object flex mt-10px">
        <!-- Asset image -->
        <div @click.right.prevent="" class="asset-img">
          <img class="full def" src="../asset/img/Crean.webp" alt="Crean png" />
        </div>

        <!-- buble small and big for animation -->
        <div class="pa b-s rou tf-1"></div>
        <div class="pa b-l rou tf-2"></div>
        <div class="pa b-m rou tf-3"></div>
        <div style="pa background: #bade6c;" class="b-m rou tf-4"></div>
      </div>

      <!-- Hi -->
      <center class="inf">
        <h2>I create</h2>
        <p>
          Front End Single Page App & Progressive Web App & I do Design. I Have More Then 3
          Years Experience, I Did Some Big Project Those Take To Finish Mont After Month. I
          Love My Work. The creativity and enthusiasm of my choice.
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

  mounted() {
    window.onscroll = () => {
      this.scp = window.pageYOffset;
    };
  },

  // Component name
  name: "info",
};
</script>
<style scoped>
.asset-img {
  width: 130px;
  height: 130px;
  border-radius: 50%;
  background: #6f00ff;
}

.tf-1 {
  background: orangered;
  transform: translate(90px, -100px);
}

.tf-2 {
  background: orange;
  transform: translate(-90px, -100px);
}

.tf-3 {
  transform: translate(60px, 98px);
}

.tf-4 {
  background: #ff00f2;
  transform: translate(-200px, 30px);
}

.inf {
  margin-top: 30px;
}
.inf {
  width: 95%;
  max-width: 500px;
  margin: 25px auto;
}
</style>

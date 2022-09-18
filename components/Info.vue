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
        <div class="pa b-s rou"></div>
        <div class="pa b-l rou"></div>
        <div class="pa b-m rou"></div>
        <div class="pa b-m rou"></div>
      </div>

      <!-- Hi -->
      <center class="inf">
        <h2>I create</h2>
        <p class="anm-text">Front end single page app & progressive web app & I do design. I have more then
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

<template>
  <div class="project-container">

    <br>
    <!-- Project title -->
    <h3>My some porjects</h3>
    <span>Hover on card for show details and wheel to show more project</span>
    <br><br>

    <!-- Projects card container -->
    <div @wheel.self="slide" ref="slide" class="project-card-container flex">
      <div @wheel.self="slide" v-for="i in 10" :key="i" class="card">
        {{ i }}
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "project",
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
  setup() {
    console.log("You can run js code");
  },
};
</script>
<style scoped>
.project-container {
  width: 95%;
  margin: 0 auto;
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
  width: 90%;
  padding: 5px;
  height: 150px;
  min-width: 300px;
  margin: 5px 6px;
  max-width: 500px;
  border-radius: 4px;
  background: red;
}
</style>

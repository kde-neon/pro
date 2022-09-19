<template>
  <div class="tools-container">
    <!-- Tools image -->
    <div @click.right.prevent="" class="img-tool on def">
      <img class="full def" src="../asset/img/Trofie.webp" alt="Tools" srcset="" />
    </div>

    <!-- Tool title -->
    <center class="tool-info on">
      <h2>Production Tools</h2>
      <span>My most used production tools</span>
      <br /><br />
    </center>

    <!-- Production tools are -->
    <div class="tec-cont flex">
      <div v-for="(name, i) in tools" :key="i" class="list flex tool-box on">
        <!-- Tool icon -->
        <div class="icon flex">
          <svg width="100%" height="100%" viewBox="0 0 512 512">
            <path
              d="M461.8 53.6c-.4-1.7-1.6-3-3.3-3.4-54.4-13.3-180.1 34.1-248.2 102.2-13.3 13.3-24.2 26.4-33.1 39.1-21-1.9-42-.3-59.9 7.5-50.5 22.2-65.2 80.2-69.3 105.1-1 5.9 3.9 11 9.8 10.4l81.1-8.9c.1 7.8.6 14 1.1 18.3.4 4.2 2.3 8.1 5.3 11.1l31.4 31.4c3 3 6.9 4.9 11.1 5.3 4.3.5 10.5 1 18.2 1.1l-8.9 81c-.6 5.9 4.5 10.8 10.4 9.8 24.9-4 83-18.7 105.1-69.2 7.8-17.9 9.4-38.8 7.6-59.7 12.7-8.9 25.9-19.8 39.2-33.1 68.4-68 115.5-190.9 102.4-248zM298.6 213.5c-16.7-16.7-16.7-43.7 0-60.4 16.7-16.7 43.7-16.7 60.4 0 16.7 16.7 16.7 43.7 0 60.4-16.7 16.7-43.7 16.7-60.4 0z"
            />
            <path
              d="M174.5 380.5c-4.2 4.2-11.7 6.6-19.8 8-18.2 3.1-34.1-12.8-31-31 1.4-8.1 3.7-15.6 7.9-19.7l.1-.1c2.3-2.3.4-6.1-2.8-5.7-9.8 1.2-19.4 5.6-26.9 13.1-18 18-19.7 84.8-19.7 84.8s66.9-1.7 84.9-19.7c7.6-7.6 11.9-17.1 13.1-26.9.3-3.2-3.6-5.1-5.8-2.8z"
            />
          </svg>
        </div>

        <!-- Tool name -->
        <div class="text">
          <h4>{{ name }}</h4>
        </div>
      </div>
    </div>

    <br />

  </div>
</template>
<script>
export default {
  name: "Tool",
  data() {
    return {
      tools: ["Html5", "Css3", "JavaScript", "Vue3", "Nuxt3", "Vue Cli", "Nuxt Cli"],
    };
  },
};
</script>
<style>
.tools-container {
  margin: 20vh 0;
}
.tec-cont {
  width: 90%;
  min-width: 200px;
  max-width: 600px;
  margin: 0 auto;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}

/* Image tools */
.img-tool {
  opacity: 1;
  width: 150px;
  margin: 0 auto;
  transition: all .4s ease;
}

.tool-info {
  opacity: 1;
  filter: blur(0px);
  transition: all .4s ease;
}

.img-tool.on,
.tool-info.on {
  opacity: 0;
  filter: blur(20px);
  transform: translateY(400px);
}

/* tools list */
.list {
  padding: 5px 10px;
  margin: 3px 5px;
  align-items: center;
  justify-content: left;
  border: solid 1px transparent;
  border-radius: 4px;
}

/* tools list iocn */
.list .icon {
  width: 20px;
  height: 20px;
  padding-left: 5px;
  align-items: center;
  justify-content: left;
}

.list .icon svg path {
  fill: #0066ff;
}

.list .text {
  cursor: default;
  margin-left: 5px;
}

.list:hover {
  background: rgba(0, 132, 255, 0.13);
  transform: matrix3d(1, 0, 0, 0, 0, 1, 1.5, 0, 0, 0, 1, 0, 0, 0, 0, 1);
}

.tool-box {
  opacity: 1;
  filter: blur(0px);
  transition: all 0.4s ease;
}

.tool-box.on {
  opacity: 0;
  filter: blur(20px);
  transform: translateY(400px);
}
</style>

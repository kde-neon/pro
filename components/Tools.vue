<template>
  <div class="tools-container">
    <!-- Tools image -->
    <div @click.right.prevent="" class="img-tool def">
      <img class="full def" src="../asset/img/Trofie.webp" alt="Tools" srcset="" />
    </div>

    <!-- Tool title -->
    <center>
      <h2>Production Tools</h2>
      <span>My most used production tools</span>
      <br /><br />
    </center>

    <!-- Production tools are -->
    <div class="tec-cont flex">
      <div v-for="(name, i) in tools" :key="i" class="list flex">
        <!-- Tool icon -->
        <div class="icon flex">
          <svg width="20.509" height="22.215" viewBox="0 0 20.509 22.215">
            <path
              id="md-flask"
              d="M83.888,64.362,78.5,55.69V50.563h1.709V48H68.247v2.563h1.709V55.69l-5.335,8.672a4.972,4.972,0,0,0-.646,2.435,3.43,3.43,0,0,0,3.476,3.418H81.116A3.336,3.336,0,0,0,84.481,66.8,4.877,4.877,0,0,0,83.888,64.362ZM68.84,61.671l1.575-2.563h7.642l1.591,2.563Z"
              transform="translate(-63.973 -48)"
              fill="#002bff"
            />
          </svg>
        </div>

        <!-- Tool name -->
        <div class="text">
          <h4>{{ name }}</h4>
        </div>
      </div>
    </div>
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
  width: 150px;
  margin: 0 auto;
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
  widows: 25px;
  height: 25px;
  padding-left: 5px;
  align-items: center;
  justify-content: left;
}

.list .text {
  margin-left: 5px;
}

.list:hover {
  background: rgba(38, 0, 255, 0.075);
}
</style>

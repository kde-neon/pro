<template>
  <div class="info-container">
    <h2 ref="txt">Hi</h2>
  </div>
</template>
<script>
export default {
  data(){
    return {
      scp: 0,
    }
  },

  mounted(){
    window.onscroll = ()=> {
      this.scp = window.pageYOffset;
    }
  },

  // Component name
  name: "info",
}
</script>

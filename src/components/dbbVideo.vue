<template>
  <div class="z_video">
      <!-- autoplay="autoplay" -->
    <video controls="controls" autoplay="autoplay">
      <source :src="picData.logo" type="video/ogg" />
      <source :src="picData.video" type="video/mp4" />
    </video>
  </div>
</template>

<style scoped>
  .z_video {
    width: 100%;
    font-size: .28rem;
    margin: 0 auto;
    text-align: center;
  }
  .z_video video {
      width: 90%;
      /* width: 7.5rem; */
      margin: 0 auto;
  }

</style>


<script>
    export default {
        data(){
            return {
                picData: {
                    logo: require('../assets/logo.png'),
                    video: require('../assets/201.mp4')
                }
            }
        }
    }

</script>

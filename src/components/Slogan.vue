<template>
  <div class="slogan">
    <span id="title">生日快乐</span><br>
    <span id="from" @click="test" >     芝芝仙女 2022年10月23日</span>
    <audio id="audio" src="/static/audio/cyx.mp3" controls="controls" hidden="hidden" autoplay="autoplay"  loop="loop"> </audio>
  </div>
</template>

<script>
  export default {
    name: "Slogan",
          methods: {
          test(){
            let vo = document.getElementById("audio")
            vo.autoplay = true
            vo.play()
          }
      }
  }
</script>

<style>
  .slogan {
    padding-top: 1em;
    text-align: center;
  }
  #title {
    color: white;
    font-size: 3em;
  }
  #titl {
    color: white;
    font-size: 3em;
  }
  #from {
    color: white;
    opacity: 0.4;
    font-size: 1.5em;
  }
</style>

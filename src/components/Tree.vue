<template>
  <div>
    <div class="container">
      <div class="tree">
        <div class="shadow ts-3d"></div>
        <div class="trunk ts-3d">
          <div></div>
          <div></div>
          <div></div>
          <div></div>
        </div>
        <div class="leaves-bottom ts-3d">
          <div></div>
          <div></div>
          <div></div>
          <div></div>
        </div>
        <div class="leaves-middle ts-3d">
          <div class="ts-3d"></div>
          <div class="ts-3d"></div>
          <div class="ts-3d"></div>
          <div class="ts-3d"></div>
        </div>
        <div class="leaves-top ts-3d">
          <div class="ts-3d"></div>
          <div class="ts-3d"></div>
          <div class="ts-3d"></div>
          <div class="ts-3d"></div>
        </div>
        <div class="star star-1 ts-3d"></div>
        <div class="star star-2 ts-3d"></div>
        <div class="star star-3 ts-3d"></div>
        <div class="star star-4 ts-3d"></div>
        <div class="star star-5 ts-3d"></div>
        <div class="shine ts-3d"></div>
      </div>
      <div id="snow" class="snow-container">
        <div class="snow snow-1 snow-y-1"></div>
        <div class="snow snow-2 snow-y-2"></div>
        <div class="snow snow-3 snow-y-3"></div>
        <div class="snow snow-4 snow-y-3"></div>
        <div class="snow snow-5 snow-y-2"></div>
        <div class="snow snow-6 snow-y-1"></div>
        <div class="snow snow-7 snow-y-1"></div>
        <div class="snow snow-8 snow-y-2"></div>
        <div class="snow snow-9 snow-y-3"></div>
        <div class="snow snow-10 snow-y-3"></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
  .container {
    padding-top: 10em;
    opacity: 0.8;
    background-image: linear-gradient(-20deg, #ee9ca7 0%, #ffdde1 70%);
  }
</style>

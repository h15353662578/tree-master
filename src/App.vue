<template>
  <div id="app">
    <Tree/>
    <Slogan/>
  </div>
</template>

<script>
import Tree from './components/Tree'
import Slogan from './components/Slogan'

export default {
  name: 'App',
  components: {
    Tree, Slogan
  }
}
</script>

<style>
  #app {
    height: 100%;
    background-image: linear-gradient(-20deg, #ee9ca7 20%, #ffdde1 80%);
  }
</style>

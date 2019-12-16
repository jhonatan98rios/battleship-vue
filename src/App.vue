<template>
  <div id="app">
    <Menu class="hide" />
    <Game class="show" />
  </div>
</template>

<script>
import Menu from './components/Menu.vue'
import Game from './components/Game.vue'

export default {
  name: 'app',
  components: {
    Menu,
    Game
  }
}
</script>

<style lang="scss">
body{
  margin: 0 auto;

  .hide{
    display: none
  }

  .show{
    display: block
  }

  #app{
    width: 100vw;
    height: 100vh;
    margin: 0 auto;
    padding: 0;
    background-repeat: no-repeat;
  }
}

</style>

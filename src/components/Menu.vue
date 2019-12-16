<template>
  <div class="menu">
    <Header isMenu />
    <Options />
  </div>
</template>

<script>
import Header from './Header.vue'
import Options from './Options.vue'

export default {
  components: {
    Header,
    Options
  },
  data: ()=>{
    return{
      title: 'Battleship',
    }
  },

  methods: {

  }
}
</script>

<style scoped lang="scss">
.menu{
  background-image: linear-gradient(#01B3EA,#06a,#001);
  background-size:  100% 100%;
  height: 100vh;
}
</style>

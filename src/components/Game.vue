<template>
  <div class="game">
    <Header />
    <Field />
  </div>
</template>

<script>
import Header from './Header.vue'
import Field from './Field.vue'

export default {
  components: {
    Header,
    Field
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

.game{
  background-image: linear-gradient(#01B3EA,#06a,#001);
  width: 100%;
  height: 100vh;
}

</style>

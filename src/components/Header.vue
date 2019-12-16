<template>
  <div class="header">
    <h1 class="logo logo-center" v-class="{ 'p-t-200' : isMenu }" v-html="this.title"/>
  </div>
</template>

<script>
export default {

  data(){
    return{
      title: 'Battleship',
      menu: true
    }
    
  },

  props:{
    isMenu: Boolean
  },

  methods: {

  }
}
</script>

<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css?family=Lemon&display=swap');

.header{
	margin: 0 auto;
  text-align: center;

  .p-t-200{
    padding-top: 200px;
  }

  .logo{
    margin: 0 auto;
    font-family: 'Lemon', cursive;
    font-size: 60px;
    padding: 50px 0;
    line-height: 50px;
    font-weight: bolder;
    -webkit-text-stroke-width: 1px;
    -webkit-text-stroke-color: #fff;
    background: -webkit-linear-gradient(#08c, #3cf, #08c);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    filter: drop-shadow(1px 1px 3px #035);
  }
}



</style>

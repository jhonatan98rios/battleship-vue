<template>
  <div class="options">
    <div class="buttons">
      <button class="button_play"> Play </button>
    </div>
  </div>
</template>

<script>
export default {
  methods: {

  }
}
</script>

<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css?family=Lemon&display=swap');

.options{
  align-items: center;
  width: 100%;

  .buttons{
    width: 230px;
    margin: 0 auto;  

    .button_play{
      width: 230px;
      height: 60px;
      margin: 10px auto;
      font-size: 25px;
      border-radius: 20px;
      background-image: linear-gradient(#3cf, #0ae);
      border: none;
      box-shadow: 1px 1px 10px #035;
      color: #fff;
      font-weight: bolder;
    }
  }
}


</style>

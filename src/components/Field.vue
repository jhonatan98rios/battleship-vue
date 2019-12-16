<template>
  <div class="field">
    <table id="campo">
			<tr> 
				<th id="a1"> </th>
				<th id="a2"> </th>
				<th id="a3"> </th>
				<th id="a4"> </th>
				<th id="a5"> </th>
			</tr>
			<tr> 
				<th id="b1"> </th>
				<th id="b2"> </th>
				<th id="b3"> </th>
				<th id="b4"> </th>
				<th id="b5"> </th>
			</tr>
			<tr>
				<th id="c1"> </th>
				<th id="c2"> </th>
				<th id="c3"> </th>
				<th id="c4"> </th>
				<th id="c5"> </th>
			</tr>
			<tr>
				<th id="d1"> </th>
				<th id="d2"> </th>
				<th id="d3"> </th>
				<th id="d4"> </th>
				<th id="d5"> </th>
			</tr>
			<tr>
				<th id="e1"> </th>
				<th id="e2"> </th>
				<th id="e3"> </th>
				<th id="e4"> </th>
				<th id="e5"> </th>
			</tr>
		</table>
  </div>
</template>

<script>
export default {

  data(){
    return{
    }
  },

  methods: {
    
  }
}
</script>

<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css?family=Lemon&display=swap');

table{
  border-spacing: 0px;
  margin: 0 auto;
	background-image: url('../assets/texture.jpg');
	background-size: 100% 100%;
	border: 1px solid rgb(39, 38, 38);
	width: 95%;
  max-width: 600px;
  max-height: 600px;
	height: 90vw;

  tr th{
    border: 1px solid #fff;
    margin: 0px auto;
    padding: 0px;
    width: calc(20% - 2px);
    height: calc(20% - 2px);
    background-image: url('../assets/x.png');
    background-size: 0%;
    font-size: 0px;
  }
}


</style>

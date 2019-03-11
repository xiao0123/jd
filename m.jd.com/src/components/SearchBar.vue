<template>
	<div class="search-bar">
		<div class="category"></div>
		<div class="search-from">
			<input type="text" name="" id="" value="" />
		</div>
		<div class="login"></div>
	</div>
</template>

<script>
	export default{
		data:function(){
			return {};
		},
		methods:{},
		props:[],
		watch:{},
		computed:{},
		created:function(){},
		
		
	}
	
</script>

<style>
.search-bar {
		height: 44px;
		background-color: red;
		position: relative;
	}
.search-bar .category,.search-bar .login{
	width: 50px;
	height: 44px;
	background-color: yellow;
	position: absolute;
	top:0px;
	left: 0px;
}
.search-bar .login{
	right:0px;
	left: auto;
}
.search-bar .search-from{
	width:100%;
	padding:0px 50px;
	padding-top: 7px;
	box-sizing: border-box;
}
.search-bar .search-from input{
	width:100%;
	height: 30px;
	border-radius: 15px;
	box-sizing: border-box;
	border-right-color: white;
}


</style>
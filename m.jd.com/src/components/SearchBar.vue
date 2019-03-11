<template>
	<div class="search-bar flex">
		<div class="category">
			<span class="icon"></span>
		</div>
		<div class="search-from flex-item">
			<span class="icon"></span>
			<input type="text" name="" id="" value="" />
		</div>
		<div class="login"><a href="#">登录</a></div>
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
	.search-bar{
		height: 44px;
		background-color: red;
	}
	.search-bar .category,.search-bar .login{
		width: 50px;
		height: 44px;
		/*background-color: yellowgreen;*/
	}
	.search-from{
		position: relative;
		padding-top: 7px;
	}
	.search-from input{
		width:100%;
		height: 30px;
		border-radius: 15px;
		border-right-color: white;
		border: none;
		
	}
	.login a{
		line-height: 44px;
		font-size: 14px;
		color: white;
		padding-left: 10px;
	}
	.category .icon{
		margin: 14px 0 0 15px;
	    width: 20px;
	    height: 18px;
	    display: block;
	    background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACgAAAAgAgMAAAAdw9KTAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAAAMUExURUdwTP///////////waf0AoAAAADdFJOUwDjSYAlncUAAAAbSURBVBjTY5j/Hwq+MdTDmH+RmUgK6AuGhcsAU5tyB6Ji+x0AAAAASUVORK5CYII=) no-repeat;
	    background-size: 100% 100%;
	}
	.search-from .icon{
		 width: 20px;
	    height: 15px;
	    background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACgAAAAeBAMAAACs80HuAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAAAwUExURUdwTOk7Puo7PfE+SP9SUuo7Peo8Pu0/Qeo7Peo7Peo7Pek7Peo7Pes8Pus8P+k7PaLYf6IAAAAPdFJOUwCjwREGj1sg9Hrd6bFINxDM6d8AAAD3SURBVCjPY2AAAv3/nxnk////sUo1nQEOoIIgoOaARfD/WmyC/wNQBL+lzZQCCn5FEfwCZJX2//8/AV2Qoej//3YMQWb9/x8xBBkq/v8vwBBk/f8/AUOQ/f9/AQxBhvX/N2AKnv//AVMwHsjBEJz//zs2lVgE5bFpx2pR//8FUMEvcEE+mOPX/2+AC/JAvcnyH6gDJvj+/w8DEM0G0gEVZN8PDfpqkA6o4O3//5tBtGX//98OEEHmJGAkXWBgCNQC0t9Abv4aKrMewmYAR6sAAzyKfydABX8yIASFGSCCjQ/ggr+mg61WOjgXnHwmKSnpiM4FO5EBAIlo6/K7pNY1AAAAAElFTkSuQmCC) no-repeat;
	    background-size: 20px 15px;
	    margin: 8px 8px 0 15px;
	    position: absolute;
	    z-index: 1;
	    float: left;
	}
	
/*.search-bar {
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
}*/


</style>
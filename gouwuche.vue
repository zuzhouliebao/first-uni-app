<template>
	<meta charset="utf-8" />
	<title></title>
	<title>v-on指令练习</title>
	<!-- 开发环境版本，包含了有帮助的命令行警告 -->
	<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
	<style type="text/css">
			html{
			font-family: -apple-system,"Helvetica Neue",Arial,"PingFang SC","Hiragino Sans GB",STHeiti,"Microsoft YaHei","Microsoft JhengHei","Source Han Sans SC","Noto Sans CJK SC","Source Han Sans CN","Noto Sans SC","Source Han Sans TC","Noto Sans CJK TC","WenQuanYi Micro Hei",SimSun,sans-serif;
		}
		.container{
			display: flex;
			flex-direction: column;
		    width:95%;
			margin: 0 auto;
		}
		.item{
			display: flex;
			border: 1px solid #eee;
			border-radius: 10px;
			width: 95%;
			height: 100px;
			margin-bottom: 10px;
			/* 垂直方向居中 */
			align-items: center;
			/* 水平方向居中 */
			/* justify-content: center; */
			padding-left: 10px;
			padding-right: 10px;
		}
		.item-id{
			flex: 1 1 5%;
		}
		.item-img{
			flex: 1 1 20%;
		}
		.item-name{
			flex: 1 1 30%;
		}
		.item-price{
			flex: 1 1 20%;
		}
		.item-count{
			/* display: flex; */
			flex: 1 1 30%;
		}
		.goods-count{
			width: 15px;
		}
		.submit{
			
			border: 1px #3083ff solid;
			border-radius: 4px;
			background-color: #3487ff;
			box-shadow: 0 5px 8px 0 rgba(24,95,255,.1);
			color: #fff;
			text-align: center;
			font-weight: lighter;
			background-image: linear-gradient(0deg,#398bff,#3083ff);
			width: 100px;
			height: 45px;
			margin: 10px 0 8px;
			font-size: 23px;
			
		}
		img{
		width: 45px;
		height: 40px;
		}
		.settlement {
			display: flex;
			justify-content: space-between;
			align-items: center;
		}
	
	</style>
</template>

<script>
	
			<div class="settlement">
				<p>总价￥：{{totalPrice}}</p >
			<button class="submit" type="button" @click="totalEnd1()" >结算</button>
			</div>
			
			<div class="end" v-if="show">
				<p>商品数量为：{{totalEnd1}},需要支付的总价为：{{totalPrice}}</p>

	
</script>

<style>
	<script type="text/javascript">
		var app=new Vue({
			el:'#app',
			data:{
				goodsList:[{
					id:1,
					name:'iPhone',
					price:6000,
					count:1,
					imageUrl:"img/p1.jpg"
				
				},
				{
					id:2,
					name:'iPhoneX',
					price:7000,
					count:1,
					imageUrl:'img/p2.jpg'
				},
				{
					id:3,
					name:'iPhone xs Max',
					price:8000,
					count:1,
					imageUrl:'img/p3.jpg',
					
				
				
			}}
	</script>
</style>

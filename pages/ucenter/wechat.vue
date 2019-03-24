<template>
	<view class="content">
		<view class="title">
			<view class="title-left">
				<text>微信</text>
			</view>
			<view class="title-right">
				<image src="../../static/sousuo.png"></image>
				<image src="../../static/plus.png"></image>
			</view>
		</view>
		<view class="container">
			<view class="item">
				<view class="left">
					<image src="../../static/feng.jpg" alt="">
				</view>
				<view class="right">
					<view class="container">
						<text class="name">莫以有</text>
						<text class="info">陪你看烟花灿烂</text>
					</view>
					<view class="time">11:03</view>
				</view>
			</view>
			<view class="item">
				<view class="left">
					<image src="../../static/feng.jpg" alt="">
				</view>
				<view class="right">
					<view class="container">
						<text class="name">莫以有</text>
						<text class="info">陪你看烟花灿烂</text>
					</view>
					<view class="time">11:03</view>
				</view>
			</view>
			<view class="item">
				<view class="left">
					<image src="../../static/feng.jpg" alt="">
				</view>
				<view class="right">
					<view class="container">
						<text class="name">莫以有</text>
						<text class="info">陪你看烟花灿烂</text>
					</view>
					<view class="time">11:03</view>
				</view>
			</view>
			<view class="item">
				<view class="left">
					<image src="../../static/feng.jpg" alt="">
				</view>
				<view class="right">
					<view class="container">
						<text class="name">莫以有</text>
						<text class="info">陪你看烟花灿烂</text>
					</view>
					<view class="time">11:03</view>
				</view>
			</view>
		</view>
	</view>
</template>
<script>
	export default {
		data() {

		}
	}
</script>

<style>
	.content {
		height: 100%;
	}
	.title {
		display:flex;
		justify-content: space-between;
	}
	.title-left text {
		margin-top: 30px;
		height: 40px;
		width: 40px;
		font-size: 50px;
	}
	.title-right image {
		margin-top: 30px;
		width: 40px;
		height: 40px;
	}
	.container {
		margin-top: 10px;
		justify-content: space-between;
		
	}
	.card {
		width: 100%;
	}
	.left image {
		margin-top: 10px;
		margin-left: 30upx;
		width: 60px;
		height: 60px;
		border-radius: 10px;
	}
	.item {
		display: flex;
		margin-top: 30px;
		justify-content: space-between;
		width: 100%;
		margin-top: 20px;
	}
	.item .right {
		display: flex;
		width: 100%;
		margin-down: 15px;
		border-bottom: 1px solid #eee;
		height: 10px;
		justify-content: space-between;
	}
	.name {
		margin-left: 3px;
		margin-top: 16px;
		font-size: 15px;
		font-family: "楷书";
	}
	.info {	
		color: #AAA;
	}
</style>

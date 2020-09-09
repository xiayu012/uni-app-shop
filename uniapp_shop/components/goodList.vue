<template>
	<view class="goods_list">
		<view class="good_item">
			<image src="http://demo.dtcms.net/upload/201504/20/thumb_201504200046589514.jpg"></image>
			<view class="price">
				<text>￥2100</text>
				<text>￥2400</text>
			</view>
			<view class="goods_name">华为荣耀</view>
		</view>
		<view class="good_item">
			<image src="http://demo.dtcms.net/upload/201504/20/thumb_201504200046589514.jpg"></image>
			<view class="price">
				<text>￥2100</text>
				<text>￥2400</text>
			</view>
			<view class="goods_name">华为荣耀</view>
		</view>
		<view class="good_item">
			<image src="http://demo.dtcms.net/upload/201504/20/thumb_201504200046589514.jpg"></image>
			<view class="price">
				<text>￥2100</text>
				<text>￥2400</text>
			</view>
			<view class="goods_name">华为荣耀</view>
		</view>
	</view>
</template>

<script>
</script>

<style lang="scss">
	.goods_list {
		padding: 0 15rpx;
		display: flex;
		justify-content: space-between;
		flex-wrap: wrap;
		.good_item{
			overflow: hidden;
			background: #fff;
			box-sizing: border-box;
			padding: 15rpx;
			width: 355rpx;
			margin: 10rpx 0;
			image{
				width: 80%;
				height: 150px;
				display: block;
				margin: auto;
			}
			.price{
				color: $shop-color;
				font-size: 36rpx;
				text:nth-child(2){
					color: #ccc;
					font-size: 28rpx;
					text-decoration: line-through;
					margin-left: 15rpx;
				}
			}
			.goods_name{
				margin-top: 10rpx;
				font-size: 33rpx;
				line-height: 35rpx;
			}
		}
	}
</style>

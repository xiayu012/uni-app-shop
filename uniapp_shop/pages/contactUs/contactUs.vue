<template>
	<view class="contact">
		<image class="img" src="http://www.itcast.cn/2018czydz/images/gywmban.jpg"></image>
		<view class="info">
			<view>联系电话：123123123</view>
			<view>联系地址：浙江省上海市东方明珠大厦</view>
		</view>
		<map class="map" :longitude="longitude" :latitude="latitude"></map>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				longitude:121.49491,
				latitude:31.24169
			}
		},
		methods: {
			
		}
	}
</script>

<style lang="scss">
	.contact{
		.img{
			width: 750rpx;
			height: 320rpx;
		}
		.info{
			padding: 10rpx 20rpx;
			font-size: 30rpx;
			view{
				line-height: 80rpx;
				border-bottom: 1px solid #eee;
			}
		}
		.map{
			width: 750rpx;
			height: 750rpx;
		}
	}
</style>

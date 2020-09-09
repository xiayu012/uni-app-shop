<template>
	<view class="home">
		<swiper indicator-dots circular>
			<swiper-item>
				<image src="http://m.itheima.com/images/slidead/mobile/20191210154717750-410.jpg"></image>
			</swiper-item>
			<swiper-item>
				<image src="http://m.itheima.com/images/slidead/mobile/20191210154717750-410.jpg"></image>
			</swiper-item>
		</swiper>
		<view class="nav">
			<view class="nav_item" @click="navItemClick1">
				<svg t="1599019002791" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="6625"
				 width="200" height="200">
					<path d="M898.133333 341.333333c0-10.666667-10.666667-21.333333-21.333333-21.333333h-128v-8.533333C746.666667 185.6 646.4 85.333333 520.533333 85.333333h-17.066666C379.733333 85.333333 277.333333 185.6 277.333333 311.466667v8.533333H149.333333c-10.666667 0-21.333333 8.533333-21.333333 21.333333l-17.066667 518.4v2.133334c4.266667 55.466667 51.2 98.133333 106.666667 98.133333h595.2c55.466667 0 102.4-42.666667 106.666667-98.133333v-2.133334l-21.333334-518.4zM320 311.466667C320 209.066667 403.2 128 503.466667 128h17.066666c100.266667 0 183.466667 83.2 183.466667 183.466667v8.533333H320v-8.533333zM298.666667 554.666667c-23.466667 0-42.666667-19.2-42.666667-42.666667 0-14.933333 8.533333-29.866667 21.333333-36.266667V384c0-12.8 8.533333-21.333333 21.333334-21.333333s21.333333 8.533333 21.333333 21.333333v91.733333c12.8 6.4 21.333333 21.333333 21.333333 36.266667 0 23.466667-19.2 42.666667-42.666666 42.666667z m426.666666 0c-23.466667 0-42.666667-19.2-42.666666-42.666667 0-14.933333 8.533333-29.866667 21.333333-36.266667V384c0-12.8 8.533333-21.333333 21.333333-21.333333s21.333333 8.533333 21.333334 21.333333v91.733333c12.8 6.4 21.333333 21.333333 21.333333 36.266667 0 23.466667-19.2 42.666667-42.666667 42.666667z"
					 fill="#ffffff" p-id="6626"></path>
				</svg>
				<view>xiayu商城</view>
			</view>
			<view class="nav_item" @click="navItemClick2">
				<svg t="1599027452067" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="6818"
				 width="200" height="200">
					<path d="M512 67.168c-247.04 0-448 172.256-448 384 0 116.512 63.04 226.048 174.048 301.408l84.16 52.032c-3.68 23.552-18.752 74.496-33.44 115.936-4.256 12.064-0.928 25.504 8.448 34.176 6.016 5.568 13.824 8.512 21.728 8.512 4.416 0 8.832-0.896 13.024-2.752 36.416-16.224 147.456-68.96 187.584-125.376C763.136 831.616 960 660.704 960 451.168 960 239.424 759.04 67.168 512 67.168zM580.224 543.968 384.96 543.968c-17.664 0-32-14.336-32-32s14.336-32 32-32l195.264 0c17.696 0 32 14.336 32 32S597.92 543.968 580.224 543.968zM640.928 415.968 384.96 415.968c-17.664 0-32-14.336-32-32s14.336-32 32-32l255.968 0c17.696 0 32 14.336 32 32S658.624 415.968 640.928 415.968z"
					 p-id="6819" fill="#ffffff"></path>
				</svg>
				<view>联系我们</view>
			</view>
			<view class="nav_item" @click="navItemClick3">
				<svg t="1599028136569" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="7594"
				 width="200" height="200">
					<path d="M298.005333 450.090667c-47.061333 0-85.333333-38.272-85.333333-85.333333s38.272-85.333333 85.333333-85.333333 85.333333 38.272 85.333333 85.333333S345.045333 450.090667 298.005333 450.090667zM298.005333 322.090667c-23.530667 0-42.666667 19.136-42.666667 42.666667s19.136 42.666667 42.666667 42.666667 42.666667-19.136 42.666667-42.666667S321.536 322.090667 298.005333 322.090667z"
					 p-id="7595" fill="#ffffff"></path>
					<path d="M191.317333 855.573333c-60.053333 0-106.645333-56.192-106.645333-104.512L84.672 279.317333c0-93.738667 51.264-106.645333 106.645333-106.645333l640.128 0c58.816 0 106.645333 47.850667 106.645333 106.645333l0 467.498667c0 58.816-47.829333 106.645333-106.645333 106.645333l-640.042667 2.133333C191.36 855.573333 191.338667 855.573333 191.317333 855.573333zM191.317333 215.338667c-42.048 0-63.978667 2.837333-63.978667 63.978667l0 471.744c0 27.84 29.525333 61.845333 63.978667 61.845333l640.064-2.133333c35.328 0 64.042667-28.714667 64.042667-63.978667L895.424 279.317333c0-35.285333-28.714667-63.978667-63.978667-63.978667L191.317333 215.338667z"
					 p-id="7596" fill="#ffffff"></path>
					<path d="M214.869333 768.96c-2.304 0-4.650667-0.384-6.954667-1.173333-11.136-3.84-17.045333-15.957333-13.226667-27.114667 2.624-7.616 65.258667-186.474667 181.013333-184.021333 34.602667 0.874667 63.893333 11.114667 92.224 20.992 35.456 12.394667 68.992 24.128 112.042667 17.216 28.245333-4.522667 40.341333-33.792 57.728-81.173333 23.232-63.274667 55.04-149.909333 173.461333-149.909333 11.797333 0 21.333333 9.557333 21.333333 21.333333s-9.536 21.333333-21.333333 21.333333c-88.618667 0-110.378667 59.221333-133.397333 121.941333-18.026667 49.130667-36.672 99.904-91.050667 108.608-53.781333 8.597333-95.765333-6.101333-132.864-19.050667-26.389333-9.237333-51.328-17.941333-79.232-18.624-0.533333-0.021333-1.066667-0.021333-1.621333-0.021333-69.162667 0-123.008 111.808-138.005333 155.264C232 763.392 223.722667 768.96 214.869333 768.96z"
					 p-id="7597" fill="#ffffff"></path>
				</svg>
				<view>社区图片</view>
			</view>
			<view class="nav_item" @click="navItemClick4">
				<svg t="1599028206493" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="7789"
				 width="200" height="200">
					<path d="M512 64C265.6 64 64 265.6 64 512s201.6 448 448 448 448-201.6 448-448S758.4 64 512 64zM691.2 544l-256 156.8C428.8 704 422.4 704 416 704c-6.4 0-9.6 0-16-3.2C390.4 694.4 384 684.8 384 672L384 352c0-12.8 6.4-22.4 16-28.8 9.6-6.4 22.4-6.4 32 0l256 166.4c9.6 6.4 16 16 16 28.8C704 528 700.8 540.8 691.2 544z"
					 p-id="7790" fill="#ffffff"></path>
				</svg>
				<view>学习视频</view>
			</view>
		</view>
		<!-- 推荐商品 -->
		<view class="hot_goods">
			<view class="tuijianshangpin">推荐商品</view>
			<view class="goods_list">
				<view class="good_item" @click="toGoodMessage">
					<image src="http://demo.dtcms.net/upload/201504/20/thumb_201504200046589514.jpg"></image>
					<view class="price">
						<text>￥2100</text>
						<text>￥2400</text>
					</view>
					<view class="goods_name">华为荣耀</view>
				</view>
				<view class="good_item" @click="toGoodMessage">
					<image src="http://demo.dtcms.net/upload/201504/20/thumb_201504200046589514.jpg"></image>
					<view class="price">
						<text>￥2100</text>
						<text>￥2400</text>
					</view>
					<view class="goods_name">华为荣耀</view>
				</view>
				<view class="good_item" @click="toGoodMessage">
					<image src="http://demo.dtcms.net/upload/201504/20/thumb_201504200046589514.jpg"></image>
					<view class="price">
						<text>￥2100</text>
						<text>￥2400</text>
					</view>
					<view class="goods_name">华为荣耀</view>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				swipers: []
			}
		},
		onLoad() {
			
		},
		methods: {
			navItemClick1() {
				uni.navigateTo({
					url: '/pages/goods/goods'
				})
			},
			navItemClick2() {
				uni.navigateTo({
					url: '/pages/contactUs/contactUs'
				})
			},
			navItemClick3() {
				uni.navigateTo({
					url: '/pages/goods/goods'
				})
			},
			navItemClick4() {
				uni.navigateTo({
					url: '/pages/goods/goods'
				})
			},
			toGoodMessage() {
				uni.navigateTo({
					url: '/pages/goodMessage/goodMessage'
				})
			}
		}
	}
</script>

<style lang="scss">
	.home {
		swiper {
			width: 750rpx;
			height: 380rpx;

			image {
				height: 100%;
				width: 100%;
			}
		}

		.nav {
			display: flex;

			.nav_item {
				font-size: 30rpx;
				text-align: center;
				width: 25%;

				.icon {
					width: 120rpx;
					height: 120rpx;
					background: #b50e03;
					border-radius: 60rpx;
					margin: 10px auto;
				}
			}
		}

		.hot_goods {
			background: #C0C0C0;
			overflow: hidden;
			margin-top: 30rpx;

			.tuijianshangpin {
				height: 50px;
				line-height: 50px;
				color: $shop-color;
				text-align: center;
				letter-spacing: 20px;
				background: #FFFFFF;
				margin: 7rpx 0;
			}
		}

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
	}
</style>

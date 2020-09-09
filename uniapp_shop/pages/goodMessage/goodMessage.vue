<template>
	<view class="goodMessage">
		<image src="http://demo.dtcms.net/upload/201504/20/thumb_201504200046589514.jpg"></image>
		<uni-goods-nav class="goodMessageNav" :fill="true"  :options="options" :buttonGroup="buttonGroup"  @click="onClick" @buttonClick="buttonClick" />
	</view>
</template>

<script>
	import uniGoodsNav from '@/components/uni-goods-nav/uni-goods-nav.vue'
	export default {
		data() {
			return {
				options: [{
				            icon: 'headphones',
				            text: '客服'
				        }, {
				            icon: 'shop',
				            text: '店铺',
				            info: 2,
				            infoBackgroundColor:'#007aff',
				            infoColor:"red"
				        }, {
				            icon: 'cart',
				            text: '购物车',
				            info: 2
				        }],
				        buttonGroup: [{
				          text: '加入购物车',
				          backgroundColor: '#ff0000',
				          color: '#fff'
				        },
				        {
				          text: '立即购买',
				          backgroundColor: '#ffa200',
				          color: '#fff'
				        }
				        ]
			}
		},
		methods: {
			onClick (e) {
			        uni.showToast({
			          title: `点击${e.content.text}`,
			          icon: 'none'
			        })
			      },
			      buttonClick (e) {
			        console.log(e)
			        this.options[2].info++
			      }
		},
		components: {uniGoodsNav}
	}
</script>

<style lang="scss">
	.goodMessage{
		image {
			width: 750rpx;
			height: 750rpx;
		}
		.goodMessageNav{
			position: fixed;
			bottom: 0;
			width: 100%;
		}
	}
	
</style>

<template>
	<view class="goodslist">
		<goods-list></goods-list>
		<view class="isOver">-----已经到底辽------</view>
	</view>
</template>

<script>
	import goodList from '../../components/goodList.vue'
	export default {
		data() {
			return {
				
			}
		},
		components: {"goods-list":goodList},
		methods: {
			
		},
		onPullDownRefresh() {
			setTimeout(function(){uni.stopPullDownRefresh()},500)
		}
	}
</script>

<style lang="scss">
	.goodslist {
		background: #eee;
	}
	.isOver {
		width: 100%;
		height: 50px;
		line-height: 50px;
		text-align: center;
		font-size: 28rpx;
	}
</style>

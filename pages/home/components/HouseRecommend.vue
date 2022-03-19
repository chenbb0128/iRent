<template>
	<view class="recommend-root">
		<view class="title">房源推荐</view>
		<sizer></sizer>
		<house-item></house-item>
		<house-item></house-item>
		<house-item></house-item>
	</view>
</template>

<script>
	import Sizer from './HouseRecommend/Sizer.vue'
	import HouseItem from './HouseRecommend/HouseItem.vue'
	export default {
		components: { Sizer, HouseItem }
	}
</script>

<style lang="less" scoped>
	.recommend-root {
		padding: 10rpx 32rpx 0;
		.title {
			font-size: 40rpx;
			font-weight: 500;
		}
	}
</style>

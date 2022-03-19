<template>
	<view class="swiper-root">
		<u-swiper
			:list="list"
			height="360rpx"
			indicator
			indicatorMode="dot"
		></u-swiper>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				cardCur: 0,
				list: [
					'https://s2.loli.net/2022/03/18/t241vluryR8eBhK.png',
					'https://s2.loli.net/2022/03/18/t241vluryR8eBhK.png',
					'https://s2.loli.net/2022/03/18/t241vluryR8eBhK.png',
				]
			};
		},
	}
</script>

<style lang="less" scoped>
	.swiper-root {
		padding: 50rpx 32rpx;
	}
</style>

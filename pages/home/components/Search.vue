<template>
	<view class="search-root">
		<view class="region">滨江</view>
		<view class="vertical">|</view>
		<view class="search-input">
			<input placeholder="寻找您的小窝~">
		</view>
	</view>
</template>

<script>
</script>

<style lang="less" scoped>
	.search-root {
		background-color: #f8f8f8;
		border-radius: 40rpx;
		display: flex;
		padding: 24rpx;
		align-items: center;
		margin: 60rpx 32rpx 0;
		.region {
			font-size: 32rpx;
			font-weight: 500;
			width: 80rpx;
		}
		.vertical {
			margin: 0 24rpx;
			color: #cccccc;
		}
		.search-input {
			width: 100%;
		}
	}
</style>

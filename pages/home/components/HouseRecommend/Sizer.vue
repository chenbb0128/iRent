<template>
	<view class="sizer-root">
		<view class="sizer-item selected">推荐<view class="down"></view></view>
		<view class="sizer-item">区域<view class="down"></view></view>
		<view class="sizer-item">租金<view class="down"></view></view>
	</view>
</template>

<script>
</script>

<style lang="less" scoped>
	.sizer-root {
		display: flex;
		font-size: 32rpx;
		justify-content: space-between;
		margin: 40rpx 10rpx 10rpx;
		padding-bottom: 20rpx;
		.sizer-item {
			display: flex;
			align-items: center;
			color: #b3b3b3;
			.down {
				border-right: solid #b3b3b3 1px;
				border-bottom: solid #b3b3b3 1px;
				width: 13rpx;
				height: 13rpx;
				transform: rotate(45deg);
				-webkit-transform: rotate(45deg);
				margin-left: 14rpx;
			}
		}
		.selected {
			color: #000000;
			font-weight: 500;
		}

	}
</style>

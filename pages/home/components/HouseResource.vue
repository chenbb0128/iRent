<template>
	<view class="resource-root">
		<view class="title">房源中心</view>
		<view class="card-list">
			<view class="card-item">
				<view class="card-item-content">
					<view class="card-item-title">最新房源</view>
					<view class="card-item-desc">实时更新最新发布房源</view>
				</view>
				<view class="card-item-icon">
					<image src="../../../static/home.png"></image>
				</view>
			</view>
			<view class="card-item">
				<view class="card-item-content">
					<view class="card-item-title">最新房源</view>
					<view class="card-item-desc">实时更新最新发布房源</view>
				</view>
				<view class="card-item-icon">
					<image src="../../../static/home.png"></image>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {

	}
</script>

<style lang="less" scoped>
	.resource-root {
		.title {
			font-size: 40rpx;
			font-weight: 500;
			padding: 0 32rpx 36rpx;
		}
		.card-list {
			background: #f8f8f8;
			padding: 20rpx 32rpx 70rpx;
			display: flex;
			.card-item {
				width: 100%;
				border-radius: 20rpx;
				padding: 32rpx;
				display: flex;
				background-color: #ffffff;
				color: #666666;
				box-shadow: 3px 3px 4px rgb(189,189 ,189);
				.card-item-content {
					margin-right: 20rpx;
					.card-item-title {
						font-weight: 500;
					}
					.card-item-desc {
						font-size: 24rpx;
						color: #cacac8;
						margin-top: 10rpx;
					}
				}
				.card-item-icon {
					display: flex;
					justify-content: center;
					align-items: center;
					image {
						width: 60rpx;
						height: 60rpx;
					}
				}
			}
			.card-item:first-child {
				margin-right: 20rpx;
			}
		}
	}
</style>

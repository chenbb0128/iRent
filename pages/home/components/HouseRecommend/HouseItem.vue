<template>
	<view class="house-root">
		<view class="house-image">
			<image src="../../../../static/home-demo.png" ></image>
		</view>
		<view class="content">
			<view class="title">整租房子一室一厅</view>
			<view class="desc">房子的简介</view>
			<view class="tag-list">
				<view class="tag-item">实拍tag</view>
				<view class="tag-item">实拍tag</view>
				<view class="tag-item">实拍tag</view>
			</view>
			<view class="price">
				<view class="num">1600</view>
				<view class="unit">元/月</view>
			</view>
		</view>
	</view>
</template>

<script>
</script>

<style lang="less" scoped>
	.house-root {
		border-top: 1px solid #e7e6e6;
		padding: 30rpx 0;
		display: flex;
		.house-image {
			margin-right: 32rpx;
			display: flex;
			align-items: center;
			image {
				width: 240rpx;
				height: 180rpx;
			}
		}
		.content {
			display: flex;
			flex-direction: column;
			.title {
				font-size: 32rpx;
				font-weight: 500;
			}
			.desc {
				font-size: 28rpx;
				color: #a4a4a2;
				margin-top: 5rpx;
			}
			.tag-list {
				display: flex;
				margin-top: 5rpx;
				font-size: 26rpx;
				.tag-item {
					margin-right: 8rpx;
					background-color: #f2f6fe;
					color:#a4a4a2;
					padding: 4rpx 8rpx;
					border-radius: 8rpx;
				}
			}
			.price {
				display: flex;
				margin-top: 5rpx;
				color: #f8670d;
				align-items: flex-end;
				.num {
					font-weight: 500;
					font-size: 32rpx;
					margin-right: 4rpx;
				}
				.unit {
					font-size: 22rpx;
				}
			}
		}
	}
</style>

<template>
	<view class="home-container">
		<view class="title">蚂蚁房源</view>
		<search></search>
		<swiper-container></swiper-container>
		<house-resource></house-resource>
		<house-recommend></house-recommend>
		<tabbar></tabbar>
	</view>
</template>

<script>
	import Search from './components/Search.vue'
	import SwiperContainer from './components/SwiperContainer.vue'
	import HouseResource from './components/HouseResource.vue'
	import HouseRecommend from './components/HouseRecommend.vue'
	import Tabbar from './components/Tabbar.vue'
	export default {
		components: { Search, SwiperContainer, HouseResource, HouseRecommend, Tabbar },
		data() {
			return {
				test: 0,
				cardCur: 0,
				swiperList: [{
					id: 0,
					type: 'image',
					url: 'https://ossweb-img.qq.com/images/lol/web201310/skin/big84000.jpg'
				}, {
					id: 1,
					type: 'image',
					url: 'https://ossweb-img.qq.com/images/lol/web201310/skin/big37006.jpg',
				}, {
					id: 2,
					type: 'image',
					url: 'https://ossweb-img.qq.com/images/lol/web201310/skin/big39000.jpg'
				}, {
					id: 3,
					type: 'image',
					url: 'https://ossweb-img.qq.com/images/lol/web201310/skin/big10001.jpg'
				}, {
					id: 4,
					type: 'image',
					url: 'https://ossweb-img.qq.com/images/lol/web201310/skin/big25011.jpg'
				}, {
					id: 5,
					type: 'image',
					url: 'https://ossweb-img.qq.com/images/lol/web201310/skin/big21016.jpg'
				}, {
					id: 6,
					type: 'image',
					url: 'https://ossweb-img.qq.com/images/lol/web201310/skin/big99008.jpg'
				}],
				dotStyle: false,
				towerStart: 0,
				direction: ''
			};
		},
		methods: {

		}
	}
</script>

<style scoped lang="scss">
	@import "uview-ui/index.scss";
	.home-container {
		height: 100%;
		width: 100%;
		background-color: #FFFFFF;
		.title {
			padding: 18rpx 32rpx;
			font-size: 50rpx;
			font-weight: 500;
		}
	}
</style>

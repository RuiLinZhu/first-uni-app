<template>
	<view class="content">
		<view class="firendscircle">
			<navigator url="friend" hover-class="navigator-hover">
				<button type="default" class="btn">
					<image src="../../static/firendcircle.png" mode="circle"></image>
					朋友圈
				</button>
			</navigator>
		</view>

		<view class="scanning">
			<navigator url="scan" hover-class="navigator-hover">
				<button type="default" class="btn">
					<image src="../../static/scanning.png" mode="scanning"></image>扫一扫
				</button>
			</navigator>
			<navigator url="shake" hover-class="navigator-hover">
				<button type="default" class="btn">
					<image src="../../static/shaking.png" mode="shaking"></image>摇一摇
				</button>
			</navigator>
		</view>

		<view class="nearly">
			<navigator url="near" hover-class="navigator-hover">
				<button type="default" class="btn">
					<image src="../../static/nearly.png" mode="nearly"></image>附近的人
				</button>
			</navigator>
		</view>
		<navigator url="shop" hover-class="navigator-hover">
			<view class="leisure">
				<button type="default" class="btn">
					<image src="../../static/shopping.png" mode="shopping"></image>购物
				</button>
		</navigator>
		<navigator url="game" hover-class="navigator-hover">
			<button type="default" class="btn">
				<image src="../../static/gaming.png" mode="gaming"></image>游戏
			</button>
		</navigator>
	</view>
	<navigator url="program" hover-class="navigator-hover">
		<view class="programming">
			<button type="default" class="btn">
				<image src="../../static/programming.png" mode="programming"></image>小程序
			</button>
	</navigator>
	</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {

			}
		}
	}
</script>

<style>
	.content {
		border: none;
	}

	.scanning{
		margin-top: 20upx;
	}
	.nearly{
		margin-top: 20upx;
	}
	.leisure{
		margin-top: 15upx;
	}
	.programming{
		margin-top: 20upx;
	}
	.btn {
		text-align: left;
	}
	.content image {
		width: 60upx;
		height: 60upx;
		margin-right: 10upx;

	}
</style>

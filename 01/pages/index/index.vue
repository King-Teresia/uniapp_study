<template>
	<view>
		<!-- swiper -->
		<swiper class="swiper" circular autoplay interval="3000" duration="500" indicator-dots>
			<swiper-item>
				<view class="swiper-item ">
					<image class="realPic" src="../../../../../前端开发/网页开发/好玩的素材/yuanqi3.png" mode="widthFix">
					</image>
				</view>
			</swiper-item>
			<swiper-item>
				<view class="swiper-item ">
					<image class="realPic" src="../../static/yuanqi4.png" mode="widthFix">
					</image>
				</view>
			</swiper-item>
			<swiper-item>
				<view class="swiper-item ">
					<image class="realPic" src="../../static/yuanqi2.png" mode="widthFix">
					</image>
				</view>
			</swiper-item>
			<swiper-item>
				<image class="realPic"
					src="https://fgo.wiki/images/7/72/7%E5%91%A8%E5%B9%B4%E5%80%92%E8%AE%A1%E6%97%B6.png"
					mode="widthFix">
				</image>
			</swiper-item>
		</swiper>
		<navigator url="../tpindex/tpindex">look at me</navigator>
		<button size="mini" disabled> 点击我</button>
		<view class="myPic">
			<image class="realPic" src="https://fgo.wiki/images/f/f4/%E5%B0%9A%E5%9C%A8%E6%97%85%E9%80%94%E4%B8%AD.png"
				mode="aspectFill">
			</image>
		</view>


	</view>
</template>

<script>
	export default {
		data() {
			return {
				message: "嗨嗨嗨",
			}
		},

		methods: {

		}
	}
</script>

<style lang="scss">
	.swiper {
		height: 300rpx;
		border: 1rpx solid orange;
		box-sizing: border-box;
		text-align: center;

		.swiper-item {
			display: inline-block;
			width: 100%;
			height: 300rpx;
			line-height: 300rpx;
			text-align: center;
			background-color: skyblue;
		}

		.realPic {
			width: 100%;
			// height: 100%;
		}
	}

	.myPic {
		width: 300rpx;
		height: 300rpx;
		border: 5px solid red;

		.realPic {
			width: 100%;
			height: 100%;
		}
	}
</style>
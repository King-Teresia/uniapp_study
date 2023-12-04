<template>
	<view class="content">
		<image class="logo" src="/static/logo.png"></image>
		<view class="text-area">
			<text class="title">{{title}}</text>
		</view>

		<icon type="success" size="26" color="orange" />
		<text selectable="true">沃德法</text>

		<view>
			<scroll-view class="dad" scroll-x scroll-y>
				let me see
				<view class="son">
					show me
				</view>
				<view class="son">
					show me
				</view>
				<view class="son">
					show me
				</view>
				<view class="son">
					show me
				</view>
			</scroll-view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello there my friend'
			}
		}
	}
</script>

<style lang="scss">
	.content {
		color: aqua;

		.text-area {
			color: red;
		}

		.logo {
			width: 200rpx; //750rpx 即 全部沾满屏幕
		}

		.dad {

			width: 500px;
			height: 200px;
			border: 1px solid red;
			white-space: nowrap;



			.son {
				display: inline-block;
				width: 300px;
				height: 300px;
				border: 3px solid black;
				margin-right: 10rpx;
			}
		}

	}
</style>
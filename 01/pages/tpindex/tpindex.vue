<template>
	<view>
		<!-- 之前的00 -->
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
		<!--  -->
		<navigator url="../index/index" open-type="navigate">clike me</navigator>
		<navigator url="../index/index" open-type="navigate">
			<image src="../../static/logo.png" mode=""></image>
		</navigator>

	</view>
</template>

<script>

</script>

<style lang="scss">
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
</style>
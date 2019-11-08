<template>
	<view class="content">
		<view class="main">
			<view class="time">
				<text>{{time}}</text>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				time: '2019年09月21日'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.main {
		text-align: center;
		height: 935rpx;
		width: 750rpx;
		background-color: #32d6b6;
		color: #ffffff;
		overflow: hidden;
		display: flex;
		flex-direction: column;
	}
	.time {
		margin-top: 10rpx;
		font-size: 22rpx;
		width: 246rpx;
		height: 40rpx;
		align-self: center;
		border-radius: 500rpx;
		background-color: #35d0b2;
		display: flex;
		justify-content: center;
		align-items: center;
	}

	.logo {
		height: 200upx;
		width: 200upx;
		margin-top: 200upx;
	}

	.title {
		font-size: 36upx;
		color: #8f8f94;
	}
</style>

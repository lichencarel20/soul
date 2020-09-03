<template>
	<view>
		<view class="header">
			<view class="image-content" style="background-color: #5c8983;);" >
								<view class="headerLine1">
									<view class="whichstar">
										<i class="iconfont">&#xe610;</i>
										<view> 来自思想家星球 </view>
									</view>
									<view class="coin">
										<i class="iconfont iconjinbi" ></i>
										<text>27</text>
									</view>
									<view class="addFriends">
										<i class="iconfont iconjiahaoyou" ></i>
										<text>加好友</text>
									</view>
									<view class="setting">
										设置
									</view>
								</view>
								<view class="headerLine2">
									<view class="headPortrait">
										
									</view>
								</view>
								<view class="headerLine3">
									<text>Dependent</text>
								</view>
								<view class="headerLine4">
									<text>101天，3个瞬间</text>
								</view>
								<view>
									<text>农民</text>
								</view>
								<view class="headerLine5">
									<view class="">
										超级星人
									</view>
									<view class="">
										礼物
									</view>
									<view class="">
										宠物
									</view>
									<view class="">
										夸夸墙
									</view>
								</view>
			</view>
			
			<view class="">
				1111
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			};
		},
		methods:{
			imageError:function(e){
				console.log(e)
			}
		}
	}
</script>

<style lang="scss">
	.image-content{
		width: 750rpx;
		height: 750rpx;
		color: #fefefe;
		.headerLine1{
			display: flex;
			padding-top: 30rpx;
			view{
				display: inline-block;
				height: 50rpx;
				font-size: 30rpx;
				line-height: 50rpx;
				border-radius: 15rpx;
			}
			.whichstar{
				margin-left: 20rpx;
				border: 3rpx solid #3e4750;
				
				i{
					font-size: 36rpx;
					color: #4cd8ee;
				}
			}
			.coin{
				margin-left: 100rpx;
				border: 3rpx solid #3b474b;
				i{
					display: inline-block;
					margin: 0 10rpx;
					font-size: 36rpx;
					color: #ecae13;
				}
			}
			.addFriends{
				border: 3rpx solid #3b474b;
				margin-left: 30rpx;
				margin-right: 30rpx;
				i{
					display: inline-block;
					margin: 0 10rpx;
					font-size: 36rpx;
				}
			}
			.setting{
				line-height:50rpx ;
				font-size: 34rpx;
			}
		}
	}
	
</style>

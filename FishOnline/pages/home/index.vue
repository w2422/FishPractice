<template>
	<view class="container">
		<view class="uni-margin-wrap">
			<swiper class="swiper" circular :indicator-dots="swiperOptions.indicatorDots" :autoplay="swiperOptions.autoplay" :interval="swiperOptions.interval"
				:duration="swiperOptions.duration">
				<swiper-item>
					<view class="swiper-item uni-bg-red">A</view>
				</swiper-item>
				<swiper-item>
					<view class="swiper-item uni-bg-green">B</view>
				</swiper-item>
				<swiper-item>
					<view class="swiper-item uni-bg-blue">C</view>
				</swiper-item>
			</swiper>
		</view>
	</view>
</template>

<script setup>
import { ref } from "vue"

const hello = new ref("Hello Wechat App")
var swiperOptions= new ref({
	indicatorDots:true,
	autoplay:true,
	interval:2000,
	duration:500,
})
</script>

<style>
	.container {
		padding: 20px;
		font-size: 14px;
		line-height: 24px;
	}
</style>

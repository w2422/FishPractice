<template>
	<view class="container">
		{{hello}}
	</view>
</template>

<script setup>
import { ref } from "vue"

const hello = new ref("Hello Wechat App")
</script>

<style>
	.container {
		padding: 20px;
		font-size: 14px;
		line-height: 24px;
	}
</style>

<template>
	<view class="content">
		<view :style="{height : `${statusBarHeight}px` }" ></view>
		<view>首页</view>
 </view>
</template>

<script>
	export default {
		data() {
			return {
				statusBarHeight : this.$statusBarHeight,

			}
		},
		components:{
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	
</style>


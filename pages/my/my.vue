<template>
	<view>
		<!-- 使用自定义的搜索组件 -->
		<my-search></my-search>
		
	</view>
</template>

<script>
	import badgeMin from "@/mixins/tabbar-badge.js"
	
	export default {
		mixins:[badgeMin],
	
		data() {
			return {
				
			};
		}
	}
</script>

<style lang="stylus">

</style>

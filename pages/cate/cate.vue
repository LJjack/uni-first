<template>
	<view >
		<template  v-for="(item,index) in [0,1,2,3,4,5]">
		<view class="logo-list" v-if="index != 0">
				<text>{{item}} index = {{index}}</text>
			</view>
		</template>
		
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			};
		}
	}
</script>

<style lang="stylus">

</style>

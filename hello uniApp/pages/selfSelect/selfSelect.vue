<template>
	<view class="charts-box">
	    <qiun-data-charts type="line" :chartData="chartData" />
	</view>
</template>

<script>
	export default {
		data() {
			return {
				chartData:{
				 categories:['2016','2017','2018','2019','2020','2021'],
				 series:[{
				  name:'目标值',
				  data:[35, 36, 31, 33, 13, 34]
				 },{
				  name:'完成量',
				  data:[18, 27, 21, 24, 6, 28]
				 }]
				}
			}
		},
		methods: {
			
		}
	}
</script>

<style>

</style>

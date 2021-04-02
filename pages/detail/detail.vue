<template>
	<view>详情页
		<text> 唱歌跳舞打篮球 </text>	
		<text selectable > 唱歌跳舞打篮球 </text>
		<view>
			<text> 唱歌跳舞打篮球 </text>	
			<text selectable space="ensp" > 唱歌     跳舞打篮球 </text>
		</view>
		<view>
			<text decode="false"> &amp; </text>	
		</view>
		
		<view class="box" hover-class="box-active">
			我是一个大盒子
		</view>
	</view>
</template>

<script> 
</script>

<style>
	
	.box{
		width: 100px;
		height: 100px;
		background: green;
	}
	
	.box-active{
		width: 100px;
		height: 100px;
		background: red;
	}
</style>

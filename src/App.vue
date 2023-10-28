<script setup>
	import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
	<div class="grid-container">
		<div class="grid-item block1">
			<!-- <HelloWorld /> -->
			<div class="sub-grid1">
				<div class="sub-grid-item1 sub-block1">
					属性筛选
				</div>
				<div class="sub-grid-item1 sub-block2">
					属性筛选
				</div>
				<div class="sub-grid-item1 sub-block3">
					属性筛选
				</div>
				<div class="sub-grid-item1 sub-block4">
					属性筛选
				</div>
				<div class="sub-grid-item1 sub-block5">
					属性筛选
				</div>
				<div class="sub-grid-item1 sub-block6">
					属性筛选
				</div>
			</div>
			<div class="sub-grid2">
				<div class="sub-grid-item2 sub-block1">
					时间段筛选
				</div>
				<div class="sub-grid-item2 sub-block2">
					子序列筛选
				</div>
				<div class="sub-grid-item2 sub-block3">
					子序列筛选
				</div>
				<div class="sub-grid-item2 sub-block4">
					其他控件
				</div>
			</div>
			<div class="sub-grid3">
				筛选后可用的数据块
			</div>
		</div>
		<div class="grid-item block2">
			运算区
		</div>
		<div class="grid-item block3">
			文字详细信息
		</div>
		<div class="grid-item block4">
			运算结果展示区
		</div>
		<div class="grid-item block5">
			运算块
		</div>
	</div>
</template>

<style scoped>

</style>
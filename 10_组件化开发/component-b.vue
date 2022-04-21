<template>
	<div>
		<h2>{{ title }}</h2>
		<p>{{ desc }}</p>
		<button @click="increate">点击按钮：{{ counter }}</button>
	</div>
</template>

<script>
	export default {
		data() {
			return {
				title: "我是标题",
				desc: "我是内容",
				counter: 0,
			};
		},
		methods: {
			increate() {
				return this.counter++;
			},
		},
	};
</script>

<style scoped>
</style>

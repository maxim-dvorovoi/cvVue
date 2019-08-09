<template>
	<div class="about" :onload="$parent.setLoading()">
		<h3>This is an about page</h3>
		<h2>About me</h2>
	</div>
</template>

<script>
	export default {
		name: 'about',
		methods: {

		},
		created() {
			this.$parent.setLoading();
		},
		mounted() {

		}
	}
</script>
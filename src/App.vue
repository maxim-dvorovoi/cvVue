<template>
	<div id="app">
		<div v-if="loading" id="loader" class="loader">
			<div class="dot-1"></div>
			<div class="dot-2"></div>
			<div class="dot-3"></div>
		</div>

		<div id="index" :class="loading ? 'main' : 'main-active'">
			<div id="nav">
				<router-link to="/">Home</router-link> |
				<router-link to="/about">About</router-link>
			</div>
			<router-view/>
		</div>
	</div>
</template>

<style>
	@import "assets/main.css";
</style>

<script>
	export default {
		data() {
			return {
				loading: true
			};
		},
		methods: {
			onLoadApp() {
				setTimeout(() => this.loading = false, 1000);
			},
		},
		mounted() {
			window.addEventListener('load', () => this.onLoadApp());
		}
	}
</script>
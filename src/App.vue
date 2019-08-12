<template>
	<div id="app">
		<div v-if="loading" id="loader" class="loader">
			<div class="dot-1"></div>
			<div class="dot-2"></div>
			<div class="dot-3"></div>
		</div>

		<div id="index" :class="loading ? 'main' : 'main-active'">
			<img src="./assets/me.jpeg" style="display: none">

			<div class="burger" id="burger" onclick="showHideHeader()">
				<span></span>
				<span></span>
				<span></span>
			</div>

			<div class="banner" id="banner">
				<div class="name-block">
					<h2>Hi, I'm</h2>
					<h1>
						Maxim
						<br>
						Dvorovoi
					</h1>
					<h2>Web developer</h2>
				</div>
			</div>

			<div class="container">
				<div class="header" id="header">
					<span>
						<i class="fas fa-address-card"></i>
						<router-link to="/">Resume</router-link>
					</span>
					<span>
						<i class="fas fa-folder-open"></i>
						<router-link to="/portfolio">Portfolio</router-link>
					</span>
					<span>
						<i class="fas fa-folder-open"></i>
						<router-link to="/contact">Contact</router-link>
					</span>
				</div>

				<div class="content" id="content">
					<router-view/>
				</div>
			</div>
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
			setLoading() {
				setTimeout(() => this.loading = false, 700);
			},
		},
		mounted() {
			window.onload = () => this.setLoading();
		}
	}
</script>
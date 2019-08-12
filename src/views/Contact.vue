<template>
	<div class="contact">
		<h3>Social media</h3>
		<div class="social">
			<a href="https://www.instagram.com/d_mas9" target="_blank" rel="noreferrer noorigin" class="instagram-btn">
				<i class="fab fa-instagram"></i>
				<span>instagram</span>
			</a>
			<a href="https://www.facebook.com/maxim.dvorovoy" target="_blank" rel="noreferrer noorigin" class="facebook-btn">
				<i class="fab fa-facebook-square"></i>
				<span>facebook</span>
			</a>
			<a href="https://www.linkedin.com/in/maxim-dvorovoi" target="_blank" rel="noreferrer noorigin" class="linkedin-btn">
				<i class="fab fa-linkedin"></i>
				<span>linkedin</span>
			</a>
			<a href="https://github.com/maxim-dvorovoi" target="_blank" rel="noreferrer noorigin" class="github-btn">
				<i class="fab fa-github-square"></i>
				<span>github</span>
			</a>
		</div>
	</div>
</template>

<script>
	export default {
		name: 'contact',
		methods: {

		},
		created() {
			this.$parent.setLoading();
		},
		mounted() {

		}
	}
</script>
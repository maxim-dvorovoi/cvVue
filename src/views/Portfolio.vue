<template>
	<div class="portfolio">
		<h3>Projects</h3>
		<div class="projects">
			<div>
				<a href="https://hand-made-bymaxim.000webhostapp.com/" target="_blank" rel="noreferrer noorigin">
					<img src="../assets/project1.png">
				</a>
				<h4>Hand - made</h4>
				<p>This project is created on Symfony 3,4. It was a thesis work on courses PHP Academy.</p>
			</div>
			<br>
			<br>
			<br>
			<br>
			<div>
				<a href="https://maxim-dvorovoi.github.io/dont-touch-the-blocks/" target="_blank" rel="noreferrer noorigin">
					<img src="../assets/project2.png">
				</a>
				<h4>Dont touch the blocks</h4>
				<p>This game is a simple variation Flappy Bird. I have used object-oriented programming and functional programming, to learn how it works.</p>
			</div>
		</div>
	</div>
</template>

<script>
	export default {
		name: 'portfolio',
		methods: {

		},
		created() {
			this.$parent.setLoading();
		},
		mounted() {

		}
	}
</script>
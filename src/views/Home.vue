<template>
	<div class="home">
		<h3>Profile</h3>
		<h2>I'm a Fullstack Web Developer from Kyiv, UA. I aim to make a functional applications with clean code.</h2>
		<h4>Worked with project teams to create user-friendly and appealing application interfaces and websites for users. Also worked with Vue.js framework and Highcharts as front-end developer. As a back-end developer, I have acted with PHP, MySQL, ElasticSearch, Nginx, Facebook API, Jira API and various Google API.</h4>
		<hr>
		<div class="info-list">
			<div>
				<span>Name : </span>
				Maxim Dvorovoi
			</div>
			<div>
				<span>Date of birth : </span>
				May 15, 1996
			</div>
			<div>
				<span>Address : </span>
				Kyiv, Ukraine
			</div>
			<div>
				<span>Phone : </span>
				+ 38 095 063 0 179
			</div>
			<div>
				<span>Skype : </span>
				maxwell3235
			</div>
			<div>
				<span>Interest : </span>
				full-time, freelance
			</div>
		</div>
		<div class="email">
			<a href="mailto:vmolo4nik@gmail.com">vmolo4nik@gmail.com</a>
		</div>
		<br>
		<h3>Skills</h3>
		<div class="skills-list">
			<div class="progress-label">
				<span>PHP - 2 </span>
				years experience
			</div>
			<div class="progress">
				<div class="progress-bar" style="width: 90%">
					<span>90%</span>
				</div>
			</div>

			<div class="progress-label">
				<span>JavaScript - 2 </span>
				years experience
			</div>
			<div class="progress">
				<div class="progress-bar" style="width: 90%">
					<span>90%</span>
				</div>
			</div>

			<div class="progress-label">
				<span>MySQL - 2 </span>
				years experience
			</div>
			<div class="progress">
				<div class="progress-bar" style="width: 85%">
					<span>85%</span>
				</div>
			</div>

			<div class="progress-label">
				<span>VueJS - 1 </span>
				years experience
			</div>
			<div class="progress">
				<div class="progress-bar" style="width: 80%">
					<span>80%</span>
				</div>
			</div>

			<div class="progress-label">
				<span>ElasticSearch - 1 </span>
				years experience
			</div>
			<div class="progress">
				<div class="progress-bar" style="width: 70%">
					<span>70%</span>
				</div>
			</div>

			<div class="progress-label">
				<span>Nginx - 1 </span>
				years experience
			</div>
			<div class="progress">
				<div class="progress-bar" style="width: 65%">
					<span>60%</span>
				</div>
			</div>
		</div>
		<br>
		<h3>Experience</h3>
		<div class="timeline experience">
			<div class="trophy sticky">
				<i class="fas fa-trophy"></i>
			</div>
			<div class="row">
				<div class="exp-holder">
					<div class="exp">
						<div class="hgroup">
							<h4>
								Full-Stack developer @
								<a href="https://semalt.com" target="_blank" rel="noreferrer noorigin">
									Semalt
								</a>
							</h4>
							<h5>Sep 2018 - <span class="current">Present</span></h5>
						</div>
						<p>Semalt is a team of creative, talented, proactive, and motivated experts, who have brought many successful IT projects to life. We have been honing our skills for ten years now, so we can say without a doubt that each of us is a true master of our craft. By our joint effort, we have created one of the most original and innovative web services that we proudly present to you now.</p>
					</div>

					<div class="exp">
						<div class="hgroup">
							<h4>
								Full-Stack developer @
								<a href="https://php-academy.kiev.ua" target="_blank" rel="noreferrer noorigin">
									PHP Academy
								</a>
							</h4>
							<h5>Jan 2018 - Sep 2018</h5>
						</div>
						<p>PHP Academy is the №1 web programming school in Ukraine. Provide courses with the documentary guarantee of the internship specified in the contract.</p>
					</div>
				</div>
			</div>
		</div>
		<br>
		<h3>Education</h3>
		<div class="timeline experience">
			<div class="award sticky">
				<i class="fas fa-award"></i>
			</div>
			<div class="row">
				<div class="exp-holder">
					<div class="exp">
						<div class="hgroup">
							<h4>
								Junior Web Developer @
								<a href="https://php-academy.kiev.ua" target="_blank" rel="noreferrer noorigin">
									PHP Academy
								</a>
							</h4>
							<h5>2017 - 2018</h5>
						</div>
						<p>PHP Academy is the №1 web programming school in Ukraine. Provide courses with the documentary guarantee of the internship specified in the contract.</p>
					</div>

					<div class="exp">
						<div class="hgroup">
							<h4>
								IT Specialist @
								<a href="http://foreign.dut.edu.ua" target="_blank" rel="noreferrer noorigin">
									State University of Telecommunications
								</a>
							</h4>
							<h5>2014 - 2018</h5>
						</div>
						<p>Learning in specialized classrooms and laboratories equipped with the latest devices from the leading companies HP, Alcatel-Lucent, D-Link, Huawei, ZTE, Ericsson, IBM, Watson Telecom. The State University of Telecommunications open academy CISCO, within which the Linux Professional Institute, the only certified in Ukraine Academy of Hewlett Packard, held courses in-depth study of technical English in areas of IT.</p>
					</div>

					<div class="exp">
						<div class="hgroup">
							<h4>
								Junior IT Specialist @
								<a href="https://sites.google.com/view/kkz" target="_blank" rel="noreferrer noorigin">
									Kiev College of Communication
								</a>
							</h4>
							<h5>2011 - 2014</h5>
						</div>
						<p>Was founded in 1921 by the International Committee of Education of Ukraine. For its 90 - year history, the college has trained more than 72,000 IT specialists and about 1,200 specialists of the foreign students department. Throughout its history the college has improved pedagogical skills of the teachers, introduced new technology training, accumulated education potential, improved the material and technical base.</p>
					</div>
				</div>
			</div>
		</div>
		<br>
	</div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
	name: 'home',
	components: {
		HelloWorld
	},
	methods: {

	},
	created() {
		this.$parent.setLoading();
	},
	mounted() {
		//this.$parent.setLoading();
	}
}
</script>

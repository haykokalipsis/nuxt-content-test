<template>
	<fragment>
		<MainSlider/>
		<AboutUs/>
		<Founders/>
<!--		<LatestCourses/>-->
		<Teachers/>
		<Testimonials/>

	</fragment>
</template>

<script>
	import AboutUs from '@/components/AboutUs';
	import MainSlider from '@/components/MainSlider';
	import Founders from '@/components/Founders';
	import Teachers from '@/components/Teachers';
	import LatestCourses from '@/components/LatestCourses';
	import Testimonials from '@/components/Testimonials';

	export default {
		name: 'home',
		layout: 'default',

		head() {
			return {
				titleTemplate: '',
				title: 'Славянская | Главная',
				link: [
					// {rel: 'stylesheet',  href: 'css/slick.css'}
				],
				//
				script: [
					// { src: 'js/slick.js', type: 'text/javascript', defer: true, body: true },
				]
			}
		},

		mounted() {

		},

		components: {
			Teachers,
			LatestCourses,
			Founders,
			MainSlider,
			AboutUs,
			Testimonials
		}
	}
</script>

<style scoped>

</style>

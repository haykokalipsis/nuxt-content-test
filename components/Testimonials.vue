<template>
	<!-- Start testimonial -->
	<section id="mu-testimonial">
		<div class="container">
			<div class="row">
				<div class="col-12 col-md-10 offset-md-1">
					<div class="mu-testimonial-area">
						<div id="mu-testimonial-slider" class="mu-testimonial-content">
							<!-- start testimonial single item -->
							<div class="mu-testimonial-item">
								<div class="mu-testimonial-quote">
									<blockquote>
										<p>Мы признательны нашей родной школе за высокий профессионализм, чуткость и постоянное мотивирование к развитию!</p>
									</blockquote>
								</div>
								<div class="mu-testimonial-img">
									<img src="images/testimonials/ambarcumyan-armen-profile.jpg" alt="img">
								</div>
								<div class="mu-testimonial-info">
									<h4>Армен Амбарцумян</h4>
									<span>Happy Student</span>
								</div>
							</div>
							<!-- end testimonial single item -->

							<!-- start testimonial single item -->
							<div class="mu-testimonial-item">
								<div class="mu-testimonial-quote">
									<blockquote>
										<p>Мы благодарны педагогическому составу школы за самоотверженный труд и успешное обучение школьников.</p>
									</blockquote>
								</div>
								<div class="mu-testimonial-img">
									<img src="images/testimonials/gukasov-profile.jpg" alt="img">
								</div>
								<div class="mu-testimonial-info">
									<h4>Гукасов</h4>
									<span>Happy Parent</span>
								</div>
							</div>
							<!-- end testimonial single item -->

							<!-- start testimonial single item -->
							<div class="mu-testimonial-item">
								<div class="mu-testimonial-quote">
									<blockquote>
										<p>В нашей школе человек развивается не только интеллектуально, но и нравственно!</p>
									</blockquote>
								</div>
								<div class="mu-testimonial-img">
									<img src="images/testimonials/jaklin-profile.jpg" alt="img">
								</div>
								<div class="mu-testimonial-info">
									<h4>Жаклин</h4>
									<span>Happy Student</span>
								</div>
							</div>
							<!-- end testimonial single item -->

							<!-- start testimonial single item -->
							<div class="mu-testimonial-item">
								<div class="mu-testimonial-quote">
									<blockquote>
										<p>Такой душевной атмосферы, как в нашей школе, нет нигде в мире!</p>
									</blockquote>
								</div>
								<div class="mu-testimonial-img">
									<img src="images/testimonials/janeta-profile.jpg" alt="img">
								</div>
								<div class="mu-testimonial-info">
									<h4>Жанета</h4>
									<span>Happy Student</span>
								</div>
							</div>
							<!-- end testimonial single item -->

							<!-- start testimonial single item -->
							<div class="mu-testimonial-item">
								<div class="mu-testimonial-quote">
									<blockquote>
										<p>Я благодарен судьбе за то, что мои дети попали именно в «Славянскую»! <a class="text-primary read-more" data-name="iloyan" href="">Подробнее</a></p>
									</blockquote>
								</div>
								<div class="mu-testimonial-img">
									<img src="images/testimonials/iloyan-profile.jpg" alt="img">
								</div>
								<div class="mu-testimonial-info">
									<h4>Илоян</h4>
									<span>Happy Student</span>
								</div>
							</div>
							<!-- end testimonial single item -->
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>
	<!-- End testimonial -->

</template>

<script>
    export default {
		mounted() {
			$('#mu-testimonial-slider').slick({
				slidesToShow: 1,
				dots: true,
				infinite: true,
				arrows: false,
				autoplay: true,
				speed: 500,
				cssEase: 'linear',
				fade: true,
			});
		}
	}
</script>

<style scoped>

</style>

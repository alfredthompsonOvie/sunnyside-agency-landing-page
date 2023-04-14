<template>
	<main>
		<div class="hero">
			<div class="content">
				<h1 class="title hero__title">we are creatives</h1>

				<img
					src="@/assets/images/icon-arrow-down.svg"
					alt="an icon of an arrow pointing down"
				/>
			</div>
		</div>

		<section class="about" id="about">
			<section class="services">
				<section class="services__card">
					<section class="services__card__img">
						<picture>
							<source
								srcset="@/assets/images/desktop/image-transform.jpg"
								media="(min-width: 768px)"
							/>
							<img src="@/assets/images/mobile/image-transform.jpg" alt="" />
						</picture>
					</section>
					<section class="services__card__content">
						<h2 class="title">Transform your brand</h2>
						<p class="content--description text">
							we are a full-service creative agency specializing in helping
							brands grow fast. Engage your clients through compelling visuals
							that do most of the marketing for you.
						</p>
						<a href="#" class="cta transform">learn more</a>
					</section>
				</section>
				<section class="services__card">
					<section class="services__card__img">
						<picture>
							<source
								srcset="@/assets/images/desktop/image-stand-out.jpg"
								media="(min-width: 768px)"
							/>
							<img src="@/assets/images/mobile/image-stand-out.jpg" alt="" />
						</picture>
					</section>
					<section class="services__card__content">
						<h2 class="title">Stand out to the right audience</h2>
						<p class="content--description text">
							Using a collaborative formula of designers, researchers,
							photographers, videographers, and copywriters, we'll build and
							extend your brand in digital places.
						</p>
						<a href="#" class="cta standout">learn more</a>
					</section>
				</section>
			</section>

			<div class="card">
				<div class="illustration"></div>
				<div class="illustration__content"></div>
			</div>

			<!-- <div class="card">
				<div class="illustration"></div>
				<div class="illustration__content"></div>
			</div> -->
			
			<!--  -->
			<section class="service--secondary">
				<section class="service__card__sec">
					<section class="service__card__sec__img">
						<picture>
							<source
								srcset="@/assets/images/desktop/image-graphic-design.jpg"
								media="(min-width: 768px)"
							/>
							<img
								src="@/assets/images/mobile/image-graphic-design.jpg"
								alt=""
							/>
						</picture>
					</section>
					<section class="service__card__sec__content">
						<h2 class="title">Graphic Design</h2>
						<p class="illustration__content--text text">
							Great design makes you memorable. We deliver artwork that
							underscores your brand message and captures potential client's
							attention.
						</p>
						<!-- <a href="#" class="cta graphicDesign">learn more</a> -->
					</section>
				</section>
				<section class="service__card__sec">
					<section class="service__card__sec__img">
						<picture>
							<source
								srcset="@/assets/images/desktop/image-photography.jpg"
								media="(min-width: 768px)"
							/>
							<img src="@/assets/images/mobile/image-photography.jpg" alt="" />
						</picture>
					</section>
					<section class="service__card__sec__content">
						<h2 class="title">Photography</h2>
						<p class="illustration__content--text text">
							Increase your credibility by getting the most stunning,
							high-quality photos that improve your business image.
						</p>
						<!-- <a href="#" class="cta photography">learn more</a> -->
					</section>
				</section>
			</section>
		</section>
		<section class="testimonials">
			<h1 class="testimonial__title">Client testimonials</h1>
			<section class="testimonial__card__container">
				<section class="testimonial__card">
					<img
						src="@/assets/images/image-emily.jpg"
						alt="an image of emily"
						class="avatar"
					/>
					<section class="testimonial__card__content">
						<p class="testimonial--text">
							We put our trust in Sunnyside and they delivered, making sure our
							needs were met and deadlines were always hit.
						</p>
						<section class="profile">
							<h1 class="name">Emily R.</h1>
							<p class="ocupation">Marketing Director</p>
						</section>
					</section>
				</section>
				<section class="testimonial__card">
					<img
						src="@/assets/images/image-thomas.jpg"
						alt="an image of thomas"
						class="avatar"
					/>
					<section class="testimonial__card__content">
						<p class="testimonial--text">
							Sunnyside’s enthusiasm coupled with their keen interest in our
							brand’s success made it a satisfying and enjoyable experience.
						</p>
						<section class="profile">
							<h1 class="name">Thomas S..</h1>
							<p class="ocupation">Chief Operating Officer</p>
						</section>
					</section>
				</section>
				<section class="testimonial__card">
					<img
						src="@/assets/images/image-jennie.jpg"
						alt="an image of jennie"
						class="avatar"
					/>
					<section class="testimonial__card__content">
						<p class="testimonial--text">
							Incredible end result! Our sales increased over 400% when we
							worked with Sunnyside. Highly recommended!
						</p>
						<section class="profile">
							<h1 class="name">Jennie F..</h1>
							<p class="ocupation">Business Owner</p>
						</section>
					</section>
				</section>
			</section>
		</section>
		<section class="products">
			<section>
				<picture>
					<source
						srcset="@/assets/images/desktop/image-gallery-milkbottles.jpg"
						media="(min-width: 700px)"
					/>
					<img
						src="@/assets/images/mobile/image-gallery-milkbottles.jpg"
						alt=""
					/>
				</picture>
			</section>
			<section>
				<picture>
					<source
						srcset="@/assets/images/desktop/image-gallery-orange.jpg"
						media="(min-width: 700px)"
					/>
					<img src="@/assets/images/mobile/image-gallery-orange.jpg" alt="" />
				</picture>
			</section>
			<section>
				<picture>
					<source
						srcset="@/assets/images/desktop/image-gallery-cone.jpg"
						media="(min-width: 700px)"
					/>
					<img src="@/assets/images/mobile/image-gallery-cone.jpg" alt="" />
				</picture>
			</section>
			<section>
				<picture>
					<source
						srcset="@/assets/images/desktop/image-gallery-sugarcubes.jpg"
						media="(min-width: 700px)"
					/>
					<img
						src="@/assets/images/mobile/image-gallery-sugar-cubes.jpg"
						alt="sugar cubes"
					/>
				</picture>
			</section>
		</section>
	</main>
	<footer class="footer">
		<section class="footer__contents">
			<a href="#" class="branding__footer">
				<img src="@/assets/images/logo.svg" alt="site logo" />
			</a>

			<ul class="footer__links">
				<li><a href="#" class="footer__link">About</a></li>
				<li><a href="#" class="footer__link">Services</a></li>
				<li><a href="#" class="footer__link">Projects</a></li>
			</ul>

			<ul class="socials">
				<li class="socials__item">
					<a href="https://www.facebook.com" class="social__link">
						<img
							src="@/assets/images/icon-facebook.svg"
							alt="a link to facebook"
						/>
					</a>
				</li>
				<li class="socials__item">
					<a href="https://www.instagram.com" class="social__link">
						<img
							src="@/assets/images/icon-instagram.svg"
							alt="a link to instagram"
						/>
					</a>
				</li>
				<li class="socials__item">
					<a href="https://www.twitter.com" class="social__link">
						<img
							src="@/assets/images/icon-twitter.svg"
							alt="a link to twitter"
						/>
					</a>
				</li>
				<li class="socials__item">
					<a href="https://www.pinterest.com" class="social__link">
						<img
							src="@/assets/images/icon-pinterest.svg"
							alt="a link to pinterest"
						/>
					</a>
				</li>
			</ul>
		</section>
	</footer>
	<!-- <div>
  <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
    Coded by <a href="#">Your Name Here</a>.
  </div>
  </div> -->
</template>

<script setup></script>

<style scoped>
.testimonials {
	text-align: center;
	color: var(--DarkGrayishBlue);
	padding: 3em 0;
	margin: 4em 0;
}
.testimonial__card__container {
	display: grid;
	grid-template-columns: repeat(auto-fit, minmax(250px, 350px));
	justify-content: center;
	gap: 2.5em;
	padding: 0 1em;
}
.testimonial__title {
	color: var(--GrayishBlue);
	font-family: var(--ff-heading);
	text-transform: uppercase;
	letter-spacing: 3px;
	font-size: 1.3rem;
	font-weight: var(--fw-xbold);
	margin: 1em 0 4em;
}
.avatar {
	border-radius: 50%;
	width: 4em;
}
.testimonial--text {
	margin: 1.5em 0;
	line-height: 1.5;
}
.name {
	font-family: var(--ff-heading);
	color: var(--VeryDarkGrayishBlue);
	font-weight: var(--fw-xxbold);
	font-size: 1rem;
}
.ocupation {
	font-size: 0.75rem;
	color: var(--GrayishBlue);
	margin-top: 1em;
}
.products {
	/* display: flex;
	flex-wrap: wrap; */
	display: grid;
	grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
}
.products img {
	/* object-fit: cover; */
	height: 100%;
}

footer {
	--DarkDesaturatedCyan_Graphic_design_text: hsl(167, 40%, 24%);
	--DarkBlue_photography_text: hsl(198, 62%, 26%);
	--DarkModerateCyan_footer: hsl(168, 34%, 41%);

	--VeryDarkDesaturatedBlue: hsl(212, 27%, 19%);
	--VeryDarkGrayishBlue: hsl(213, 9%, 39%);
	--DarkGrayishBlue: hsl(232, 10%, 55%);
	--GrayishBlue: hsl(210, 4%, 67%);
	--White: hsl(0, 0%, 100%);
	background-color: var(--DarkModerateCyan_footer);
	background-color: var(--GrayishBlue);
	padding: 4em 1em;
	text-align: center;
}
.footer__contents {
	max-width: 300px;
	margin-inline: auto;
}
.branding__footer img {
	filter: invert(0.5) sepia(1) hue-rotate(140deg) brightness(0.3);
	filter: invert(0.5) sepia(1) hue-rotate(140deg) brightness(0.3) saturate(1);
	/* filter: invert(.3) sepia(1) hue-rotate(140deg) brightness(.8) saturate(2); */
	/* filter: invert(.3) sepia(1) hue-rotate(80deg) brightness(.6) saturate(3); */
}
.footer__links {
	display: flex;
	justify-content: space-between;
	align-items: center;
	flex-wrap: wrap;
	gap: 0.5em;
	margin: 2.5em 0 4em;
}
.footer__link {
	color: var(--DarkDesaturatedCyan_Graphic_design_text);
	/* color: var(--DarkBlue_photography_text); */
	font-weight: var(--fw-bold);
}
.socials {
	display: flex;
	justify-content: center;
	align-items: center;
	gap: 1em;
	flex-wrap: wrap;
}
</style>

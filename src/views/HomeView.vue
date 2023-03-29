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
			<div class="card">
				<div class="illustration">
					<picture>
						<source
							srcset="@/assets/images/desktop/image-transform.jpg"
							media="(min-width: 768px)"
						/>
						<img src="@/assets/images/mobile/image-transform.jpg" alt="" />
					</picture>
				</div>
				<div class="illustration__content">
					<h2 class="title">Transform your brand</h2>
					<p class="illustration__content--text text">
						we are a full-service creative agency specializing in helping brands
						grow fast. Engage your clients through compelling visuals that do
						most of the marketing for you.
					</p>
					<a href="#" class="cta transform">learn more</a>
				</div>
			</div>
			<div class="card">
				<div class="illustration">
					<picture>
						<source
							srcset="@/assets/images/desktop/image-stand-out.jpg"
							media="(min-width: 768px)"
						/>
						<img src="@/assets/images/mobile/image-stand-out.jpg" alt="" />
					</picture>
				</div>
				<div class="illustration__content">
					<h2 class="title">Stand out to the right audience</h2>
					<p class="illustration__content--text text">
						Using a collaborative formula of designers, researchers,
						photographers, videographers, and copywriters, we'll build and
						extend your brand in digital places.
					</p>
					<a href="#" class="cta stand-out">learn more</a>
				</div>
			</div>
			<div class="card">
				<div class="illustration">
					<picture>
						<source
							srcset="@/assets/images/desktop/image-graphic-design.jpg"
							media="(min-width: 768px)"
						/>
						<img src="@/assets/images/mobile/image-graphic-design.jpg" alt="" />
					</picture>
				</div>
				<div class="illustration__content">
					<h2 class="title">Graphic Design</h2>
					<p class="illustration__content--text text">
						Great design makes you memorable. We deliver artwork that
						underscores your brand message and captures potential client's
						attention.
					</p>
					<a href="#" class="cta graphicDesign">learn more</a>
				</div>
			</div>
			<div class="card">
				<div class="illustration">
					<picture>
						<source
							srcset="@/assets/images/desktop/image-photography.jpg"
							media="(min-width: 768px)"
						/>
						<img src="@/assets/images/mobile/image-photography.jpg" alt="" />
					</picture>
				</div>
				<div class="illustration__content">
					<h2 class="title">Photography</h2>
					<p class="illustration__content--text text">
						Increase your credibility by getting the most stunning, high-quality photos that improve your business image.
					</p>
					<a href="#" class="cta photography">learn more</a>
				</div>
			</div>
		</section>
	</main>
	<!-- <div>
    
    Client testimonials

  We put our trust in Sunnyside and they delivered, making sure our needs were met and deadlines were always hit.
  Emily R.
  Marketing Director

  Sunnyside’s enthusiasm coupled with their keen interest in our brand’s success made it a satisfying and enjoyable experience.
  Thomas S.
  Chief Operating Officer

  Incredible end result! Our sales increased over 400% when we worked with Sunnyside. Highly recommended!
  Jennie F.
  Business Owner

  <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
    Coded by <a href="#">Your Name Here</a>.
  </div>
  </div> -->
</template>

<script setup></script>

<style scoped></style>

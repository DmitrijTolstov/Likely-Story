<script setup>
import CrownIcons from './icons/CrownIcons.vue';


</script>
<template>
	<section class="hero">
		<div class="container">
			<main class="hero-container">
				<div class="hero-container_images">
					<img src="https://likely-story.co.uk/wp-content/themes/Likely%20Story/dist/images/shapes/hero-main.png"
						alt="">
					<img class='blink'
						src="https://likely-story.co.uk/wp-content/themes/Likely%20Story/dist/images/shapes/hero-main-blink.png"
						alt="">
				</div>
				<h1 class="hero-container__title ">
					<span class='hero-container__title_item hero-container__title_black'>Small</span>
					<span class='hero-container__title_item'>Studio</span>
				</h1>
				<h1 class="hero-container__title hero-container__title_right">
					<span class='hero-container__title_item hero-container__title_black'>Big</span>
					<span class='hero-container__title_item'>Ideas</span>
				</h1>
				<img class='hero-container__image'
					src="https://likely-story.co.uk/wp-content/themes/Likely%20Story/dist/images/shapes/hero-shape.png"
					alt="">
			</main>
			<main class="intro">
				<div class="intro-content">
					<CrownIcons class='intro-content_image' />

					<p class='intro-content__text'>
						We’re Likely Story, an award-winning boutique design studio. We deliver
						<strong>
							spell-binding
							<svg data-stroke="#000" width='180' xmlns="http://www.w3.org/2000/svg"
								viewBox="0 0 185.957 61.128">
								<path class="p-circle" data-name="Path 10926"
									d="M5123.9-918.415c-42.727-23.458-244.844-6.845-165.158,35.188,51.42,27.124,195.73,9.857,150.576-29.8"
									transform="translate(-4939.304 930.161)" fill="none" stroke="#000"
									stroke-linecap="round" stroke-miterlimit="10" stroke-width="2"
									data-svg-origin="4940.32568359375 -929.1149291992188"></path>
							</svg>
						</strong> work for
						international clients. Ask us about digital, branding and storytelling.
					</p>
				</div>
			</main>
		</div>
	</section>
</template>
<style scoped lang='scss'>
.hero {
	&-container {
		position: relative;

		&_images {
			position: relative;

			img {
				position: absolute;
				top: 30vw;
				left: 0;
				width: 800px;
				height: 900px;
			}

			.blink {
				visibility: hidden;
				transition: blink .4s linear;
			}
		}

		&__image {
			position: absolute;
			right: 10vw;
			top: 9vw;
			height: 700px;
		}

		&__title {
			font-size: 20vw;
			overflow: hidden;

			&_right {
				margin-inline-start: 42vw;

			}

			&_item {
				display: block;
				line-height: .75;
			}

			&_black {
				color: vars.$black;
			}
		}
	}

	.intro {
		margin-inline-start: 42vw;

		&-content {
			max-width: 50rem;
			margin-block-start: 9rem;
			position: relative;

			&__text {
				font-size: 2.6rem;
				line-height: 1.75;

				strong {
					position: relative;
					display: inline-block;
					font-weight: inherit;

					svg {
						position: absolute;
						left: -1.76rem;
						top: -1rem;
					}
				}
			}

			&_image {
				position: absolute;
				right: 5rem;
				top: -3.5rem;
			}
		}
	}
}
</style>
<script setup>
</script>
<template>
	<main class="withUs">
		<div class="withUs-container">
			<div class="withUs-container-image">
				<img src='@/assets/images/home-cta-illy@2x-1006x1440.png' alt="">
			</div>
			<div class="withUs-container-content">
				<h1 class="withUs__title title-black">Work</h1>
				<h1 class="withUs__title">With Us</h1>
				<div class="content-text">
					<p class="withUs__text">Want to work together? Email us…</p>
					<a href="" class="withUs__link">
						hello@likelystory.agency
						<svg data-stroke="#000" xmlns="http://www.w3.org/2000/svg" width="200.957" height="61.128"
							viewBox="0 0 185.957 61.128">
							<path class="p-circle" data-name="Path 10926"
								d="M5123.9-918.415c-42.727-23.458-244.844-6.845-165.158,35.188,51.42,27.124,195.73,9.857,150.576-29.8"
								transform="translate(-4939.304 930.161)" fill="none" stroke="#000"
								stroke-linecap="round" stroke-miterlimit="10" stroke-width="2"></path>
						</svg>

					</a>
				</div>
			</div>
		</div>
	</main>
</template>
<style scoped lang='scss'>
.withUs {

	&-container {
		display: flex;
		align-items: center;

		&-image {
			width: 40vw;

			img {
				width: 100%;
			}
		}

		&-content {

			.withUs__title {
				font-size: 25rem;
				line-height: .9;
			}

			.content-text {
				display: flex;
				justify-content: flex-end;
				margin-block-start: 4rem;

				.withUs__text {
					font-size: 1.8rem;
				}

				.withUs__link {
					margin-inline-start: 2rem;
					font-size: 1.8rem;
					position: relative;

					svg {
						position: absolute;
						z-index: 2;
						top: -2.8rem;
						left: -2rem;
						width: 125%;

					}

				}
			}
		}
	}
}
</style>

<script setup>

</script>

<template>
	<div class="video-holder">
		<div class="video-holder-wrap">
			<div class="play">
				<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 26 26">
					<polygon fill='#fff' points="9.33 6.69 9.33 19.39 19.3 13.04 9.33 6.69"></polygon>
				</svg>
			</div>
			<div class="images">
				<img src="@/assets/images/video-banner.png" alt="">
			</div>
		</div>

	</div>
</template>

<style scoped lang='scss'>
.video-holder {
	display: flex;
	justify-content: end;
	margin-inline-end: 4rem;
	margin-block-start: 6rem;

	&-wrap {
		position: relative;

		&::before {
			position: absolute;
			content: '';
			width: 100%;
			height: 100%;
			background-color: vars.$white;
			z-index: 1;
			inset: 0;
			clip-path: polygon(20% 0, 91% 0, 100% 15%, 100% 100%, 80% 100%, 9.5% 100%, 0 85.1%, 0 0);
		}

		.play {
			position: absolute;
			z-index: 5;
			width: 9rem;
			height: 9rem;
			background-color: vars.$black;
			border-radius: 50%;
			top: 50%;
			transform: translateY(-50%);
			left: 0;
			right: 0;
			margin: 0 auto;
			cursor: pointer;
			display: flex;
			justify-content: center;
			align-items: center;
			transition: transform .3s ease;

			&:hover {
				transform: scale(1.1) translateY(-40%);
			}

			svg {
				width: 3rem;
				height: 3rem;
			}
		}

		.images {
			position: relative;
			transform: scale(.98);
			z-index: 2;
			clip-path: polygon(20% 0, 91% 0, 100% 15%, 100% 100%, 80% 100%, 9.5% 100%, 0 85.1%, 0 0);
		}
	}
}
</style>
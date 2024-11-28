<script setup>
import ImageContainer from './ImageContainer.vue';
import WithUs from './WithUs.vue';


</script>
<template>
	<div class="container">
		<section class="content">
			<div class="work-text">
				<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 246.05 245.35">
					<g id="Layer_2" data-name="Layer 2">
						<g id="Layer_1-2" data-name="Layer 1">
							<path class="cls-1 w-mask"
								d="M24.5,245.35,0,0H73.5c2.1,84-2.8,117.6-13.65,194.25l8.75,1.05L114.45,0H132L177.8,193.9l8.75-1.05C175.7,116.2,170.45,84,172.55,0h73.5l-24.5,245.35h-80.5l-13.65-99h-8.75l-13.65,99Z"
								data-svg-origin="0 0" transform="matrix(1,0,0,1,0,0)">
							</path>
						</g>
					</g>
				</svg>
				<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 258.3 258.3">
					<g id="Layer_2" data-name="Layer 2">
						<g id="Layer_1-2" data-name="Layer 1">
							<path class="cls-1 o-mask"
								d="M258.3,129.15A129.15,129.15,0,1,1,129.15,0,129.06,129.06,0,0,1,258.3,129.15Zm-67.55,0a61.6,61.6,0,1,0-61.6,61.6A61.69,61.69,0,0,0,190.75,129.15Z"
								data-svg-origin="0 -0.00003141328488709405">
							</path>
						</g>
					</g>
				</svg>
				<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 183.05 245.72">
					<g id="Layer_2" data-name="Layer 2">
						<g id="Layer_1-2" data-name="Layer 1">
							<path class="cls-1 r-mask"
								d="M59.85,162.42c13.65,43.4,13.65,58.8,13.65,83.3H0L3.5.72,74.55,0C139.3-.68,175.7,18.57,175.7,60.92c0,45.85-38.85,73.85-115.5,73.85v9.1h60.9c14.35,29,29.4,35.7,62,32.55v69.3c-54.6,0-88.55-14.35-113.75-85.05Zm11.55-56.7c18.55,0,28.7-10.85,28.7-29.4,0-17.5-10.15-24.85-28.7-24.85h-7l2.1,54.25Z"
								data-svg-origin="0 -0.017385195940732956">
							</path>
						</g>
					</g>
				</svg>
				<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 191.1 245">
					<g id="Layer_2" data-name="Layer 2">
						<g id="Layer_1-2" data-name="Layer 1">
							<path class="cls-1 k-mask"
								d="M3.5,0h70C70,34.65,59.15,65.8,29.75,113.4l7.35,5.25L112,0h79.1L78.75,140.7l4.9,5.25L114.8,130.2c17.5,34.3,37.1,46.9,68.25,46.55V245c-54.6,0-89.25-14.35-128.8-104.65l-7.7,4.2c21.7,52.85,26.25,76.3,27,100.45H0Z"
								data-svg-origin="0 0">
							</path>
						</g>
					</g>
				</svg>
			</div>
			<ImageContainer />
			<WithUs />
		</section>
	</div>

</template>
<style scoped lang='scss'>
.work-text {
	display: flex;
	width: 50%;
	transform: rotate(-8deg);
	gap: 10px;
}
</style>
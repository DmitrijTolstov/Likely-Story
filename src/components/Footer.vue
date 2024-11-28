<script setup>
import Instagram from './icons/Instagram.vue';
import LogoIcons from './icons/LogoIcons.vue';





</script>

<template>
	<footer class="footer">
		<div class="container">
			<div class="footer-content">
				<div class="footer-info">
					<LogoIcons />
					<p>© Likely Story Agency Ltd. All Rights Reserved 2024.</p>
					<a>Privacy, Terms & Cookies</a>
				</div>
				<div class="footer-contacts">
					<p>10a Stevenson Square, Manchester M1 1FB</p>
					<Instagram />
				</div>
			</div>
		</div>
	</footer>
</template>

<style scoped lang='scss'>
.footer {
	background-color: vars.$black;
	padding-block: 5rem;

	&-content {
		display: flex;
		align-items: center;
		justify-content: space-between;


		.footer-info {
			display: flex;
			align-items: center;
			gap: 3rem;

			p {
				color: vars.$gray;
			}

			a {
				position: relative;
				color: vars.$gray;
				cursor: pointer;

				&::after {
					position: absolute;
					content: '';
					width: 0.5rem;
					height: 0.5rem;
					background-color: vars.$gray;
					border-radius: 50%;
					top: 50%;
					transform: translateY(-50%);
					left: -1.5rem;
				}
			}

		}

		.footer-contacts {
			display: flex;
			align-items: center;
			gap: 3rem;

			p {
				color: vars.$gray;
			}
		}

	}

}
</style>
<script setup>
import LogoIcons from './icons/LogoIcons.vue';


</script>
<template>
	<header class="header">
		<div class="container">
			<nav class="header-nav">
				<LogoIcons />
				<ul class="nav-items">
					<a href="" class="nav-items_item">About</a>
					<a href="" class="nav-items_item">Work</a>
					<a href="" class="nav-items_item">Contact</a>
				</ul>
			</nav>
		</div>
	</header>
</template>
<style scoped lang='scss'>
.header {
	padding-block: 2rem;

	&-nav {
		display: flex;
		justify-content: space-between;
		align-items: center;
		color: vars.$white;

		.nav-items {
			display: flex;
			gap: 4rem;

			&_item {
				font-size: 2rem;
				position: relative;

				&::before {
					transition: opacity .5s ease-in-out;
					content: '';
					position: absolute;
					width: 5px;
					height: 5px;
					border-radius: 50%;
					background-color: vars.$white;
					left: 50%;
					transform: translateX(-50%);
					bottom: -2rem;
					opacity: 0;
				}

				&:hover {

					&::before {
						opacity: 1;
					}
				}
			}
		}
	}
}
</style>
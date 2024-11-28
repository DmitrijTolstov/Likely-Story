<script setup>
</script>
<template>
	<main class='image-container'>
		<div class="image-content">
			<div class="images-box"></div>
			<div class="text-box">
				<div class="text-box-links">
					<a href="" class="text-box_link">Askonas Holt</a>
					<p>view</p>
				</div>
				<div class="text-box-links">
					<a href="" class="text-box_link">Bertch Capital</a>
					<p>view</p>
				</div>
				<div class="text-box-links">
					<a href="" class="text-box_link">Our Revolution</a>
					<p>view</p>
				</div>
				<div class="text-box-links">
					<a href="" class="text-box_link">Novo</a>
					<p>view</p>
				</div>
				<div class="text-box-links">
					<a href="" class="text-box_link">The Edwin Group</a>
					<p>view</p>
				</div>
				<div class="text-box-links">
					<a href="" class="text-box_link">Smile Kitchens</a>
					<p>view</p>
				</div>
			</div>
		</div>
	</main>
</template>
<style scoped lang='scss'>
.image-container {
	margin-block: 8rem;

	.image-content {
		position: relative;

		.images-box {
			position: absolute;
			width: 30%;
			height: 90%;
			content: '';
			background-color: aquamarine;
			left: 4rem;
			top: -3rem;
			transform: rotate(7deg);
			z-index: 10;

		}

		&::before {
			position: absolute;
			width: 31%;
			height: 92%;
			content: '';
			background-color: vars.$white;
			left: 3rem;
			top: -3.5rem;
			transform: rotate(7deg);
			z-index: 2;
		}

		.text-box {
			width: 80%;
			display: flex;
			flex-direction: column;

			&-links {
				position: relative;
				display: flex;
				align-items: center;
				justify-content: center;
				padding-block: 4rem;
				cursor: pointer;
				border-top: 1px solid vars.$black;

				&:last-child {
					border-bottom: 1px solid vars.$black;
				}
			}
		}

		.text-box_link {
			font-size: 2.4rem;
		}

		p {
			font-size: 2.4rem;
			position: absolute;
			right: 0;
			opacity: 0;
		}
	}
}
</style>
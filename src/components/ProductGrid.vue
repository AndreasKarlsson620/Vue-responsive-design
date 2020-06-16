<template>
	<div>
		<div class="grid">
			<div class="product">
				Vue
			</div>
			<div class="product">
				Responsive
			</div>
			<div class="product">
				Design
			</div>
		</div>
	</div>
</template>

<script>
export default {
  name: 'ProductGrid',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.grid
{
	display: grid;
	grid-template-columns: 1fr 1fr 1fr;
	grid-gap: 1em;
	margin: 0em 10em;
}
.product
{
	border: 1px solid black;
	background-color: white;
	color: black;
}
.product:hover
{
	background-color: black;
	color: white;
}
@media (max-width: 700px)
{
	.grid
	{
		display: grid;
		grid-template-columns: 1fr;
	}
}
</style>

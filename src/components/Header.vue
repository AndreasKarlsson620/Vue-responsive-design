<template>
	<div>
		<h3>
			Vue responsive design
		</h3>
		<div>
			<div class="button">
				<button>
					Vue
				</button>
			</div>
			<div class="button">
				<button>
					Responsive
				</button>
			</div>
			<div class="button">
				<button>
					Design
				</button>
			</div>
		</div>
	</div>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3
{}
.button
{
	display: inline;
	margin-left: 1em;
}
button
{
	border: 1px solid black;
	background-color: white;
	color: black;
}
button:hover
{
	background-color: black;
	color: white;
}
@media /*(min-width: 250px) and */(max-width: 700px)
{
	.button
	{
		display: block;
	}
	button
	{
		width: 100%
	}
}
</style>

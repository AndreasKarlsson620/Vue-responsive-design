<template>
	<div>
		<div>
			<p>
				This is a Vue app that demonstrates responsive design.
			</p>
		</div>
	</div>
</template>

<script>
export default {
  name: 'InfoText',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
p:hover
{
	background-color: black;
	color: white;
}
@media (max-width: 700px)
{
	p
	{
		font-size: 2em;
		margin: 1em;
	}
}
</style>

<template>
	<div>
		<div class="alert alert-primary" role="alert">
			<slot></slot>
		</div>
	</div>
</template>

<script>
export default {
name: "Alert",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
	.alert-primary {
		color: #004085;
		background-color: #cce5ff;
		border-color: #b8daff;
	}

	.alert {
		position: relative;
		padding: .75rem 1.25rem;
		margin-bottom: 1rem;
		border: 1px solid transparent;
		border-radius: .25rem;
	}
</style>

<template>
	<div id="emptycontent">
		<p> <slot /></p>
	</div>
</template>

<script>
export default {
	name: 'EmptyMailbox',
}
</script>
<style scoped lang="scss">
	#emptycontent {
		margin-top: 10px;
	}
</style>

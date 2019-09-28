<template lang="html">
  <h1>A sinlge user with ID: {{ $route.params.id }}</h1>
</template>

<script>
export default {
	validate (data) {
		return data.params.id == 1;
	}
}
</script>

<style lang="css" scoped>
</style>

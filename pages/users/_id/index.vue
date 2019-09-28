<template lang="html">
  <h1>A sinlge user with ID: {{ $route.params.id }}</h1>
</template>

<script>
export default {
	validate (data) {
		return /^\d+$/.test(data.params.id)
		// will test to see if id entered is a number
	}
}
</script>

<style lang="css" scoped>
</style>

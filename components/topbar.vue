<template>
	<div>
		<router-link to="/">
			<button class="btn">Home</button>
		</router-link>
		<router-link to="/table">
			<button class="btn">Vuetable</button>
		</router-link>
		<router-link to="/about">
			<button class="btn">About</button>
		</router-link>
	</div>
</template>

<script>
	module.exports = {
		name: 'topbar',
	};
</script>

<style scoped>
	div {
		padding: 30px;
	}

	button {
		padding: 10px 20px;
		border-radius: 8px;
		border-color: white;
		background-color: rgb(3, 177, 75);
		color: white;
		cursor: pointer;
		transition: 0.2s;
	}

	button:hover {
		color: white;
		background-color: rgb(78, 238, 190);
	}
</style>

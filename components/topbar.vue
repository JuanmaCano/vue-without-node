<template>
	<div>
		<router-link to="/">
			<button class="btn">Home</button>
		</router-link>
		<router-link to="/about">
			<button class="btn">About</button>
		</router-link>
		<router-link to="/contact">
			<button class="btn">Contact</button>
		</router-link>
	</div>
</template>

<script>
module.exports = {
	name: 'topbar',

	data: function () {
		return {};
	},
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
	background-color: darkorange;
	color: white;
	cursor: pointer;
	transition: 0.2s;
}

button:hover {
	color: darkorange;
	background-color: white;
}
</style>

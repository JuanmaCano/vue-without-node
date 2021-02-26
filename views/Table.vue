<template>
	<div>
		<vuetable ref="vuetable" api-url="https://vuetable.ratiw.net/api/users" :fields="['name', 'nickname', 'email', 'gender']" />
	</div>
</template>

<script>
	module.exports = {
		name: 'Table',
	};
</script>

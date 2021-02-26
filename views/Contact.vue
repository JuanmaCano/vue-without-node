<template>
	<div>
		<vuetable
			ref="vuetable"
			api-url="https://vuetable.ratiw.net/api/users"
			:fields="['name', 'nickname', 'email', 'gender']"
			data-path=""
			pagination-path=""
		></vuetable>
	</div>
</template>

<script>
	/*
vue.js:634 [Vue warn]: 
Unknown custom element: 
<vuetable> - did you register the component correctly?
For recursive components, make sure to provide the "name" option.
found in
---> <Contact>
       <Root>
*/
	module.exports = {
		name: 'Contact',
		components: {
			//Vuetable,
		},
	};
</script>

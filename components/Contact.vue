<template lang='pug'>
v-list
	v-list-item
		v-list-item-icon
			v-icon mdi-phone
		v-list-item-content
			v-list-item-title 54 54 35 46 35
	v-list-item
		v-list-item-icon
			v-icon mdi-email
		v-list-item-content
			v-list-item-title ksjfzk@kjfhkjqh
		v-list-item-action
			Form
	v-list-item
		v-list-item-icon
			v-icon mdi-map-marker
		v-list-item-content
			v-list-item-title 254 Avenue de Monnom #[br] 68765 
</template>

<script lang='coffee'>
import Form from '~/components/Form'

export default
	components: {Form}
</script>
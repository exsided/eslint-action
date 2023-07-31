<template>
	<div>
		<h1 v-html="msg" class="123" v-if="msg">{{ msg }}</h1>
	</div>
</template>

<script>
export default {
	name: 'HelloWorld',
	components: {},
	props:
	{
		msg: Number
	},
	data()
	{
		return {};
	},
	computed:
	{},
	mounted()
	{},
	methods:
	{},
};
</script>

<style lang="scss">
	/*@import './style.scss';*/
</style>

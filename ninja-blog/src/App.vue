<template>
	<div>
		<add-blog></add-blog>
	</div>
</template>

<script>
import addBlog from './components/addBlog.vue';

export default {
	components: {
		'add-blog': addBlog
	},
	data() {
		return {

		}
	},
	methods: {

	}
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Nunito');

body{
	margin: 0;
	font-family: 'Nunito';
}
</style>
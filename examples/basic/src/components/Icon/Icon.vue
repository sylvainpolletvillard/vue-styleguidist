<template>
  <div v-html="require(`../svg/${iconName}.svg`)"></div>
</template>
<script>
export default {
	name: 'Icon',
	props: {
		iconName: String,
	},
};
</script>
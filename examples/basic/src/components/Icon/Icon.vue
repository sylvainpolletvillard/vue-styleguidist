<template>
  <div :style="`width:${width};`" v-html="require(`../svg/${iconName}.svg`)"></div>
</template>
<script>
export default {
	name: 'Icon',
	props: {
		/**
		 * name of the svg file to load
		 */
		iconName: String,
		/**
		 * width of the icon (CSS dimension)
		 */
		width: String,
	},
};
</script>
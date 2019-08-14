<template>
  <div class="works">
    <Work v-for="item in works" v-bind:text="item.text"  v-bind:key="item.id"></Work>
  </div>
</template>

<script>
	import Work from './Work.vue'
	export default {
		name: "works",
		props: ['works'],
		components: {
			Work
		}
	}
</script>

<style scoped>

</style>
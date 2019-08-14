<template>
  <div class="works">
    <Work v-for="work in works" v-bind:key="work.id" v-bind:nom="work.nom"></Work>
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
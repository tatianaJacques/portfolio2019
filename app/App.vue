<template>
  <div class="full-width center-content">
    <Header name="Tatiana JACQUES" job="Developpeur front-end" />
    <Works v-bind:works="worksData"/>
  </div>
</template>

<script>
	import Header from './components/Header.vue'
	import Works from './components/Works.vue'


	var data = {
		worksData: [
			{ text: 'Learn JavaScript' },
			{ text: 'Learn Vue' },
			{ text: 'Build something awesome' }
		]
	}

	export default {
		data: function () {
			return {
				worksData: data.worksData
			};
		},
		components: {
			Header,
			Works
		}
	}
</script>
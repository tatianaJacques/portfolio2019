<template>
  <div class="full-width center-content">
    <Header name="Tatiana JACQUES" job="Developpeur front-end" />
    <Works v-bind:works="worksData"/>
  </div>
</template>

<script>
	import axios from "axios"
	import Header from './components/Header.vue'
	import Works from './components/Works.vue'

	var data = {
		worksData: []
	}

	export default {
		data: function () {
			return {
				worksData: data.worksData
			};
		},
		mounted() {
			axios.get("app/assets/data/data.json")
				.then(response => {
					this.worksData = response.data.projets
					console.log('ok', this.worksData)
				})
		},
		components: {
			Header,
			Works
		}
	}
</script>
<template>
  <div class="full-width center-content">
    <Header name="Tatiana JACQUES" job="Front-end" />
    <!--
    <Wdywtk />
    <Works v-bind:works="worksData"/>
    -->
    <Waiting></Waiting>
  </div>
</template>

<script>
	import axios from "axios"
	import Header from './components/Header.vue'
	import Works from './components/Works.vue'
	import Wdywtk from './components/Wdywtk.vue'
	import Waiting from './components/Waiting.vue'

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
			Works,
			Wdywtk,
			Waiting
		}
	}
</script>
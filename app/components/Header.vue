<template>
  <nav>
    <ul>
      <li>
       {{ name }}
      </li>
      <li>
        {{ job }}
      </li>
    </ul>
  </nav>
</template>

<script>
	export default {
		props: {
			name: {
				type: String,
				required: true
			},
			job: {
				type: String,
				required: true
			}
		}
	}
</script>

<style lang="stylus" scoped>
  nav
    width 100vw
    display block
</style>
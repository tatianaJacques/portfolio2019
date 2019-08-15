<template>
  <nav>
    <ul>
      <li>
       {{ name }}
      </li>
      <li>
        {{ job }}
      </li>
      <li>
        Recherche CDI Paris / Montreuil
      </li>
      <li>
        <a href="https://www.linkedin.com/in/tatiana-j/" target="_blank"><img src="img/linkedin.png" alt=""></a>
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
  ul
    font-family Arial
    list-style none
    margin: 0
    padding: 0
    margin-bottom 15px
  li
    margin 5px
    margin-left: 10px
    margin-right: 20px
    font-size: 12px
  a
    color: #9db2ff
    text-decoration none
    font-weight bold
  img
    width: 30px
</style>
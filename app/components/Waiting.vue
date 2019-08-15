<template>
  <div class="wait">
    <div class="landing">
      <p>Ce portoflio est actuellement en refonte.</p>
    </div>

    <div>
      <h2>Projets</h2>

      <div class="wait_work">
        <h3>1253</h3>
        <img src="img/1253.png" alt="">
        <img src="img/1253_1.png" alt="">
        <img src="img/1253_2.png" alt="">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/1BwVyhmFpMQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <ul>
          <li>Client réel</li>
          <li>Tests utilisateurs</li>
          <li>Revalorisation du patrimoine</li>
          <li>Vue.js</li>
          <li>Pixi.js</li>
          <li>Animations</li>
        </ul>
        <p>Projet en collaboration avec l'école de la Sorbonne dans le cadre d'un projet de fin Master Design et Management de l'Innovation Interactive aux Gobelins.</p>
        <p>Une future présentation du projet est prévu lors des journées européenne du patrimoine 2019 en Sorbonne.</p>
        <p>Le SIRIS de la Sorbonne en parle : <a target="_blank" href="https://www.siris.sorbonne.fr/gobelins/?fbclid=IwAR2RJvnAN3EQmNg_cQWfAOeINaEJf_HF-WaQU1u5Za6zRQhgxUDs611Q8PA">www.siris.sorbonne</a></p>
        <p>Mon rôle : développement front-end et animations des éléments</p>
        <a href="http://aliciabaudry.garden/1253/fr/" target="_blank">Lien vers le projet</a>
      </div>

      <div class="wait_work">
        <h3>AFP - Le Fil</h3>
        <img src="img/afp1.gif" alt="">
        <img src="img/afp2.png" alt="">
        <img src="img/afp3.png" alt="">
        <ul>
          <li>Client réel</li>
          <li>Gestion Big Data</li>
          <li>Vue.js</li>
          <li>Three.Js</li>
          <li>GSAP</li>
          <li>API AFP</li>
        </ul>
        <p>Projet en collaboration avec l'AFP dans le cadre d'un projet pour le Master Design et Management de l'Innovation Interactive aux Gobelins.</p>
        <p>Notre rôle était de mettre en valeur les données de l'API de l'AFP.</p>
        <p>Mon rôle : développement front-end et animations des éléments</p>
      </div>

      <div class="wait_work">
        <h3>A la bonheur</h3>
        <img src="img/alb1.png" alt="">
        <img src="img/alb2.png" alt="">
        <img src="img/alb3.png" alt="">
        <ul>
          <li>Projet conception</li>
          <li>Tests utilisateurs</li>
        </ul>
        <p>Projet fait dans le cadre de mon Master Design et Management de l'Innovation Interactive aux Gobelins.</p>
        <p>Notre mission était de trouver un service liant deux générations différentes et de le présenter à Station F.</p>
        <p>Ce service devait être viable et être validé par les futurs utilisateurs.</p>
        <p>A la bonheur est un service permettant aux personnes à la retraite de trouver des activités en partenariat avec des entreprises.</p>
        <a href="img/alabonheur.pdf" target="_blank">Le concept en détail</a>
      </div>

      <div class="wait_work">
        <h3>Flow</h3>
        <img src="img/flow1.gif" alt="">
        <img src="img/flow2.gif" alt="">
        <img src="img/flow3.png" alt="">
        <ul>
          <li>Projet client</li>
          <li>Three.js</li>
          <li>Typographie</li>
          <li>Synchronisation</li>
        </ul>
        <p>Projet fait dans le cadre de mon Master Design et Management de l'Innovation Interactive aux Gobelins en partenariat avec Astérios.</p>
        <p>Notre mission était de mettre en valeur les artistes d'Astérios.</p>
        <p>Flow est une expérience interactive typograpique permettant de découvrir les artistes du label via les paroles communes des chansons.</p>
        <p>Mon rôle a été la création de la structure et la gestion des animations.</p>
        <a href="https://www.behance.net/gallery/66346653/FLOW-une-exprience-web-typotique" target="_blank">Le concept en détail</a>
      </div>

      <div class="wait_work">
        <h3>4 années d'alternance</h3>
        <p>Chez DISKO et OHWEE</p>
        <p>Festival de Cannes, Pierre Frey, Ubisoft, CA Immobilier, Thai Kitchen, Belldandy, Hermès, PMU, Hennessy... </p>
        <p>Mes missions : intégration, front, structure starter front, animations, ... </p>
      </div>
    </div>
  </div>
</template>

<script>
	export default {
		props: {
		}
	}
</script>

<style lang="stylus" scoped>
  .wait
    text-align center
    margin 0 auto
    width: 100vw
    h2
      font-size 35px
    img
      width: 562px
      margin-bottom: 10px
  .wait_work
    width 562px
    text-align center
    margin 0 auto
    margin-bottom 105px
    h3
      font-size 28px
    p
      line-height 24px
    h3, p, a, ul, li
      font-family Arial
    a
      color: #9db2ff
      text-decoration none
      font-weight bold

    p
      text-align left
    ul
      display flex
      flex-wrap wrap
      list-style none
      margin: 0
      padding: 0
      margin-bottom 15px
    li
      margin 5px
      margin-left: 0
      margin-right: 20px
      color: #c3c6c7
      font-size: 12px
  .landing
    color: #c3c6c7
    font-size: 12px
</style>
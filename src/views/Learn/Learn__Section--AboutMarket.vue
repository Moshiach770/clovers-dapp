<template lang="pug">
  about(v-on="$listeners")
    h3(slot="header") And you can sell it in the <b>Feed</b>
    img.block(slot="graphic", src="./imgs/market.svg", style="height:70vh;max-height:80vw;max-width:none")
</template>

<script>
import About from './Learn__Section--AboutACloverPage'
export default {
  name: 'LearnSectionAboutMarket',
  components: { About }
}
</script>

<style>
</style>

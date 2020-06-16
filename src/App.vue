<template>
  <div id="app">
    <Header />
	<InfoText />
	<ProductGrid />
  </div>
</template>

<script>

import Header from './components/Header.vue'
import InfoText from './components/InfoText.vue'
import ProductGrid from './components/ProductGrid.vue'

export default {
  name: 'App',
  components:
  {
	Header,
	InfoText,
	ProductGrid
  }
}
</script>

<style>
#app
{
	text-align: center;
	margin-top: 0px;
}
</style>

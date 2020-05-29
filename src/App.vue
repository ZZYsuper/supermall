<template>
  <div id="app" class="cart">
    <Header/>
    <Context/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/header'
import Context from './components/context'
import Footer from './components/footer'
export default {
  name: 'App',
  components: {
    Header, Context, Footer
  }
}
</script>

<style lang="scss">
.cart{
  width: 990px;
  margin: 30px auto;
}
</style>

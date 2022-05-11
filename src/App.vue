<template>  
  <Header />
  <Body />
  <Footer />

</template>

<script>
import Header from "./components/Header.vue"
import Body from "./components/Body.vue"
import Footer from "./components/Footer.vue"

export default {
name:'app',
components: {
  Header,
  Body,
  Footer,
}
}
</script>

<style>

</style>

<template>  
  <header-template />
  <body-template />
  <footer-template />

</template>

<script>
import HeaderTemplate from "./components/HeaderTemplate.vue"
import BodyTemplate from "./components/BodyTemplate.vue"
import FooterTemplate from "./components/FooterTemplate.vue"

export default {
name: 'App',
components: {
  HeaderTemplate,
  BodyTemplate,
  FooterTemplate,
  }
}
</script>

<style>

</style>

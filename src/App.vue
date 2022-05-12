<template>  
  <header-template />
  <div>
    <router-view/>
  </div>
  <footer-template />

</template>

<script>
import HeaderTemplate from "./components/HeaderTemplate.vue"
import FooterTemplate from "./components/FooterTemplate.vue"

export default {
name: 'App',
components: {
  HeaderTemplate,
  FooterTemplate,
  }
}
</script>

<style>

</style>


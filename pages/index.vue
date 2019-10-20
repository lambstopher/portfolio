<template>
  <div class="container">
    <div>
      
      <h1 class="title">
        Hi, I'm Chris
      </h1>
      <h2 class="subtitle">
        I'm a Web Developer interested in all technology that can be deployed on a webserver.
      </h2>
      <div class="links">
        <nuxt-link to="portfolio" class="button--green">View My Work</nuxt-link>
        <nuxt-link to="contact" class="button--green">Let's Talk</nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  head () {
    return {
      title: 'Home | Chris Lamb - Web Developer'
    }
  },
  components: {
    Logo
  }
}
</script>

<style>

</style>

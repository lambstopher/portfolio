<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">
        Hi, I'm Chris.
      </h1>
      <h2 class="subtitle">
        I'm a Web Developer.
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
  components: {
    Logo
  }
}
</script>

<style>

</style>

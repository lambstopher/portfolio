<template>
  <div class="container">
    <div>
      <h1 class="title">
        Portfolio
      </h1>
      <h2 class="subtitle">
        Stuff I've done.
      </h2>
      <div class="links">
        <nuxt-link to="portfolio/project1" class="button--green">project1</nuxt-link>
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

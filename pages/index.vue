<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">
        Hi, I'm Chris.
      </h1>
      <h2 class="subtitle">
        Step into my portfolio...
      </h2>
      <div class="links">
        <nuxt-link to="resume" class="button--green">Click Here</nuxt-link>
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

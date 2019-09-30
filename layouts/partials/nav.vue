<template>
  <header>
    <nuxt-link to="/" class="logo">CL</nuxt-link>
    <nav>
      <div class="nav-link-holder">
          <div class="nav-link"><nuxt-link to="/resume">Resume</nuxt-link></div>
          <div class="nav-link"><nuxt-link to="/portfolio">Portfolio</nuxt-link></div>
          <div class="nav-link"><nuxt-link to="/contact">Contact</nuxt-link></div>
      </div>
    </nav>
  </header>
</template>
<script>
export default {
}
</script>
<style>
  header {
      background: rgb(0, 000, 000);
      display: grid;
      grid-template-columns: repeat(2,auto);
  }
  .logo:hover, .nav-link a:hover {
      color: #41b883;
      text-decoration: none;
  }
  .logo, .nav-link a {
      padding: 1em 2em;
      display: block;
      text-transform: uppercase;
      text-decoration: none;
      font-weight: bold;
      color: white;
      font-size: .9em;
  }
  nav {
      justify-self: right;
  }
  .nav-link {
      display: inline;
  }
  .nav-link a {
      padding: 1em 2em;
      display: inline-block;
      background: rgba(0,0,0,0.1);
  }
  @media only screen and (max-width: 480px) {
    header {
      display: contents;
    }
    .logo {
      width: 20vw;
      background: #000;
    }
    nav {
      justify-self: center;
      position: fixed;
      bottom: 0px;
      width: 100%;
      background: #000;
    }
    .nav-link {
      padding: 0rem 0rem;
    }
    .nav-link a {
        width: 32vw;
        padding: 1em 0em 1em 0em;
        text-align: center;
    }
  }
</style>
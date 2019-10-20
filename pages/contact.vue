<template>
  <div class="container">
    <div>
      <h1 class="title">
        Let's Talk.
      </h1>
      <h2 class="subtitle">
        Fill out the form and I'll get back to you.
      </h2>
      <form name="contact" method="POST" data-netlify="true">
            <div class="contact-input"><input type="text" name="name" placeholder="Your Name" /></div>
            <div class="contact-input"><input type="email" name="email" placeholder="Your Email" /></div>
            <div class="contact-input"><textarea name="message" placeholder="What do you want to talk about?"></textarea></div>
            <div class="contact-input"><button type="submit" class="button--green">Send</button></div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  head () {
    return {
      title: 'Contact | Chris Lamb - Web Developer'
    }
  }
}
</script>

<style>
    .contact-input input, textarea {
        width: 100%;
        margin: 5px;
        padding: 15px;
        border-radius: 15px;
        border: 1px solid #8a8a8a;
    }
    .contact-input input:focus, textarea:focus {
        outline: none;
        border: 1px solid #41b883;
    }
</style>

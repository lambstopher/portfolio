<template>
  <div class="container">
    <div class="full-width">
    <div class="row">
      <div class="col-sm-12">
        <h1 class="title">
          Portfolio
        </h1>
        <h2 class="subtitle">
          Check out some of the brands and tools I've worked with. Please contact me for further details.
        </h2>
      </div>
    </div>
    <div class="row">
      <div class="col-lg-4 col-md-6">
        <div class="project-holder">
          <img class="project-image" src="../assets/images/whirlpool-logo.jpg" />
          <div class="project-details">
            <div class="project-title">Whirlpool</div>
            <p>Worked cross-functionally with marketing/IT teams to assist in the development, authoring and ongoing support of the whirlpool.com website.</p>
          </div>
        </div>
      </div>
      <div class="col-lg-4 col-md-6">
        <div class="project-holder">
          <img class="project-image" src="../assets/images/maytag-logo.jpg" />
          <div class="project-details">
            <div class="project-title">Maytag</div>
            <p>Worked cross-functionally with marketing/IT teams to assist in the development, authoring and ongoing support of the maytag.com website.</p>
          </div>
        </div>
      </div>
      <div class="col-lg-4 col-md-6">
        <div class="project-holder">
          <img class="project-image" src="../assets/images/kitchenaid-logo.jpg" />
          <div class="project-details">
            <div class="project-title">KitchenAid</div>
            <p>Worked cross-functionally with marketing/IT teams to assist in the development, authoring and ongoing support of the kitchenaid.com website.</p>
          </div>
        </div>
      </div>
      <div class="col-lg-4 col-md-6">
        <div class="project-holder">
          <img class="project-image" src="../assets/images/jennair-logo.jpg" />
          <div class="project-details">
            <div class="project-title">Jenn-Air</div>
            <p>Worked cross-functionally with marketing/IT teams to assist in the development, authoring and ongoing support of the jennair.com website.</p>
          </div>
        </div>
      </div>
      <div class="col-lg-4 col-md-6">
        <div class="project-holder">
          <img class="project-image" src="../assets/images/gladiator-logo.jpg" />
          <div class="project-details">
            <div class="project-title">Gladiator Garage Works</div>
            <p>Worked cross-functionally with marketing/IT teams to assist in the development, authoring and ongoing support of the gladiatorgarageworks.com website.</p>
          </div>
        </div>
      </div>
      <div class="col-lg-4 col-md-6">
        <div class="project-holder">
          <img class="project-image" src="../assets/images/amana-logo.jpg" />
          <div class="project-details">
            <div class="project-title">Amana</div>
            <p>Worked cross-functionally with marketing/IT teams to assist in the development, authoring and ongoing support of the amana.com website.</p>
          </div>
        </div>
      </div>
      <div class="col-lg-4 col-md-6">
        <div class="project-holder">
          <img class="project-image" src="../assets/images/aem-logo.jpg" />
          <div class="project-details">
            <div class="project-title">Adobe Experience Manager</div>
            <p>Assisted in multiple re-platforming projects to the AEM platform. Proficient in <b>authoring</b> and <b>front-end AEM development</b>. Worked extensively with <b>AEM DAM</b> in an asset migration project.</p>
          </div>
        </div>
      </div>
      <div class="col-lg-4 col-md-6">
        <div class="project-holder">
          <img class="project-image" src="../assets/images/nuxtjs-logo.jpg" />
          <div class="project-details">
            <div class="project-title">NuxtJS</div>
            <p>Worked with static site generator <b>NuxtJS</b> and <b>Vue</b> to create light weight web applications. Deployed applications through <b>Netlify</b>. This portfolio is an example of one of these projects.</p>
          </div>
        </div>
      </div>
      <div class="col-lg-4 col-md-6">
        <div class="project-holder">
          <img class="project-image" src="../assets/images/target-logo.jpg" />
          <div class="project-details">
            <div class="project-title">Adobe Target</div>
            <p>Have deployed dozens of <b>A/B</b> and <b>experience targed</b> tests using AT. Created clean/reusable code that effectively manipulates the DOM while not impacting performance.</p>
          </div>
        </div>
      </div>
    </div>
    </div>
  </div>
</template>

<script>
export default {
  head () {
    return {
      title: 'Portfolio | Chris Lamb - Web Developer'
    }
  }
}
</script>

<style>
  .project-holder {
    height: 250px;
  }
  .project-holder img {
    width: 250px;
    margin: 0 auto;
  }
  .full-width {
    width: 100%;
  }
  .project-details {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    height: 100%;
    width: 100%;
    opacity: 0;
    transition: .5s ease;
    background-color: #afe8cf;
  }
  .project-holder:hover .project-details {
    opacity: 1;
  }
  .project-title {
    font-weight: bold;
    color: #000;
    padding: 10px;
    font-size: 1.3rem;
  }
  .project-image {
    display: block;
    width: 100%;
    height: auto;
  }
  .project-details p {
    color: #000;
    padding: 0 1rem;
    text-align: left;
  }
</style>

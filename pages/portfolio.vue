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
      <div class="col-sm-4">
        <div class="project-holder">
          <img class="project-image" src="../assets/images/whirlpool-logo.jpg" />
          <div class="project-details">
            <div class="project-title">Whirlpool</div>
            <p>Lorum Ipsum text text text text</p>
          </div>
        </div>
      </div>
      <div class="col-sm-4">
        <div class="project-holder">
          <img class="project-image" src="../assets/images/maytag-logo.jpg" />
          <div class="project-details">
            <div class="project-title">Maytag</div>
            <p>Lorum Ipsum text text text text</p>
          </div>
        </div>
      </div>
      <div class="col-sm-4">
        <div class="project-holder">
          <img class="project-image" src="../assets/images/kitchenaid-logo.jpg" />
          <div class="project-details">
            <div class="project-title">KitchenAid</div>
            <p>Lorum Ipsum text text text text</p>
          </div>
        </div>
      </div>
      <div class="col-sm-4">
        <div class="project-holder">
          <img class="project-image" src="../assets/images/jennair-logo.jpg" />
          <div class="project-details">
            <div class="project-title">Jenn-Air</div>
            <p>Lorum Ipsum text text text text</p>
          </div>
        </div>
      </div>
      <div class="col-sm-4">
        <div class="project-holder">
          <img class="project-image" src="../assets/images/gladiator-logo.jpg" />
          <div class="project-details">
            <div class="project-title">Gladiator Garage Works</div>
            <p>Lorum Ipsum text text text text</p>
          </div>
        </div>
      </div>
      <div class="col-sm-4">
        <div class="project-holder">
          <img class="project-image" src="../assets/images/amana-logo.jpg" />
          <div class="project-details">
            <div class="project-title">Amana</div>
            <p>Lorum Ipsum text text text text</p>
          </div>
        </div>
      </div>
      <div class="col-sm-4">
        <div class="project-holder">
          <img class="project-image" src="../assets/images/aem-logo.jpg" />
          <div class="project-details">
            <div class="project-title">Adobe Experience Manager</div>
            <p>Lorum Ipsum text text text text</p>
          </div>
        </div>
      </div>
      <div class="col-sm-4">
        <div class="project-holder">
          <img class="project-image" src="../assets/images/aem-logo.jpg" />
          <div class="project-details">
            <div class="project-title">Adobe DAM</div>
            <p>Lorum Ipsum text text text text</p>
          </div>
        </div>
      </div>
      <div class="col-sm-4">
        <div class="project-holder">
          <img class="project-image" src="../assets/images/target-logo.jpg" />
          <div class="project-details">
            <div class="project-title">Adobe Target</div>
            <p>Lorum Ipsum text text text text</p>
          </div>
        </div>
      </div>
    </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {

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
    background-color: #41b883;
  }
  .project-holder:hover .project-details {
    opacity: 1;
  }
  .project-title {
    font-weight: bold;
    color: #fff;
    padding: 10px;
    font-size: 1.3rem;
  }
  .project-image {
    display: block;
    width: 100%;
    height: auto;
  }
  .project-details p {
    color: #fff;
  }
</style>

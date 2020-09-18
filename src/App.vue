<template>
  <div id="app">
    <div id="banner">
      <b-carousel
        fade
        id="carousel-fade"
        :interval="8000"
        style="text-shadow: 0px 0px 2px #000"
        img-width="100%"
        img-height="480px"
      >
        <b-carousel-slide
          caption-html="
            <h3 class='mh1 slide-hdr'>Lightweight, Portable, Efficient</h3>
            <h6 class='mh2 slide-sub-hdr'>pyShelf goes anywhere you can deploy a docker image</h5>
          "
          img-src="./assets/slide-home-no-blur.png"
        ></b-carousel-slide>
        <b-carousel-slide
          caption-html="
            <h3 class='mh1 slide-hdr'>Powered By Python</h1>
            <h6 class='mh2 slide-sub-hdr'>A vibrant and diverse eco-system, combined with sensible syntax made Python no-brainer for pyShelf</h6>
          "
          img-src="./assets/slide-dev-screenshot-no-blur.png"
        ></b-carousel-slide>
        <b-carousel-slide
          caption-html="
            <h3 class='mh1 slide-hdr'>Enjoying pyShelf?</h1>
            <h6 class='mh2 slide-sub-hdr'>Consider Sponsoring On GitHub!</h6>
          "
          img-src="./assets/slide-githubsponsors-no-blur.png"
        ></b-carousel-slide>
        <div id="top-bar" class="d-flex justify-content-between">
          <div id="branding" class="p2">
            <div class="d-flex flex-column">
              <div id="site-title" class="text-left">
                <h3 class="primary site-title">pyShelf</h3>
              </div>
              <div class="pl-1 justify-text-top"><h6 class="font-weight-light site-slogan">Open Source EBook Server</h6></div>
            </div>
          </div>
          <div id="nav" class="pr-1 align-items-center mt-auto mb-auto">
            <div class="mt-0 sticky-top p2">
              <b-button-group size="md">
                <router-link to="/">
                  <b-button size="sm" class="site-nav">
                    <b-icon icon="house-door" aria-hidden="true"></b-icon> Home
                  </b-button>
                </router-link>
                <router-link to="/download">
                  <b-button size="sm" class="site-nav">
                    <b-icon icon="download" aria-hidden="true"></b-icon> Download
                  </b-button>
                </router-link>
                <b-button size="sm" class="site-nav">
                  <!--<router-link to="/download">-->
                  <b-icon icon="hdd-rack" aria-hidden="true"></b-icon> Get
                  Involved
                  <!--</router-link>-->
                </b-button>
              </b-button-group>
            </div>
          </div>
        </div>
      </b-carousel>
    </div>
    <router-view />
    <div class="footer-container">
    </div>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #000;
}
#banner {
  background-size: cover;
  background-blend-mode: luminosity;
  background-color: #0000008c;
  border-bottom: 10px solid #00000070;
  border-top: 10px solid #00000070;
  margin-bottom: 0px;
}
#top-bar {
  //background-image: url("assets/blue-background.jpg");
  background-color: #000000bd;
  color: silver;
  //opacity: 90%;
  position: fixed;
  top: 0px;
  min-width: 100%;
  z-index: 1;
}
#nav {
  padding: 0px;

  a {
    font-weight: bold;
    color: #ffffff;

    &.router-link-exact-active {
      color: #000000;
    }
  }
}
.site-nav {
  background-color: #343a40;
}
.carousel-item {
  height: 480px;
  width: 100%;
}
.img-fluid {
  max-width: 100%;
  height: max-content;
}
</style>

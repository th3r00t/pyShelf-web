<template xmlns:a="http://www.w3.org/1999/html">
  <div class="outwrap">
    <div class="section first-section">
      <div class="section-intro">
        <h6 class="primary section-hdr">Feature Overview</h6>
        <h3 class="section-sub-hdr">pyShelf is constantly evolving</h3>
      </div>
      <div class="section-container">
        <b-container fluid="lg">
          <b-row align-v="top" align-h="center" cols="4">
            <b-col>
              <div class="highlight-box">
                <div class="highlight-inner">
                  <img class="highlight-image" src="@/assets/docker.png"/>
                  <div class="highlight-caption">
                    <h5 class="primary">You asked for it</h5> It's here. pyShelf has been redesigned with Docker in mind
                  </div>
                </div>
              </div>
            </b-col>
            <b-col>
              <div class="highlight-box">
                <div class="highlight-inner">
                  <img class="highlight-image" src="@/assets/home-example.png"/>
                  <div class="highlight-caption">
                    <h5 class="primary">Web Based Interface</h5>
                    Use pyShelf anywhere.
                  </div>
                </div>
              </div>
            </b-col>
            <b-col>
              <div class="highlight-box">
                <div class="highlight-inner">
                  <img class="highlight-image" src="@/assets/responsive-ui.png"/>
                  <div class="highlight-caption">
                    <h5 class="primary">Responsive U/X</h5>
                    pyShelf is fully responsive, use it on any device
                  </div>
                </div>
              </div>
            </b-col>
            <b-col>
              <div class="highlight-box">
                <div class="highlight-inner">
                  <img class="highlight-image" src="@/assets/navbar.png"/>
                  <div class="highlight-caption">
                    <h5 class="primary">Streamlined U/I</h5>
                    The interface has been redesigned for a more informative, less intrusive user experience.
                  </div>
                </div>
              </div>
            </b-col>
            <b-col>
              <div class="highlight-box">
                <div class="highlight-inner">
                  <img class="highlight-image" src="@/assets/cli-preview.png"/>
                  <div class="highlight-caption">
                    <h5 class="primary">T.U.I</h5>
                    Terminal User Interface, pyShelf can be run as a headless service, no X server needed.
                  </div>
                </div>
              </div>
            </b-col>
            <b-col>
              <div class="highlight-box">
                <div class="highlight-inner">
                  <img class="highlight-image" src="@/assets/book-description.png"/>
                  <div class="highlight-caption">
                    <h5 class="primary">Metadata Retrieval</h5>
                    We do our best to retrieve your books metadata.
                  </div>
                </div>
              </div>
            </b-col>
            <b-col>
              <div class="highlight-box">
                <div class="highlight-inner">
                  <img class="highlight-image" src="@/assets/book-details.png"/>
                  <div class="highlight-caption">
                    <h5 class="primary">Detailed View</h5>
                    Want more details before choosing a book? Click the info button.
                  </div>
                </div>
              </div>
            </b-col>
            <b-col>
              <div class="highlight-box">
                <div class="highlight-inner">
                  <img class="highlight-image" src="@/assets/django.png"/>
                  <div class="highlight-caption">
                    <h5 class="primary">Django Driven</h5>
                    When you need a dependable frontend framework look no further.
                  </div>
                </div>
              </div>
            </b-col>
          </b-row>
        </b-container>
      </div>
    </div>
    <div class="section">
      <div class="section-container">
        <b-container>
          <b-row align-v="top" align-h="center">
            <b-col>
              <div class="ad-box">
                <div class="highlight-inner">
                  <p>get started</p>
                  <p>pyShelf is hosted on GitHub</p>
                  <img src="@/assets/GitHub-Mark-64px.png" /><img src="@/assets/GitHub_Logo.png" width="320px"/><br />
                </div>
              </div>
            </b-col>
            <b-col>
              <div class="ad-box">
                <p>donate to pyShelf</p>
                <p>Consider Sponsoring pyShelf on github to help with development</p>
                <img src="@/assets/githubsponsors.png" width="320px" /><br />
              </div>
            </b-col>
            <b-col>
              <div class="ad-box">
                <p>get involved</p>
                <p>join us on discord</p>
                <img src="@/assets/discord_logo_color.png" width="320px" /><br />
              </div>
            </b-col>
          </b-row>
        </b-container>
      </div>
      <div>
      </div>
      <div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FrontPage",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>

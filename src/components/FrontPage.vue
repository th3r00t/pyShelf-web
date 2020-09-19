<template xmlns:a="http://www.w3.org/1999/html">
  <div class="outwrap">
    <div class="section first-section">
      <div class="section-intro">
        <h6 class="primary section-hdr">Feature Overview</h6>
        <h3 class="section-sub-hdr mh1">pyShelf is constantly evolving</h3>
      </div>
      <div class="section-container">
        <b-container fluid="lg">
          <b-row align-v="top" align-h="center" cols-lg="4" cols-md="2" cols-sm="1">
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
    <div class="section second-section">
      <div class="section-container" id="download">
        <b-container>
          <b-row align-v="top" align-h="center" cols-md="2" cols-sm="1">
            <b-col>
              <b-container class="ad-box">
                <a href="https://github.com/th3r00t/pyShelf">
                <h3 class="sh1">get started</h3>
                <p>pyShelf is hosted on GitHub</p>
                <img src="@/assets/GitHub-Mark-64px.png" /><img src="@/assets/GitHub_Logo.png" width="220px"/>
                </a>
              </b-container>
            </b-col>
            <b-col>
              <b-container class="ad-box">
                <a href="https://discord.gg/H9TbNJS">
                <h3 class="sh1">get involved</h3>
                <p>join us on discord</p>
                <img src="@/assets/discord_logo_color.png" width="220px" />
                </a>
              </b-container>
            </b-col>
          </b-row>
        </b-container>
      </div>
      <div class="section third-section">
        <div class="section-container">
          <b-container class="ad-box">
            <b-row>
              <b-col>
                <h3 class="sh1">donate to pyShelf</h3>
                <p class="quote">pyShelf is a Free and Open Source project with one full time developer,
                and a small supporting staff on discord, if you find pyShelf useful consider sponsoring
                on github, or make a one time donation via paypal to help with development. Every little
                bit helps!
                </p>
                <b-table-simple hover small caption-top responsive>
                  <caption>SLOC generated using David A. Wheeler's 'SLOCCount'</caption>
                  <colgroup><col><col><col></colgroup>
                  <b-thead head-variant="light">
                    <b-tr>
                      <b-th>SLOC</b-th><b-th>Directory</b-th><b-th>by-lang</b-th>
                    </b-tr>
                  </b-thead>
                  <b-tbody>
                    <b-tr>
                      <b-td>678</b-td><b-td>src/</b-td><b-td>python 678</b-td>
                    </b-tr>
                    <b-tr>
                      <b-td>560</b-td><b-td>src/lib</b-td><b-td>python 560</b-td>
                    </b-tr>
                    <b-tr>
                      <b-td colspan="3">Totals by language</b-td>
                    </b-tr>
                    <b-tr>
                      <b-td colspan="2">python</b-td><b-td colspan="1">1238</b-td>
                    </b-tr>
                    <b-tr>
                      <b-td colspan="2">Total Physical Lines of Code (SLOC)</b-td><b-td colspan="1">1238</b-td>
                    </b-tr>
                    <b-tr>
                      <b-td colspan="2">Total Estimated Cost to Develop</b-td><b-td colspan="1">$ 33,806</b-td>
                    </b-tr>
                  </b-tbody>
                </b-table-simple>
              </b-col>
            </b-row>
            <b-row>
              <b-col>
                <b-container>
                  <b-row>
                    <b-col>
                      <iframe src="https://github.com/sponsors/th3r00t/button" title="Sponsor th3r00t" height="35" width="116" style="border: 0;"></iframe>
                    </b-col>
                    <b-col>
                      <a href="https://www.patreon.com/bePatron?u=42571126" data-patreon-widget-type="become-patron-button">Become a Patron!</a>
                    </b-col>
                    <b-col>
                      <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
                        <input type="hidden" name="cmd" value="_s-xclick" />
                        <input type="hidden" name="hosted_button_id" value="3SH4A3XATY8VW" />
                        <input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif" border="0" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Donate with PayPal button" />
                        <img alt="" border="0" src="https://www.paypal.com/en_US/i/scr/pixel.gif" width="1" height="1" />
                      </form>
                    </b-col>
                  </b-row>
                  <b-row>
                  </b-row>
                </b-container>
              </b-col>
            </b-row>
          </b-container>
        </div>
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

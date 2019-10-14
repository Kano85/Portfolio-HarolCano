<template>
<v-container grid-list-lg>
  <v-layout row>
    <v-flex xs12 class="text-xs-center display-1 font-weight-black my-5">Projects and Works</v-flex>
  </v-layout>
  <v-layout row wrap class="meal-plans">
    <!-- <v-flex xs12 sm12 md4>
        <v-card>
          <v-responsive>
            <img src="~@/assets/voronoi-a.jpg" height="500px">
            <v-container fill-height fluid>
              <v-layout fill-height>
                <v-flex xs12 align-end flexbox>
                  <span class="headline white--text">Project 1</span>
                </v-flex>
              </v-layout>
            </v-container>
          </v-responsive>

          <v-card-text>
            <div>
              <h3 class="headline mb-0">Project 1</h3>
              <div>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
              </div>
            </div>
          </v-card-text>

          <v-card-actions>
            <v-btn outline block color="green" @click="showRecipes('keto')" data-cy="plansKetoBtn">Select This Project</v-btn>
          </v-card-actions>
        </v-card>
      </v-flex> -->
    <v-flex xs12 sm12 md4>
      <!-- <v-card>
          <v-responsive>
            <img src="~@/assets/voronoi-b.jpg" height="500px">
            <v-container fill-height fluid>
              <v-layout fill-height>
                <v-flex xs12 align-end flexbox>
                  <span class="headline white--text">Project 2</span>
                </v-flex>
              </v-layout>
            </v-container>
          </v-responsive>

          <v-card-text>
            <div>
              <h3 class="headline mb-0">Project 2</h3>
              <div>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
              </div>
            </div>
          </v-card-text>

          <v-card-actions>
            <v-btn outline block color="green" @click="showRecipes('keto')" data-cy="plansKetoBtn">Select This Project</v-btn>
          </v-card-actions>
        </v-card> -->
      <v-card>
        <v-responsive>
          <img src="~@/assets/portfolio.png" height="500px" />
          <v-container fill-height fluid>
            <v-layout fill-height>
              <v-flex xs12 align-end flexbox> </v-flex>
            </v-layout>
          </v-container>
        </v-responsive>

        <v-card-text>
          <div>
            <h3 class="headline mb-0">Portfolio Code</h3>
            <span class="headline white--text">Project 4</span>
            <div>
              Firebase <br />
              Axios <br />
              Vuetify <br />
              Vuex <br />
            </div>
          </div>
        </v-card-text>

        <v-card-actions>
          <v-btn href="https://github.com/Kano85/landing-page-haroldcano.git" text>git hub
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>

    <v-flex xs12 sm12 md4>
      <v-card>
        <v-responsive>
          <img src="" height="500px" />
          <img src="~@/assets/kugu-app.dummy.png" height="500px" />
          <v-container fill-height fluid>
            <v-layout fill-height>
              <v-flex xs12 align-end flexbox>

              </v-flex>
            </v-layout>
          </v-container>
        </v-responsive>

        <v-card-text>
          <div>
            <h3 class="headline mb-0">Kugu Dashboard Dummy</h3>
            <span class="headline white--text">Project 5</span>
            <div>
              Vue.js <br />
              Iframe <br />
              Node.js <br />
              Basic CSS - HTML <br />
            </div>
          </div>
        </v-card-text>

        <v-card-actions>
          <v-btn href="http://projekte.pages.kugu.cloud/submetering-portal-frame/" outline block color="green" @click="showRecipes('paleo')" data-cy="plansPaleoBtn">
            Preview Weblink</v-btn>
          <v-btn text>git hub </v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>

    <v-flex xs12 sm12 md4>
      <v-card>
        <v-responsive>
          <img src="~@/assets/kugu-app.png" height="500px" />
          <v-container fill-height fluid>
            <v-layout fill-height>
              <v-flex xs12 align-end flexbox>
              </v-flex>
            </v-layout>
          </v-container>
        </v-responsive>

        <v-card-text>
          <div>
            <h3 class="headline mb-0">
              Kugu Dashboard Rest API
            </h3>
            <span class="headline white--text">Project 6</span>
            <div>
              Vue.js <br />
              Element.io <br />
              Node.js <br />
              Axios <br />
            </div>
          </div>
        </v-card-text>

        <v-card-actions>
          <v-btn href="http://projekte.pages.kugu.cloud/billing-gui/#/Uebersicht" outline block color="green" @click="showRecipes('vegan')" data-cy="plansVeganBtn">
            Preview Weblink
          </v-btn>
          <v-btn href="https://github.com/Kano85/landing-page-haroldcano.git" text>git hub
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
    <v-flex xs12 sm12 md4>
      <v-card>
        <v-responsive>
          <img src="~@/assets/Poster.png" height="500px" />
          <v-container fill-height fluid>
            <v-layout fill-height>
              <v-flex xs12 align-end flexbox>
              </v-flex>
            </v-layout>
          </v-container>
        </v-responsive>

        <v-card-text>
          <div>
            <h3 class="headline mb-0">
              Graphic Design HU-Berlin
            </h3>
            <span class="headline white--text">Project 3</span>
            <div>
              Illustrator <br />
              InDesign <br />
              Photoshop <br />
            </div>
          </div>
        </v-card-text>
        <v-card-actions>
          <v-btn href="https://drive.google.com/file/d/1M2AY5MPx1tsYDbOrJ5DCQ2Be4fSPhtJS/view?ts=5da395de" text>
            Poster
          </v-btn>
          <v-btn href="https://drive.google.com/file/d/18-Y75eTDoo1s7BI2VcZ58YLg001bIO8D/view?usp=sharing" text>
            Program
          </v-btn>
          <v-btn href="https://drive.google.com/file/d/1RctVLH1gTgEhRW2T98fNwwzjETA65oYh/view?usp=sharing" text>
            Certificate
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
    <v-flex xs12 sm12 md4></v-flex>
  </v-layout>
</v-container>
</template>

<script>
export default {
  name: 'HomePlans'
  // ,
  // methods: {
  //     showRecipes(plan) {
  //         this.$store.dispatch('getRecipes', plan);
  //     }
  // }
};
</script>

<style scoped></style>

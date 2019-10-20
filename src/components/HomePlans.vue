

<template>
<v-container grid-list-lg>
  <v-layout row>
    <div class="display-4 font-weight-black black--text text-xs-center">
      Projects
    </div>
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
      <v-card>
        <v-responsive>
          <img src="~@/assets/portfolio1.png" height="500px" />
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
              Vue.js <br />
              Vuetify <br />
              Vuex <br />
            </div>
          </div>
        </v-card-text>

        <v-card-actions>
          <v-btn href="https://github.com/Kano85/Portfolio-HarolCano.git" text>git hub
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
              <v-flex xs12 align-end flexbox> </v-flex>
            </v-layout>
          </v-container>
        </v-responsive>

        <v-card-text>
          <div>
            <h3 class="headline mb-0">Kugu Dashboard Dummy</h3>
            <span class="headline white--text">Project 5</span>
            <div>
              Iframe <br />
              Node.js <br />
              Basic CSS - HTML <br />
              <br />
              The active links are under the aside menu ./Übersicht and ./Liegenschaften/Straßburger Str.9F

            </div>
          </div>
        </v-card-text>

        <v-card-actions>
          <v-btn href="https://billing-gui-git.firebaseapp.com" outline block color="green" @click="showRecipes('paleo')" data-cy="plansPaleoBtn">
            Preview Weblink</v-btn>
          <v-btn href="https://github.com/Kano85/submetering.git" text>git hub </v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>

    <v-flex xs12 sm12 md4>
      <v-card>
        <v-responsive>
          <img src="~@/assets/kugu-app.png" height="500px" />
          <v-container fill-height fluid>
            <v-layout fill-height>
              <v-flex xs12 align-end flexbox> </v-flex>
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
              <br />
              The active router links are in the aside-menu ./Liegenschafts and ./Casavi<br />
              The different data is uploaded under ./casavi but disconnected, take a look at the code.<br />
            </div>
          </div>
        </v-card-text>

        <v-card-actions>
          <v-btn href="https://billing-gui.firebaseapp.com" outline block color="green" @click="showRecipes('vegan')" data-cy="plansVeganBtn">
            Preview Weblink
          </v-btn>
          <v-btn href="https://github.com/Kano85/billing-gui-git.git" text>git hub
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
              <v-flex xs12 align-end flexbox> </v-flex>
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
    <v-flex xs12 sm12 md4>
      <v-card>
        <v-responsive>
          <img src="~@/assets/adobexd.png" height="500px">
          <v-container fill-height fluid>
            <v-layout fill-height>
            </v-layout>
          </v-container>
        </v-responsive>

        <v-card-text>
          <div>
            <h3 class="headline mb-0">Wireframes with Adobe XD.</h3>
            <span class="headline white--text">Project 3</span>
            <div>
              These are some examples of the projects that have resulted from the user Reasearch sessions
            </div>
          </div>
        </v-card-text>

        <v-card-actions>
          <v-btn href="https://drive.google.com/open?id=1gNmWA-UPxWDaM74RDsa1br8qY2XVHpas" text>
            Project1.xd
          </v-btn>
          <v-btn href="https://drive.google.com/open?id=1rroR7iC0HwzJJY-bDrCwpgkbO8IXciXl" text>
            Porject2.xd
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
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

<style scoped>
.display-4 {
  text-align: center;
  margin-bottom: 5vh;
}
.headline {
  font-weight: bold;
}
</style>

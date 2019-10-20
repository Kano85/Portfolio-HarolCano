<template>
<v-container fluid class="lighten-4">
  <v-container grid-list-lg>
    <v-layout column>
      <v-flex>
        <div class="custom-selector display-4 font-weight-black white--text text-xs-left">
          About Me
        </div>
        <div class="display-1">
          Who I am
        </div>

        <p class="subheading mt-3">
          I am Harold, a Designer based in Berlin. What I most
          like about what I do is the creative processes the work
          in Design areas enables. I never stop learning and
          constantly find myself on a journey of exploring the
          numerous directions Design can offer.
        </p>
      </v-flex>
      <v-flex>
        <div class="display-1">
          So here’s my journey:
        </div>
        <p class="subheading mt-3">
          Barcelona and my university degree in Product Design
          marked the starting point. During my studies I developed
          a passion for 3D-Modeling and 3D-Printing and continued
          my journey to Berlin, where I engaged in several
          projects and built my own 3D-Printers. Later, I realised
          there is much more to explore as a Product Designer. So
          I traveled further to dip into a new territory - UX/UI
          and Web-Development. To get there I have trained myself
          further in several courses and a lot of self-study. I
          studied the basic tools of Graphic Design and
          transformed the theory into practice by designing
          promotional material of different kinds for a symposium
          at Humboldt-University of Berlin. As I had developed
          enthusiasm for this “digital” art of design, I wanted to
          gain more knowledge and thus, educated myself in the
          field of Web- and App-Development. Over the last couple
          of months I have acquired practical experience working
          at Kugu Home GmbH. There, I have been developing apps
          and improving my programming skills.
        </p>

        <p class="subheading mt-3">
          With UX/UI Design and Web Development, I believe to have
          reached a suitable area for me to settle. What makes
          this area so special in my eyes is that I can always
          involve design components when programming and produce a
          more creative outcome. This is the reason why I believe
          UX/UI fits to me so perfectly - it creates a bridge
          between classic Product Design and Web-Programming.
        </p>

        <p class="subheading mt-3"></p>
      </v-flex>
      <v-flex>
        <p class="subheading mt-3">
          Please find below a list of IT-Tools I am familiar with,
          some insights into my projects and my contact details.
        </p>
        <div class="display-1">
          IT Knowledge
        </div>
        <div class="it">
        <h2>Programming languages</h2>

          HTML5, CSS3<br />
          Modern JavaScript ES6 (Basics)<br />
          Vue.js including rest API, libraries and components<br />

          <h2>Graphic design</h2>

          Illustrator, InDesign<br />
          Whimsical (used for Research)<br />
          Adobe XD, FIGMA (used for Wireframes, User flow)<br />

          <h2>3D-Design and 3D Printing</h2>

          Solidworks 2015<br />
          Rhino 6 (Grasshoper)<br />
          Netfabb<br />
          Slic3r, Cura for 3D Printing optimization FDM<br />
          Basic VRAY<br />
        </div>

        <div class="notice display-1">
          I am currently looking for new projects and challenges.<br />
          Reach out to me to connect!<br />
        </div>
      </v-flex>
    </v-layout>
  </v-container>
</v-container>
</template>

<script>
export default {
  name: 'HomeDetails'
};
</script>

<style scoped>

h2 {
  margin-top: 3vh;
  color: white;
}

.lighten-4 {
  background-color: #1976D2;
}

.display-1 {
  margin-top: 3vh;
  font-weight: bold;
  color: white;
}
p {
  color: white;
}
.it {
  color: white;
}
.notice  {
  text-align: center !important;
  margin-left: 0vh !important;
  margin-right: 0vh !important;
}

@media only screen and (min-width: 1900px) {

p {
  margin-left: 40vh;
  margin-right: 40vh;
  }
.display-1 {
  margin-left: 30vh;
 }
.it {
  margin-left: 30vh;
}
.subheading {
  margin-left: 30vh;
}
}
</style>

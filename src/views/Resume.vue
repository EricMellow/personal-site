<template>
  <div class="container-div hero-image">
    <h2 class="sub-head">Résumé</h2>
    <v-expansion-panels class="panels-fix" focusable>
      <v-expansion-panel>
        <v-expansion-panel-header class="exp-header">Skills</v-expansion-panel-header>
        <v-expansion-panel-content class="exp-content">
          <ul>
            <li>Angular</li>
            <li>React/Redux/Router</li>
            <li>Vue</li>
            <li>JavaScript/Typescript</li>
            <li>HTML5</li>
            <li>CSS3</li>
            <li>Python</li>
            <li>Node.js/Express.js</li>
            <li>Git/GitHub</li>
            <li>Testing suites (Jest, Mocha/Chai)</li>
            <li>WAI-ARIA</li>
            <li>Photoshop</li>
            <li>RESTful API development</li>
            <li>Agile workflow</li>
          </ul>
        </v-expansion-panel-content>
      </v-expansion-panel>

      <v-expansion-panel>
        <v-expansion-panel-header class="exp-header">Experience</v-expansion-panel-header>
        <v-expansion-panel-content class="exp-content">
          <div>
            <h3 class="companies">BDS Analytics</h3>
            <h5 class="dates">January 2020 - Present</h5>
            <p>
              Working on creating new front end versions of both internal and
              customer-facing web apps, while also doing some work to update
              legacy code to use modern and/or more efficient programming
              techniques. Everything is expected to be responsive to ensure
              performance on both mobile and desktop environments. I am
              documenting and unit testing the code that I deliver, as well as
              fixing any bugs as they arise. This is all done within an Agile
              development process and I am expected to make sure timelines
              and deliverables are met. Essential technologies used:
            </p>
            <ul style="margin-bottom: 15px;">
              <li>Vue</li>
              <li>Jest</li>
            </ul>
          </div>
          <v-divider style="margin: 20px 0; background-color: white;"></v-divider>
          <div>
            <h3 class="companies">Charter Communications</h3>
            <h5 class="dates">August 2018 - January 2020</h5>
            <p>
              Working on the Advanced Engineering team I helped create an
              automation application for the network engineers, allowing them to
              go from manually auditing and configuring one router at a time to
              being able to push configurations to thousands of routers at once.
              Essential technologies used:
            </p>
            <ul>
              <li>Angular</li>
              <li>Typescript</li>
              <li>GraphQL</li>
            </ul>
          </div>
        </v-expansion-panel-content>
      </v-expansion-panel>

      <v-expansion-panel>
        <v-expansion-panel-header class="exp-header">Education</v-expansion-panel-header>
        <v-expansion-panel-content class="exp-content">
          <div>
            <h3 class="schools">Turing School of Software & Design</h3>
            <h5 class="studies">Front End Engineering</h5>
            <h5 class="location">Denver, CO</h5>
          </div>
          <v-divider style="margin: 20px 0; background-color: white;"></v-divider>
          <div>
            <h3 class="schools">University of Nebraska</h3>
            <h5 class="studies">BS in English Theory & Criticism</h5>
            <h5 class="studies">Minor in Philosophy</h5>
            <h5 class="location">Lincoln, NE</h5>
          </div>
        </v-expansion-panel-content>
      </v-expansion-panel>
    </v-expansion-panels>
  </div>
</template>

<style scoped>
.hero-image {
  background-image: url("../assets/arrow.jpg");
  height: 100%;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.sub-head {
  color: #3ecbbe;
  font-weight: 400;
  text-align: center;
  padding: 10px;
  font-size: 3rem;
  font-family: sofia-pro, sans-serif;
  -webkit-text-stroke: 1.5px #3ecbbe;
  text-stroke: 1.5px #3ecbbe;
  -webkit-text-fill-color: transparent;
  text-fill-color: transparent;
  color: transparent;
  transition: opacity 0.4s;
}

.container-div {
  height: 100%;
  background-color: black;
  display: flex;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: flex-start;
}

.panels-fix {
  width: 50vw;
  margin-top: 100px;
  margin-bottom: 25px;
}

.exp-header {
  font-size: 2rem;
  height: 75px;
  color: #3ecbbe;
  background-color: #272727;
}

.dates {
  font-weight: 400;
  margin-bottom: 10px;
  font-size: 1rem;
}

.companies {
  font-weight: 400;
  font-size: 2rem;
}

.schools {
  font-size: 2rem;
  font-weight: 300;
}

.studies {
  font-weight: 400;
  font-size: 1.25rem;
}

.location {
  font-weight: 300;
  font-size: 1.25rem;
}

/deep/
  .theme--light.v-expansion-panels
  .v-expansion-panel-header
  .v-expansion-panel-header__icon
  .v-icon {
  color: #3ecbbe;
}

/deep/
  .theme--light.v-expansion-panels.v-expansion-panels--focusable
  .v-expansion-panel-header:hover::before {
  opacity: 0.1;
  color: white;
}

/deep/
  .theme--light.v-expansion-panels.v-expansion-panels--focusable
  .v-expansion-panel-header--active:hover::before,
.theme--light.v-expansion-panels.v-expansion-panels--focusable
  .v-expansion-panel-header--active::before {
  opacity: 0.1;
  color: #fff;
}

.exp-content {
  color: white;
  background-color: #272727;
}

ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

li {
  padding-left: 1em;
  text-indent: -1em;
}

li::before {
  content: "• ";
  color: #3ecbbe;
  font-size: 18px;
}
</style>
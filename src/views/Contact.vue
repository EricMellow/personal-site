<template>
  <div class="container-div hero-image">
    <h2 class="sub-head">Contact</h2>
    <v-card
      class="card-dark btn-border"
      style="background-color: #272727; color: white;"
      transition="scale-transition"
      origin="center center"
    >
      <v-card-title>
        <svg class="svg-style" viewBox="0 0 24 24">
          <path
            fill="#3ecbbe"
            d="M6,17C6,15 10,13.9 12,13.9C14,13.9 18,15 18,17V18H6M15,9A3,3 0 0,1 12,12A3,3 0 0,1 9,9A3,3 0 0,1 12,6A3,3 0 0,1 15,9M3,5V19A2,2 0 0,0 5,21H19A2,2 0 0,0 21,19V5A2,2 0 0,0 19,3H5C3.89,3 3,3.9 3,5Z"
          />
        </svg>Eric Jungbluth
      </v-card-title>
      <v-card-text>
        <p class="info">
          <svg class="svg-style" viewBox="0 0 24 24">
            <path
              fill="#3ecbbe"
              d="M20,8L12,13L4,8V6L12,11L20,6M20,4H4C2.89,4 2,4.89 2,6V18A2,2 0 0,0 4,20H20A2,2 0 0,0 22,18V6C22,4.89 21.1,4 20,4Z"
            />
          </svg>
          <a href="mailto:eric.j.jungbluth@gmail.com">Eric.J.Jungbluth@gmail.com</a>
        </p>
        <p style="color: rgba(255, 255, 255, 0.6);" class="info">
          <svg class="svg-style" viewBox="0 0 24 24">
            <path
              fill="#3ecbbe"
              d="M17,19H7V5H17M17,1H7C5.89,1 5,1.89 5,3V21A2,2 0 0,0 7,23H17A2,2 0 0,0 19,21V3C19,1.89 18.1,1 17,1Z"
            />
          </svg>402.890.3223
        </p>
        <p class="info">
          <svg class="svg-style" viewBox="0 0 24 24">
            <path
              fill="#3ecbbe"
              d="M19 3A2 2 0 0 1 21 5V19A2 2 0 0 1 19 21H5A2 2 0 0 1 3 19V5A2 2 0 0 1 5 3H19M18.5 18.5V13.2A3.26 3.26 0 0 0 15.24 9.94C14.39 9.94 13.4 10.46 12.92 11.24V10.13H10.13V18.5H12.92V13.57C12.92 12.8 13.54 12.17 14.31 12.17A1.4 1.4 0 0 1 15.71 13.57V18.5H18.5M6.88 8.56A1.68 1.68 0 0 0 8.56 6.88C8.56 5.95 7.81 5.19 6.88 5.19A1.69 1.69 0 0 0 5.19 6.88C5.19 7.81 5.95 8.56 6.88 8.56M8.27 18.5V10.13H5.5V18.5H8.27Z"
            />
          </svg>
          <a href="https://www.linkedin.com/in/ericjungbluth/" target="_blank">View my LinkedIn page</a>
        </p>
        <p class="info">
          <svg class="svg-style" viewBox="0 0 24 24">
            <path
              fill="#3ecbbe"
              d="M12,2A10,10 0 0,0 2,12C2,16.42 4.87,20.17 8.84,21.5C9.34,21.58 9.5,21.27 9.5,21C9.5,20.77 9.5,20.14 9.5,19.31C6.73,19.91 6.14,17.97 6.14,17.97C5.68,16.81 5.03,16.5 5.03,16.5C4.12,15.88 5.1,15.9 5.1,15.9C6.1,15.97 6.63,16.93 6.63,16.93C7.5,18.45 8.97,18 9.54,17.76C9.63,17.11 9.89,16.67 10.17,16.42C7.95,16.17 5.62,15.31 5.62,11.5C5.62,10.39 6,9.5 6.65,8.79C6.55,8.54 6.2,7.5 6.75,6.15C6.75,6.15 7.59,5.88 9.5,7.17C10.29,6.95 11.15,6.84 12,6.84C12.85,6.84 13.71,6.95 14.5,7.17C16.41,5.88 17.25,6.15 17.25,6.15C17.8,7.5 17.45,8.54 17.35,8.79C18,9.5 18.38,10.39 18.38,11.5C18.38,15.32 16.04,16.16 13.81,16.41C14.17,16.72 14.5,17.33 14.5,18.26C14.5,19.6 14.5,20.68 14.5,21C14.5,21.27 14.66,21.59 15.17,21.5C19.14,20.16 22,16.42 22,12A10,10 0 0,0 12,2Z"
            />
          </svg>
          <a href="https://github.com/EricMellow" target="_blank">View my GitHub page</a>
        </p>
      </v-card-text>
    </v-card>
  </div>
</template>

<style scoped>
.container-div {
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
}

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

.svg-style {
  width: 24px;
  height: 24px;
  margin-right: 5px;
}

.info {
  align-items: center;
  display: flex;
}

a:link {
  text-decoration: none;
  color: rgba(255, 255, 255, 0.6);
}

a:visited {
  color: rgba(255, 255, 255, 0.6);
  text-decoration: none;
}

.card-dark {
  max-width: 350px;
  background-color: #272727;
  width: 325px;
  color: white;
  margin-top: 50px;
}

.btn-border {
  position: relative;
  display: inline-block;
  padding: 0.5em 2em;
  cursor: pointer;
  overflow: hidden;
}
.btn-border:before,
.btn-border:after {
  content: "";
  position: absolute;
  left: 0;
  height: 2px;
  width: 100%;
  background-color: #252525;
}
.btn-border:before {
  top: 0;
}
.btn-border:after {
  bottom: 0;
}
.btn-border:hover > * > *:before,
.btn-border:hover > * > *:after {
  transform: translate3d(0, 0, 0);
}
.btn-border:hover > * > * > *:before,
.btn-border:hover > * > * > *:after {
  transform: translate3d(0, 0, 0);
}
.btn-border > *:before,
.btn-border > *:after {
  content: "";
  position: absolute;
  top: 0;
  height: 100%;
  width: 2px;
  background-color: #252525;
}
.btn-border > *:before {
  left: 0;
}
.btn-border > *:after {
  right: 0;
}
.btn-border > * > *:before,
.btn-border > * > *:after {
  content: "";
  position: absolute;
  left: 0;
  z-index: 9;
  height: 2px;
  width: 100%;
  background-color: #3ecbbe;
}
.btn-border > * > *:before {
  top: 0;
  transform: translate3d(-105%, 0, 0);
  transition: transform 0.8s cubic-bezier(0.4, 0, 0.2, 1);
}
.btn-border > * > *:after {
  bottom: 0;
  transform: translate3d(105%, 0, 0);
  transition: transform 0.8s cubic-bezier(0.4, 0, 0.2, 1);
}
.btn-border > * > * > *:before,
.btn-border > * > * > *:after {
  content: "";
  position: absolute;
  top: 0;
  z-index: 9;
  height: 100%;
  width: 2px;
  background-color: #3ecbbe;
}
.btn-border > * > * > *:before {
  left: 0;
  transform: translate3d(0, 105%, 0);
  transition: transform 0.8s cubic-bezier(0.4, 0, 0.2, 1);
}
.btn-border > * > * > *:after {
  right: 0;
  transform: translate3d(0, -105%, 0);
  transition: transform 0.8s cubic-bezier(0.4, 0, 0.2, 1);
}
</style>
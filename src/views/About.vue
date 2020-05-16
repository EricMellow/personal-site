<template>
  <div class="about">
    <h2 class="sub-head">About</h2>
    <p class="p-text">
      A front-end developer with a passion for problem-solving; my focus is on
      creating clean software solutions that deliver a great user experience. My
      undergraduate degree gives me a great base in critical thinking and the
      ability to make connections across multiple ideas. I'm endlessly curious
      and enjoy a good challenge, which is what drew me to software development
      when I was looking to change careers.
      While it's impossible to really get to know me just from my site, I've included
      three of my major interests below that are both important to me and
      have also shaped who I am in a significant way.
    </p>
    <v-parallax dark src="../assets/music-bw.jpeg" class="music"></v-parallax>
    <div>
      <h2 class="sub-head">Music</h2>
      <p class="p-text">
        I've been a musician since college. I taught myself how to play bass
        and started a band with my friends. No clubs would book us so we rented out a social hall and put
        on our own shows. We wanted to go on tour, so we booked some shows
        around the midwest over spring break. We never stopped to think that we
        couldn't do something; if we wanted to do it, we would just do it. We
        got to the point where we were releasing a record every couple of years
        and going on 4-5 weeklong tours a few times a year. When I look back on
        it now, I'm amazed at what we were able to accomplish through sheer
        will, and I'm thankful for all the friends I made along the way and all
        the experiences I got to have as I toured the country with my best friends.
      </p>
    </div>
    <v-parallax dark src="../assets/run.jpg" class="music"></v-parallax>
    <div>
      <h2 class="sub-head">Running</h2>
      <p class="p-text">
        I love the simplicity of running. I love that you only get out
        of it what you put into it. I love chasing my goals and seeing how close
        I can come to the limits of my abilities. Running has taught me hard
        work, dedication and perseverance. It has taken me to places like
        Boston, Toronto, Beijing, and even into the heart of the Grand Canyon.
        Whether chasing marathon PRs or just running through the mountains with
        my friends, there is always something I enjoy about running.
      </p>
    </div>
    <v-parallax dark src="../assets/books.jpeg" class="music"></v-parallax>
    <div>
      <h2 class="sub-head">Reading</h2>
      <p class="p-text">
        As someone with a degree in English Theory & Criticism and a minor in
        Philosophy, it should come as no surprise that I'm a voracious reader. I
        jump back and forth between fiction and non-fiction; from a beautiful
        paragraph of perfectly crafted prose to a peek into the life and mind of
        an important figure, it all interests me. While both can teach you
        something about the world, only fiction can teach you a little bit about
        yourself. As someone with a great thirst for knowledge and a healthy
        dose of curiosity, my personal library will always be expanding.
      </p>
    </div>
  </div>
</template>

<style scoped>
.music {
  height: 650px !important;
}

.sub-head {
  background-color: black;
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

.p-text {
  background-color: black;
  color: white;
  /* text-align: center; */
  padding: 10px 200px 25px 200px;
  line-height: 2.5rem;
  font-size: 1.5rem;
  margin: 0;
}
</style>
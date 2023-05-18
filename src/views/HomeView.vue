<template>
  <main>
    <NavBar />
    <div id="home" style="padding-bottom: 60px;">
      <div class="wrapper pt-5">
        <div class="row">
          <div class="col-md-6">
            <div class="flip-box">
              <div class="flip-box-inner">
                <div class="flip-box-front">
                  <img class="img img-fluid" src="https://i.postimg.cc/kXZsqSPz/t0.jpg" alt="IMO">
                </div>
                <div class="flip-box-back">
                  <img class="photo img-fluid" src="https://i.postimg.cc/nV1L9kVN/IMG-20220810-221420-027.jpg" alt="logo">
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-6">
            <p class="text-center animate__animated animate__fadeInDown" id="myName" style="color: black;">WELCOME TO MY
              PORTFOLIO</p>
            <!-- <p class="slogan-now">Be mesmerized.</p> -->
            <div class="waviy">
              <span style="--i:1">M</span>
              <span style="--i:2">O</span>
              <span style="--i:3">G</span>
              <span style="--i:4">A</span>
              <span style="--i:5">M</span>
              <span style="--i:6">A</span>
              <span style="--i:7">D</span>
              <div style="color: transparent;">.......</div>
              <span style="--i:8">I</span>
              <span style="--i:9">M</span>
              <span style="--i:10">R</span>
              <span style="--i:11">A</span>
              <span style="--i:12">A</span>
              <span style="--i:13">N</span>
            </div>
            <div class="waviy">
              <span style="--i:14">B</span>
              <span style="--i:15">E</span>
              <span style="--i:16">R</span>
              <span style="--i:17">N</span>
              <span style="--i:18">K</span>
              <span style="--i:19">S</span>
              <span style="--i:20">E</span>
              <span style="--i:21">N</span>
            </div>
            <p class="text-center animate__animated animate__fadeInUp" id="myName" style="color: black;">FULL STACK WEB
              DEVELOPER</p>
            <div class="home_extra">
              <button><a download="../assets/ImraanCV.pdf" href="../assets/ImraanCV.pdf" target="_blank"
                  class="tdn">Download
                  CV</a></button>
              <button><a href="/about" class="tdn">More info</a></button>

              <!-- <div class="lead pt-4">
                  <a id="M1I0B_" target="_blank" href="https://www.instagram.com/imraanbernksen"
                    class="fa-brands fa-instagram"></a>
                  <a id="M1I0B_" target="_blank" href="https://www.youtube.com/channel/UCSPsMgF3JVcXGRjXDwGBNaQ"
                    class="fa-brands fa-youtube"></a>
                  <a id="M1I0B_" target="_blank" href="https://www.tiktok.com/@imraanbernksen"
                    class="fa-brands fa-tiktok"></a>
                  <a id="M1I0B_" target="_blank" href="https://codepen.io/IMRAANBERNKSEN"
                    class="fa-brands fa-codepen"></a>
                  <a id="M1I0B_" target="_blank" href="https://github.com/ImraanBernksen"
                  class="fa-brands fa-github"></a>
                </div> -->
            </div>
          </div>
        </div>
      </div>
    </div>
    <FooterComponent />
  </main>
</template>
<script>
import NavBar from '../components/NavBar.vue';
import FooterComponent from '../components/FooterComponent.vue'
export default {
  components: {
    NavBar,
    FooterComponent
  }
}
</script>
<style scoped>
/*
main {
  height: 100vh !important;
}
*/

.tdn {
  text-decoration: none;
}

button {
  padding: 13px 36px;
  border-radius: 50px;
  border: 0;
  background-color: white;
  box-shadow: rgb(0 0 0 / 5%) 0 0 8px;
  letter-spacing: 1.5px;
  text-transform: uppercase;
  font-size: 15px;
  transition: all .5s ease;
}

button:hover {
  letter-spacing: 3px;
  background-color: hsl(0, 0%, 0%);
  color: hsl(0, 0%, 100%);
  box-shadow: rgb(255, 255, 255) 0px 7px 29px 0px;
}

button:active {
  letter-spacing: 3px;
  background-color: hsl(0, 0%, 100%);
  color: hsl(0, 0%, 100%);
  box-shadow: rgb(93 24 220) 0px 0px 0px 0px;
  transform: translateY(10px);
  transition: 100ms;
}

body {
  width: 100%;
}

#M1I0B_ {
  color: black;
  font-size: 30px;
  padding: 10px;
}

#M1I0B_:hover {
  color: white;
}

#myName {
  padding-top: 30px;
  font-size: 30px;
}

/* .rowed {
  display: flex;
  justify-content: center;
  border: 5px solid black;
}

.rows{
  display: inline-block;
  justify-content: center;
  align-items: center;
  border: 3px solid red;
}
*/

.wrapper {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 80vh;
}

.wrapper img {
  display: block;
  margin: 15px auto;
  width: 30em;
}

.wrapper p {
  text-align: center;
}

.flip-box {
  background-color: transparent;
  width: 500px;
  height: 500px;
  perspective: 1000px;
  border-radius: 50%;
  margin: auto;
}

.flip-box-inner {
  position: relative;
  width: 100%;
  height: 100%;
  transition: transform 0.8s;
  transform-style: preserve-3d;
}

.flip-box:hover .flip-box-inner {
  transform: rotateY(180deg);
}

.flip-box-front,
.flip-box-back {
  position: absolute;
  width: 100%;
  height: 100%;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
}

.flip-box-back {
  color: black;
  transform: rotateY(180deg);
  border-radius: 50%;
  text-align: center;
}

.waviy {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: 'Gemunu Libre', sans-serif;
}

.waviy span {
  position: relative;
  display: inline-block;
  font-size: 80px;
  color: white;
  text-transform: uppercase;
  animation: flip 2s infinite;
  animation-delay: calc(.2s * var(--i))
}

@keyframes flip {

  0%,
  80% {
    transform: rotateY(360deg)
  }
}

/*
.slogan-now {
  color: white;
  text-shadow:  1.5px 1.5px 1.5px black;
  text-align: center;
  font-size: 25px;
  animation-duration: 2.5s;
  animation-fill-mode: both;
  animation-name: sloganColor;
  animation-iteration-count: infinite;
}
@keyframes sloganColor {
  0% {
    color: white;
  }
  50% {
    color: black;
  }
  100% {
    color: white;
  }
}
*/</style>
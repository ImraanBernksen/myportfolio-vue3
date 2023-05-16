<template>
<main>
    <NavBar/>
    <div id="skills">
        <div class="container">
 <div class="row">
  <!-- <div class="col-lg-6 p-4">
    <div style="height: 33rem; width: 32rem; margin: auto;">
    <h4><ins>Technical Skills</ins></h4>
    <div class="text-dark">
      <i class="fa-brands fa-html5 fa-3x"></i>

      <i id="imo" class="fa-brands fa-css3 fa-3x"></i>

      <i id="imo" class="fa-brands fa-bootstrap fa-3x"></i>

      <i id="imo" class="fa-brands fa-square-js fa-3x"></i>

      <i id="imo" class="fa-brands fa-vuejs fa-3x"></i>

      <i id="imo" class="fa-brands fa-node-js fa-3x"></i>

      <i id="imo" class="bi bi-filetype-sql fa-3x"></i>

    </div>
  </div>
</div> -->
<div class="col-lg-6 p-4">
             <div style="width: 33rem; width: 32rem; margin: auto;">
                 <h4 class="animate__animated animate__fadeInLeft"><ins>Education</ins></h4>
                 <ul>
                  <li>
                      <p class="lead about-par">Oaklands High School, Chukker Rd, Lansdowne <br> - Matriculated (2016 - 2020)</p>
                  </li>
                  <li>
                      <p class="lead about-par">Life Choices Academy, 314 Imam Harom Rd, Lansdowne :<br> - Currently : Full Stack Course (2022 - 2023) <br> - Intern : LC Studio (2023 - Currently) <br> - Lecturer Assistant (2023 - Currently)</p>
                  </li>
                </ul>
              </div>
              <div style="height: 33rem; width: 32rem; margin: auto;">
                <h4 class="animate__animated animate__fadeInLeft"><ins>Technical Skills</ins></h4>
                <div class="container">
                  <div class="row">
                    <div class="col-4"><i class="fa-brands fa-html5 fa-5x"></i></div>
                    <div class="col-4"><i id="imo" class="fa-brands fa-css3 fa-5x"></i></div>
                    <div class="col-4"><i id="imo" class="fa-brands fa-bootstrap fa-5x"></i></div>
                    <div class="col-4"><i id="imo" class="fa-brands fa-square-js fa-5x"></i></div>
                    <div class="col-4"><i id="imo" class="fa-brands fa-vuejs fa-5x"></i></div>
                    <div class="col-4"><i id="imo" class="fa-brands fa-node fa-5x"></i></div>
                    <div class="col-4"><i id="imo" class="bi bi-filetype-sql fa-5x"></i></div>
                    <div class="col-4"><i id="imo" class="fa-brands fa-wordpress fa-5x pt-4"></i></div>
                    <div class="col-4"><i id="imo" class="fa-brands fa-figma fa-5x pt-4"></i></div>
                    <div class="col-4"><img style="width: 7rem; padding-left: 30px" id="imo" src="https://i.postimg.cc/WbHy00rY/user-experience.png"></div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-lg-6 p-4">
                 <h4 class="card-title animate__animated animate__fadeInRight"><ins>Experience</ins></h4>
                 <ul class="timeline">
                  <li class="event">
                      <p class="lead about-par">Grasshopper Coding Fundamentals I &amp; II Certifications - 2022 (Completed)</p>
                  </li>
                  <li class="event">
                      <p class="lead about-par">Responsive Web Design Developer Certification - 2022 (Completed)</p>
                  </li>
                  <li class="event">
                      <p class="lead about-par">JavaScript  Algorithms and Data Structures Certification - 2022 (Completed)</p>
                  </li>
                  <li class="event">
                      <p class="lead about-par">Life Choices Coding Academy: <br> Full Stack Course - 2022/23 (Completed)</p>
                  </li>
                  <li class="event">
                    <p class="lead about-par">Life Choices Coding Academy: <br>LC Studio - 2023 (Currently)</p>
                </li>
                <li class="event">
                    <p class="lead about-par">Life Choices Coding Academy : <br> Lecturer Assistant - 2023 (Currently)</p>
                </li>
                </ul>
            </div>
         </div>
 </div>
</div>
        <!-- </div> -->
    <FooterComponent/>
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
.card { 
  border-radius: 20px;
  box-shadow: 3px -3px 3px 3px black;
}
.card:hover {
  border-radius: 20px;
  box-shadow: 3px -3px 3px 3px gold;
}

/*timeline*/

body{margin-top:20px;}
.timeline {
    border-left: 3px solid #00334C;
    border-bottom-right-radius: 4px;
    border-top-right-radius: 4px;
    margin: 0 auto;
    letter-spacing: 0.2px;
    position: relative;
    line-height: 1.3em;
    font-size: 1.03em;
    padding: 50px;
    list-style: none;
    text-align: left;
    max-width: 100%;
}

@media (max-width: 767px) {
    .timeline {
        max-width: 98%;
        padding: 25px;
    }
}

.timeline h1 {
    font-weight: 300;
    font-size: 1.4em;
}

.timeline h2,
.timeline h3 {
    font-weight: 600;
    font-size: 1rem;
    margin-bottom: 10px;
}

.timeline .event {
    border-bottom: 1px dashed #e8ebf1;
    padding-bottom: 25px;
    margin-bottom: 25px;
    position: relative;
}

@media (max-width: 767px) {
    .timeline .event {
        padding-top: 30px;
    }
}

.timeline .event:last-of-type {
    padding-bottom: 0;
    margin-bottom: 0;
    border: none;
}

.timeline .event:before,
.timeline .event:after {
    position: absolute;
    display: block;
    top: 0;
}

.timeline .event:before {
    left: -207px;
    content: attr(data-date);
    text-align: right;
    font-weight: 100;
    font-size: 0.9em;
    min-width: 120px;
}

@media (max-width: 767px) {
    .timeline .event:before {
        left: 0px;
        text-align: left;
    }
}

.timeline .event:after {
    -webkit-box-shadow: 0 0 0 3px #00334C;
    box-shadow: 0 0 0 3px #00334C;
    left: -55.8px;
    background: #fff;
    border-radius: 50%;
    height: 9px;
    width: 9px;
    content: "";
    top: 5px;
}

@media (max-width: 767px) {
    .timeline .event:after {
        left: -31.8px;
    }
}

.rtl .timeline {
    border-left: 0;
    text-align: right;
    border-bottom-right-radius: 0;
    border-top-right-radius: 0;
    border-bottom-left-radius: 4px;
    border-top-left-radius: 4px;
    border-right: 3px solid #727cf5;
}

.rtl .timeline .event::before {
    left: 0;
    right: -170px;
}

.rtl .timeline .event::after {
    left: 0;
    right: -55.8px;
}

</style>
<template>
<main>
    <NavBar/>
    <div id="skills">
    <div class="container">
    <div class="row">
    <div class="col-lg-6 p-4 animate__animated animate__fadeInLeft">
            <h4><ins>EDUCATION</ins></h4>
            <div class="row pt-4">
            <div class="col-sm-6 m-auto">
                <div class="border-img">
                    <img src="https://i.postimg.cc/RZRJCf0B/cropped-oaklands-badge-small-2.png" style="width: 10rem;">
                </div>
            </div>
            <div class="col-sm-6 m-auto pt-3">
                <p class="lead about-par">Oaklands High School, Chukker Rd, Lansdowne <br> - Matriculated (2016 - 2020)</p>
            </div>
            </div>
            <div class="row pt-4">
            <div class="col-sm-6 m-auto">
                <div class="border-img">
                    <img src="https://i.postimg.cc/FHmJQGNp/LIFE-CHOICES-ICON-ON-GREEN.jpg" style="width: 10rem;">
                </div>
            </div>
            <div class="col-sm-6 m-auto pt-3">
                <p class="lead about-par">Life Choices Academy, 314 Imam Harom Rd, Lansdowne :<br> - LC Studio Intern (2023 - Currently) <br> - Lecturer Assistant (2023 - Currently)</p>
            </div>
            </div>
    </div>
    <div class="col-lg-6 p-4 animate__animated animate__fadeInRight">
        <h4 class="card-title"><ins>EXPERIENCE</ins></h4>
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
                <p class="lead about-par">Life Choices Coding Academy: <br> Full Stack Developer Course - 2022/23 (Completed)</p>
            </li>
        </ul>
    </div>
    </div>
    <div class="container">
        <div style="margin: auto;">
        <h4><ins>TECHNICAL SKILLS</ins></h4>
            <div class="row">
            <div class="col">
                <i id="imo" class="fa-brands fa-html5 fa-10x"></i>
            </div>
            <div class="col">
                <i id="imo" class="fa-brands fa-css3 fa-10x"></i>
            </div>
            <div class="col">
                <i id="imo" class="fa-brands fa-bootstrap fa-10x"></i>
            </div>
            <div class="col">
                <i id="imo" class="fa-brands fa-square-js fa-10x"></i>
            </div>
            <div class="col">
                <i id="imo" class="fa-brands fa-vuejs fa-10x"></i>
            </div>
        </div>
        <div class="row">
            <div class="col"><i id="imo" class="fa-brands fa-node fa-10x pt-5"></i></div>
            <div class="col"><i id="imo" class="bi bi-filetype-sql fa-10x"></i></div>
            <div class="col"><i id="imo" class="fa-brands fa-wordpress fa-10x pt-5"></i></div>
            <div class="col"><i id="imo" class="fa-brands fa-figma fa-10x pt-5"></i></div>
            <div class="col"><img class="pt-5 m-auto" style="width: 10rem;" id="imo" src="https://i.postimg.cc/WbHy00rY/user-experience.png"></div>
        </div>
        </div>
    </div>
 </div>
</div>
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

.border-img {
    border: 1px solid;
    box-shadow: 5px 10px;
    width: 10rem;
    margin: auto;
}

.border-img:hover {
border: 1px solid white;
box-shadow: 5px 10px white;
}


.row > .col > i:hover {
    color: white;
}
i.imo:hover {
    color: white;
}

.img-border {
    border: 5px solid #00334C;
    margin-left: 140px;
    margin-right: 140px;
}
/*
.card { 
  border-radius: 20px;
  box-shadow: 3px -3px 3px 3px black;
}
.card:hover {
  border-radius: 20px;
  box-shadow: 3px -3px 3px 3px gold;
}
*/

/*timeline*/

body{margin-top:20px;}
.timeline {
    border-left: 3px solid #00334C;
    border-bottom-right-radius: 4px;
    border-top-right-radius: 4px;
    margin: 0 auto;
    letter-spacing: 0.2px;
    position: relative;
    line-height: 1.0em;
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
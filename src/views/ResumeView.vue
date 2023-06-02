<template>
<main>
    <NavBar/>
    <div id="skills">
    <div class="container">
    <div class="row">
    <div class="col-lg-6 p-4 animate__animated animate__fadeInLeft">
            <h4><ins>EDUCATION</ins></h4>
            <div class="row pt-4 pb-4" id="border-edu">
            <div class="col-sm-6 m-auto">
                <div class="border-img">
                    <img src="https://i.postimg.cc/RZRJCf0B/cropped-oaklands-badge-small-2.png" style="width: 10rem;">
                </div>
            </div>
            <div class="col-sm-6 m-auto pt-3">
                <p class="lead about-par">Oaklands High School, Chukker Rd, Lansdowne <br> - Matriculated (2016 - 2020)</p>
            </div>
            </div>
            <div class="row pt-2 pb-1 mt-4" id="border-edu">
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
        <h4><ins>EXPERIENCE</ins></h4>
        <ul class="border-expert py-2">
            <li>
                <p class="lead about-par" id="expert">Grasshopper Coding Fundamentals I &amp; II Certifications - 2022 (Completed)</p>
            </li>
            <li>
                <p class="lead about-par" id="expert">Responsive Web Design Developer Certification - 2022 (Completed)</p>
            </li>
            <li>
                <p class="lead about-par" id="expert">JavaScript  Algorithms and Data Structures Certification - 2022 (Completed)</p>
            </li>
            <li>
                <p class="lead about-par" id="expert">Life Choices Coding Academy: <br> Full Stack Developer Course - 2022/23 (Completed)</p>
            </li>
        </ul>
        <!-- <ul class="timeline">
            <li>
                <p class="lead about-par">Grasshopper Coding Fundamentals I &amp; II Certifications - 2022 (Completed)</p>
            </li>
            <li>
                <p class="lead about-par">Responsive Web Design Developer Certification - 2022 (Completed)</p>
            </li>
            <li>
                <p class="lead about-par">JavaScript  Algorithms and Data Structures Certification - 2022 (Completed)</p>
            </li>
            <li>
                <p class="lead about-par">Life Choices Coding Academy: <br> Full Stack Developer Course - 2022/23 (Completed)</p>
            </li>
        </ul> -->
    </div>
    </div>
    <div class="container">
        <div class="tech-skills">
        <h4><ins>TECHNICAL SKILLS</ins></h4>
            <div class="row pt-5">
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
.tech-skills {
    padding: 40px 0 80px 0;
}

#border-edu {
    box-shadow: 0 3px 10px black;
}
.border-expert {
  box-shadow: 0 3px 10px black;
}

.border-expert:hover {
    background-color: white;
}

#border-edu:hover {
    background-color: white;
}

#expert {
    padding: 22.5px;
}

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
</style>
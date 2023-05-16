<template>
    <main>
    <NavBar/>
    <div id="projects">
      <h4 class="animate__animated animate__fadeInDown"><ins>PROJECTS</ins></h4>
      <div class="lead" id="projectlinks">
        <div class="row" style="gap: 2rem; padding: 20px;">
        <div class="card h-100" v-for="item in arr" :key="item" style="width: 28rem; margin: auto; background-color: white;">
          <img :src="item.imgSrc" loading="lazy" class="card-img-top mt-2">
          <div class="card-body">
            <h4 class="card-title">{{item.projectName}}</h4>
            <p class="card-text">{{item.projectText}}</p>
            <a :href="item.linkOne" target="_blank" class="btn btn-outline-dark" id="btn_">GitHub</a>
            <a :href="item.linkTwo" target="_blank" class="btn btn-outline-dark" id="btn_">Hosting</a>
          </div>
        </div>
      </div>
      </div>
      <div class="lead" id="viewprojects">
        <ul>
          <li>
            <a
              id="M1I0B_"
              target="_blank"
              href="https://github.com/ImraanBernksen"
              class="fa-brands fa-github"
            ></a>
          </li>
          <li>
            <a
              id="M1I0B_"
              target="_blank"
              href="https://app.netlify.com/teams/imraanbernksen/overview"
              class="fa-solid fa-n"
            ></a>
          </li>
          <li>
            <a
              id="M1I0B_"
              target="_blank"
              href="https://codepen.io/IMRAANBERNKSEN"
              class="fa-brands fa-codepen"
            ></a>
          </li>
        </ul>
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
  },
    data() {
      return {
        arr: [
          {
            imgSrc: "https://i.postimg.cc/GmGX1PZm/Screenshot-1.png",
            projectName: "Mesmerize Ecommerce Website",
            linkOne: "https://github.com/ImraanBernksen/Mesmerize_Project",
            projectText: "VueJs, NodeJs, MySQL",
            linkTwo: "https://mesmerize-project10.web.app/",
          },
          {
            imgSrc: "https://i.postimg.cc/Jng5HKgJ/Screenshot-8.png",
            projectName: "Nostalgic Ecommerce Website",
            linkOne: "https://github.com/Mu-een/Nostalgic_NodeEOMP",
            projectText: "VueJS, NodeJS, MySQL",
            linkTwo: "https://nostalgic-nodejs-eomp.web.app/",
          },
          {
            imgSrc: "https://i.postimg.cc/B6PMWhN1/project1.png",
            projectName: "Portfolio Page",
            projectText: "HTML",
            linkOne: "https://github.com/ImraanBernksen/PortfolioPage",
            linkTwo: "https://imraanbernksenportfoliopage.netlify.app/",
          },
          {
            imgSrc: "https://i.postimg.cc/ZRj3M6zy/project2.png",
            projectName: "JavaScript Calculator",
            projectText: "HTML, JavaScript",
            linkOne: "https://github.com/ImraanBernksen/JS_Calculator",
            linkTwo: "https://imraanbernksen-jscalculator.netlify.app/",
          },
          {
            imgSrc: "https://i.postimg.cc/YCk25yNG/project3.png",
            projectName: "JavaScript EOMP",
            projectText: "HTML, JavaScript",
            linkOne: "https://github.com/ImraanBernksen/JS_EOMP",
            linkTwo: "https://imraanbernksen-js-eomp.netlify.app/",
          },
          {
            imgSrc: "https://i.postimg.cc/BvKdDY2w/tcn-bnry-test.png",
            projectName: "TCN (BNRY Assessment)",
            linkOne: "https://github.com/ImraanBernksen/bnry_test-CC.git",
            projectText: "VueJS, Node",
            linkTwo: "https://bnrytest-tcn.web.app/",
          },
        ],
      };
    },
  };
</script>
<style scoped>
#projects {
  text-align: center;
  padding-bottom: 20px;
}
#projectlinks li {
  list-style: none;
}
#viewprojects li {
  list-style: none;
  padding: 0 5px;
  display: inline;
}
#viewprojects {
  padding-top: 50px;
}

#projects a {
  padding: 0 5px;
}
.project-tile {
  text-shadow: 0 0 8px black;
}

img {
  border-radius: 8px;
}
.card { 
  border-radius: 20px;
  box-shadow: 3px -3px 3px 3px black;
}
.card:hover {
  border-radius: 20px;
  box-shadow: 3px -3px 3px 3px white;
}
</style>
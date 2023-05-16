<template>
<main>
  <NavBar/>
  <div id="about">
      <div style="height: 15rem; width: 80rem; margin: auto;">
      <h4 class="animate__animated animate__fadeInDown"><ins>ABOUT ME</ins></h4>
      <p class="lead about-par">
        I'm 20 years old and born in Cape Town, South Africa. I'm a IT Intern for LC Studio
        at Life Choices Academy and i would like to have a job in web development.
        Graduated from Oaklands Highschool in 2020 then, after I did some online courses.
        I'm very mature for my age, friendly and hardworking. I've
        always been interested in technology, web design and software development.
        I enjoy interacting and work with people. One of my most important attributes is
        responsibility, I appreciate being depended on and trustworthy. I will always go the
        extra mile and be helpful where I can.
      </p>
  </div>      
<div class="row">
  <div class="col-lg-6">
  <div style="height: 25rem; width: 31rem; margin: auto;">
      <h4 class="about-par animate__animated animate__fadeInLeft"><ins>PERSONAL DETAILS</ins></h4>
              <p class="lead about-par">
                Name: Mogamad Imraan<br>
                Surname: Bernksen<br>
                Gender: Male<br>
                Birth: 04/07/2002<br>
                Cellphone: 0681278921<br>
                Email: imraanbernksen@gmail.com<br>
                Location: Cape Town, South Africa<br>
              </p>
  </div>
</div>
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
    <div class="col-lg-6">
    <div style="height: 25rem; width: 50rem; margin: auto; padding-right: 200px;">
      <h4 class="about-par animate__animated animate__fadeInRight"><ins>INTERESTS</ins></h4>
      <p class="lead about-par">
        My interests are working out, playing soccer, web design and designing clothing. Coding involves a lot of problem-solving skills. Web design allows me to showcase my creativity by designing visually appealing websites. Similarly, coding allows me to develop innovative solutions to real-world problems. The reason why so interested in soccer because it keeps me going and participating in team sports can provide a sense of community and social connection, which can improve my overall well-being. Exercise has improved my mental health by reducing stress, anxiety, and depression, and boosting self-esteem and cognitive function.
      </p>
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
  name: 'AboutView',
  components: {
    NavBar,
    FooterComponent
  }
}
</script>
<style scoped>

#about {
  text-align: center;
}
.card { 
  border-radius: 20px;
  box-shadow: 3px -3px 3px 3px black;
}
.card:hover {
  border-radius: 20px;
  box-shadow: 3px -3px 3px 3px gold;
}
  
</style>

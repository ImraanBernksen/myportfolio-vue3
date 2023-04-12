<template>
<main>
    <NavBar/>
    <div id="skills">
        <h2><ins>Resume</ins></h2>
 <div class="row">
         <div class="col-lg-4 p-4">
             <div class="card" id="cards_" style="height: 25rem; width: 30rem; margin: auto;">
               <div class="card-body">
                 <h4 class="card-title">Details</h4>
                         <p class="card-text lead about-par">
                           Name: Mogamad Imraan<br>
                           Surname: Bernksen<br>
                           Birth: 04/07/2002<br>
                           Languages: English &amp; Afrikaans - Read &amp;
                           Write
                           Cellphone: 0681278921<br>
                           Email: imraanbernksen@gmail.com<br>
                           Location: Cape Town, South Africa<br>
                         </p>
               </div>
             </div>
         </div>
         <div class="col-lg-4 p-4">
             <div class="card" id="cards_" style="height: 25rem; width: 30rem; margin: auto;">
               <div class="card-body">
                 <h4 class="card-title">Education</h4>
                 <p class="card-text lead about-par">
                    Oaklands High School, Chukker Rd, Lansdowne - Matriculated (2016 - 2020)<br><br>
                    Life Choices Academy, 314 Imam Harom Rd, Lansdowne - Student (2022 - Currently)<br>
                 </p>
               </div>
             </div>
         </div>
         <div class="col-lg-4 p-4">
             <div class="card" id="cards_" style="height: 25rem; width: 30rem; margin: auto;">
               <div class="card-body">
                 <h4 class="card-title">Experience</h4>
                 <p class="card-text lead about-par">
                    Grasshopper Coding Fundamentals I & II Certifications - 2022 (Completed)<br>
                    Responsive Web Design Developer Certification - 2022 (Completed)<br>
                    JavaScript  Algorithms and Data Structures Certification - 2022 (Completed)<br>
                    Life Choices Coding Academy Student - 2022 (Currently)<br>
                 </p>
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
<style>
    
</style>
<template>
<main>
<NavBar/>
    <div id="contact">
        <h2><ins>Contact</ins></h2>
        <div class="lead" id="fill">
        <!-- <h4 class="text-center">Fill in:</h4> -->
        <form name="contact-form" action="https://formspree.io/f/xwkzrbbv" method="POST">
        <div class="row mx-4 text-white">
            <div class="col-6">
              <label for="name">Name:</label>
              <input type="text" name="name" class="form-control" id="cards_" placeholder="Name" aria-label="Name">
            </div>
            <div class="col-6">
                <label for="name">Surname:</label>
              <input type="text" name="name" class="form-control" id="cards_" placeholder="Surname" aria-label="Surname">
            </div>
            <div class="col-6">
                <label for="number" class="form-label">Cellphone number:</label>
                <input type="text" name="name" class="form-control" id="cards_" placeholder="Cellphone number" aria-label="Cellphone number">
              </div>
              <div class="col-6">
                <label for="email" class="form-label">Email address:</label>
                <input type="email" name="email" class="form-control" id="cards_" placeholder="name@example.com">
              </div>
              <div class="mb-3">
                <label for="message" class="form-label">Message:</label>
                <textarea class="form-control" name="message" id="cards_" placeholder="Write something..." rows="3"></textarea>
              </div>
              <div class="mx-auto">
              <button type="submit" class="btn btn text-white" id="btn_">Submit</button>
             </div>
             </div>
        </form>
       </div>
     <br>
     <br>
     <div class="info">
       <p class="text-white lead">
         Cellphone: 0681278921<br>
         Gmail: imraanbernksen@gmail.com<br>
       </p>
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
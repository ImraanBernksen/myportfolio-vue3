<template>
<main>
<NavBar/>
    <div id="contact">
        <h4 class="animate__animated animate__fadeInDown"><ins>CONTACT</ins></h4>
        <div class="lead" id="fill">
        <br>
        <form name="contact-form" action="https://formspree.io/f/xwkzrbbv" method="POST">
          <div class="row mx-5 text-white">
              <div class="col-6">
                <label for="name">Name:</label>
                <input type="text" name="name" class="form-control" id="cards_" placeholder="Name" aria-label="Name" required>
              </div>
              <div class="col-6">
                  <label for="name">Surname:</label>
                <input type="text" name="name" class="form-control" id="cards_" placeholder="Surname" aria-label="Surname" required>
              </div>
              <div class="col-6">
                  <label for="number" class="form-label">Cellphone number:</label>
                  <input type="text" name="name" class="form-control" id="cards_" placeholder="Cellphone number" aria-label="Cellphone number" required>
                </div>
                <div class="col-6">
                  <label for="email" class="form-label">Email address:</label>
                  <input type="email" name="email" class="form-control" id="cards_" placeholder="name@example.com" required>
                </div>
                <div class="mb-3">
                  <label for="message" class="form-label">Message:</label>
                  <textarea class="form-control" name="message" id="cards_" placeholder="Write something..." rows="3" required></textarea>
                </div>
                <div class="mx-auto">
                <button type="submit" class="btn btn-outline-dark" id="btn_" style="width: 200px;">Submit</button>
               </div>
               </div>
          </form>
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
  
#contact {
  padding-bottom: 140px;
}

label {
  color: #00334C;
}

</style>
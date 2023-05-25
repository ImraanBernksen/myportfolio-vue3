<template>
<main>
<NavBar/>
    <div id="contact">
        <h4 class="animate__animated animate__fadeInDown"><ins>CONTACT</ins></h4>
        <div class="lead p-5 pt-0" id="fill">
        <form name="contact-form" action="https://formspree.io/f/xwkzrbbv" method="POST">
          <div class="row">
              <div class="col-12 col-lg-6">
                <label for="name" class="form-label">Full Name:</label>
                <input type="text" name="name" class="form-control input" required>
              </div>
              <div class="col-12 col-lg-6">
                <label for="number" class="form-label">Cellphone number:</label>
                <input type="number" name="number" class="form-control input" required>
              </div>
              <div class="col-12 col-lg-6">
                <label for="email" class="form-label">Email address:</label>
                <input type="email" name="email" class="form-control input" required>
              </div>
              <div class="col-12 col-lg-6">
                  <label for="name" class="form-label">Subject:</label>
                <input type="text" name="name" class="form-control input" required>
              </div>
                <div class="mb-3">
                  <label for="message" class="form-label">Message:</label>
                  <textarea class="form-control input" name="message" rows="5" required></textarea>
                </div>
                <div class="mx-auto pt-3">
                <button type="submit" class="btn btn-outline-light input"  style="width:9rem;">Submit</button>
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
form {
  padding: 30px;
  box-shadow: 0 3px 10px black;
}

button {
  background: black;
}
.input {
  border: none;
  border-radius: 4px;
  box-shadow: 2px 2px 7px 0 rgb(0, 0, 0, 0.2);
  outline: none;
}

#contact {
  padding-bottom: 20px;
}

label {
  color: #00334C;
}

</style>
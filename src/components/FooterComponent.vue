<template>
    <footer style="background-color: white">
        
        <div class="container text-center pt-3">
            <div class="row">
            <div class="col-sm-4 lead">
                <div class="info">
                    <p class="lead about-par text-start">
                    <i id="icon" class="fa-sharp fa-solid fa-location-dot"></i> Address: Highlands Estate, Cape Town, Western Cape<br>
                    <i id="icon" class="fa-solid fa-phone"></i> Cellphone: 0681278921<br>
                    <i id="icon" class="fa-solid fa-envelope"></i> Gmail: imraanbernksen@gmail.com<br>
                    </p>
                </div>
            </div>
            <div class="col-sm-4">
            <a class="quick" href="/">HOME</a>
            <a class="quick" href="/about">ABOUT</a>
            <a class="quick" href="/resume">RESUME</a>
            <a class="quick" href="/projects">PROJECTS</a>
            <a class="quick" href="/testimonials">TESTIMONIALS</a>
            <a class="quick" href="/contact">CONTACT</a>
            </div>
            <div class="col-sm-4 lead m-auto">
            <a id="socials" target="_blank" href="https://instagram.com/imraanbernksen/" class="fa-brands fa-instagram"></a>
            <a id="socials" target="_blank" href="https://github.com/ImraanBernksen" class="fa-brands fa-github"></a>
            <a id="socials" target="_blank" href="https://www.linkedin.com/in/imraanbernksen/" class="fa-brands fa-linkedin"></a>
            <p class="lead pt-2">MIB &copy; COPYRIGHT 2023 | ALL RIGHTS RESERVED</p>
            </div>
            </div>
            <!-- <br>
            <div class="line"></div>
            <br>
            <p class="lead" style="margin-bottom: 0;">MIB &copy; COPYRIGHT 2023</p> -->
        </div>
    </footer>
</template>
<script>
export default {
    name: 'FooterComponent'
}
</script>
<style scoped>
/*
a#socials {
    display: inline;
}
*/
#socials {
    text-decoration: none;
    padding: 10px;
    display: block;
    color: black;
    font-size: 30px;
}

#socials:hover {
    color: #00FFA2;
}

#icon {
    color: #00FFA2;
    padding: 10px;
}

footer {
    padding: 10px;
    box-shadow:  0px 0 19px rgba(1, 0, 0, 0.9);
    width: 100%;
}

.info {
    padding-top: 10px;
    padding-bottom: 40px;
  }

.quick:hover{
    color: #00FFA2;
}
.quick {
    display: block;
    padding: 5px;
    color: black;
    /*text-align: start; */
    font-size: 18px;
    text-decoration: none;
}

.line {
    height: 2px;
    width: 85vw;
    background-color: black;
    justify-content: center;
    margin: auto;
}

a:hover {
    color: blue;
  }
</style>
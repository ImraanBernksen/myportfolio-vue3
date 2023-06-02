<template>
  <div class="menu">
    <div class="menu-list">
      <nav class="navbar navbar-expand-lg navbar navbar-light static-top">
        <div class="container-fluid">
          <a href="/"><img class="logo" src="https://i.postimg.cc/L40McznY/logo.png" alt="logo"></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse text-center" id="navbarSupportedContent">
            <ul class="navbar-nav mb-2 mb-lg-0">
              <li class="nav-item">
                <router-link to="/" class="nav-link">Home</router-link>
              </li>
              <li class="nav-item">
                <router-link to="/about" class="nav-link">About</router-link>
              </li>
              <li class="nav-item">
                <router-link to="/resume" class="nav-link">Resume</router-link>
              </li>
              <li class="nav-item">
                <router-link to="/projects" class="nav-link">Project</router-link>
              </li>
              <li class="nav-item">
                <router-link to="/testimonials" class="nav-link">Testimonials</router-link>
              </li>
              <li class="nav-item">
                <router-link to="/contact" class="nav-link">Contact</router-link>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}

.navbar-collapse {
  justify-content: center;
  align-items: center;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  margin: 0 10px;
}

.logo {
  width: 2em;
  border-radius: 50%;
}

.menu-list li {
  padding: 0 5px;
}

.menu-list {
  font-family: 'Playfair Display', serif;
  list-style: none;
  font-size: 25px;
}

nav {
  background-color: white;
  box-shadow: 0px 0 10px rgba(1, 0, 0, 0.9);
}

a:hover {
  color: #00FFA2;
  border-radius: 5px;
}

a.router-link-active {
  color: #00FFA2;
  border-radius: 5px;
}

.nav-link {
  text-decoration: none;
  color: black;
}
</style>

<template>
    <router-view/>
</template>
<script>

</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Gemunu+Libre:wght@600&family=Nanum+Pen+Script&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Alkalami&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    word-wrap: break-word;
}

body {
    height: 100vh;
    width: 100%;
}

h2 {
    font-family: 'Gemunu Libre', sans-serif;
}
h4, p, .project-tile, #fill, #social-media, #projects, footer {
    font-family: 'Alkalami', serif;
}
main, footer {
    min-width: 100%;
}

h1, h2, h3, h5, h6 {
    text-align: center;
    padding-bottom: 20px;
    padding: 20px;
    color: #00334C;
}
h4 {
    text-align: center;
    padding-bottom: 20px;
    padding-top: 20px;
    color: gold;
}

#skills {
    padding-bottom: 30px;
    text-align: center;
}

.about-par{
    text-align: start;
}

#social-media a {
    padding: 0 5px;
}


#social-media {
    text-align: center;
    padding-bottom: 20px;
}

#socials {
    text-decoration: none;
    padding: 6px
}

.img {
    border-radius: 50%;
}

.photo {
    border-radius: 50%;
}

#picture {
    background-attachment: fixed;
    background-repeat: no-repeat;
    background-size:cover;
}

#M1I0B_ {
    padding: 0 5px;
    text-decoration: none;
}

#imo {
    display: block;
    padding-top: 10px;
}

.home_extra {
    text-align: center;
    padding-top: 30px;
}

.form-label {
    padding-top: 15px;
}

#cards_ {
    border: 1px solid;
    padding: 10px;
    box-shadow: 5px 10px;
}

#btn_ {
    border: 1px solid;
    padding: 10px;
    box-shadow: 1px 5px;
}

#about1_ {
    border: 1px solid;
    box-shadow: 5px 10px;
    padding: 20px;
}

main {
    /*
    background: url(https://i.postimg.cc/DzDVmKRH/wallpaper4.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    width: 100%;
    height: 100%;
    background-color: #00FFA2;
    */
    background-image: linear-gradient(to right top, #00334c, #006282, #0096a6, #00cbb1, #00ffa2);
}

@media screen and (max-width:300px) {
    body {
    width: 100%;
    }
}

</style>
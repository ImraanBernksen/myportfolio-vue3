<template>
<main>
<NavBar/>
<!-- <div id="testimonial">
    <h4 class="animate__animated animate__fadeInDown"><ins>TESTIMONIALS</ins></h4>
    <div class="row" style="gap: 2rem; padding: 35px;">
        <div class="card" v-for="item in arr" :key="item" style="height: 38rem; width: 28rem; margin: auto; background-color: transparent;">
          <img :src="item.imgSrc" loading="lazy" class="card-img-top mt-2" alt="pic1">
          <div class="card-body">
            <h4 class="card-title">{{item.personName}}</h4>
            <p class="card-text" style="font-size: large;">{{item.infoText}}</p>
          </div>
        </div>
    </div>
</div> -->
<h4 class="animate__animated animate__fadeInDown"><ins>TESTIMONIALS</ins></h4>
<div id="testimonial">
<div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="true">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="3" aria-label="Slide 4"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="4" aria-label="Slide 5"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="5" aria-label="Slide 6"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <div class="card mb-3" id="cards_" style="width: 80%; margin: 0 auto; background-color: transparent;">
        <div class="row g-0" style="width: 100%;">
          <div class="col-md-5">
            <img src="https://i.postimg.cc/pTFspNgf/t1.jpg" class="img-fluid rounded-start m-auto">
          </div>
          <div class="col-md-7">
            <div class="card-body m-4">
              <h5 class="card-title m-auto" style="font-size: 30px;">Meezaan Davids</h5>
              <p class="card-text m-auto" style="font-size: 25px;">Imraan seems like chill guy who likes to keep to himself. He is a smart person who likes to be challenged and very passionate about soccer. He is a good judge of character, determined and hardworking. Engage conversions and topics with an innovate mindset to things.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="carousel-item">
      <div class="card mb-3" id="cards_" style="width: 80%; margin: 0 auto; background-color: transparent;">
        <div class="row g-0" style="width: 100%;">
          <div class="col-md-5">
            <img src="https://i.postimg.cc/9f6FFBY4/t5.jpg" class="img-fluid rounded-start m-3">
          </div>
          <div class="col-md-7">
            <div class="card-body m-4">
              <h5 class="card-title m-auto" style="font-size: 30px;">Kauthar Brandt</h5>
              <p class="card-text m-auto" style="font-size: 25px;">Imraan is a friendly individual and a pleasure to work with because of his supporting attributes. He encourages his peers to do their best, which allows him to work with any social group. His very knowledgeable on any topic, so its always lovely to engage in conversion with him.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="carousel-item">
      <div class="card mb-3" id="cards_" style="width: 80%; margin: 0 auto; background-color: transparent;">
        <div class="row g-0" style="width: 100%;">
          <div class="col-md-5">
            <img src="https://i.postimg.cc/KjQBYJv7/t2.jpg" class="img-fluid rounded-start m-3">
          </div>
          <div class="col-md-7">
            <div class="card-body m-4">
              <h5 class="card-title m-auto" style="font-size: 30px;">Brogan Gys</h5>
              <p class="card-text m-auto" style="font-size: 25px;">He is a very punctual person,  always on time. He is a very passionate person on the things he loves to do. He is very experienced with HTML, CSS, Bootstrap and thus he always understands his code and work that he is busy with.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="carousel-item">
      <div class="card mb-3" id="cards_" style="width: 80%; margin: 0 auto; background-color: transparent;">
        <div class="row g-0" style="width: 100%;">
          <div class="col-md-5">
            <img src="https://i.postimg.cc/QdCvRYV6/Joel-Profile.jpg" class="img-fluid rounded-start m-3">
          </div>
          <div class="col-md-7">
            <div class="card-body m-4">
              <h5 class="card-title m-auto" style="font-size: 30px;">Joel Mukanya</h5>
              <p class="card-text m-auto" style="font-size: 25px;">Imraan is the definition of a dedicated and professional young talent who has already proven to us that he is work-ready. He gained knowledge of web development, databases, APIs, and more.He volunteers as a lecturer assistant, and his duties are to assist students with their tasks and mark their assignments.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="carousel-item">
      <div class="card mb-3" id="cards_" style="width: 80%; margin: 0 auto; background-color: transparent;">
        <div class="row g-0" style="width: 100%;">
          <div class="col-md-5">
            <img src="https://i.postimg.cc/9MxgMX7y/candice-2022.jpg" class="img-fluid rounded-start m-3">
          </div>
          <div class="col-md-7">
            <div class="card-body m-4">
              <h5 class="card-title m-auto" style="font-size: 30px;">Candice Amon</h5>
              <p class="card-text m-auto" style="font-size: 25px;">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Assumenda dolorem ut, non debitis, vel eum vero odio dicta cum in voluptatibus! Illum, ut doloribus dignissimos nam totam ratione incidunt atque.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="carousel-item">
      <div class="card mb-3" id="cards_" style="width: 80%; margin: 0 auto; background-color: transparent;">
        <div class="row g-0" style="width: 100%;">
          <div class="col-md-5">
            <img src="https://i.postimg.cc/2j00W7Qg/Oslin-Johnson.png" class="img-fluid rounded-start m-3">
          </div>
          <div class="col-md-7">
            <div class="card-body m-4">
              <h5 class="card-title m-auto" style="font-size: 30px;">Oslin Johnson</h5>
              <p class="card-text m-auto" style="font-size: 25px;">Imraan is a diligent person, with the keen ability to adapt very well. One of his outstanding talents is that he is great team player and motivator as well. His cool mind allows him to be an effective person.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
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
//     data (){
//     return {
//   arr : [
//   {
//     personName: 'Meezaan Davids',
//     infoText: 'Imraan seems like chill guy who likes to keep to himself. He is a smart person who likes to be challenged and very passionate about soccer. He is a good judge of character, determined and hardworking. Engage conversions and topics with an innovate mindset to things.',
//     imgSrc: 'https://i.postimg.cc/pTFspNgf/t1.jpg',
//   },
//   {
//     personName: 'Kauthar Brandt',
//     infoText: 'Imraan is a friendly individual and a pleasure to work with because of his supporting attributes. He encourages his peers to do their best, which allows him to work with any social group. His very knowledgeable on any topic, so its always lovely to engage in conversion with him.',
//     imgSrc: 'https://i.postimg.cc/9f6FFBY4/t5.jpg',
//   },
//   {
//     personName: 'Brogan Gys',
//     infoText: 'He is a very punctual person,  always on time. He is a very passionate person on the things he loves to do. He is very experienced with HTML, CSS, Bootstrap and thus he always understands his code and work that he is busy with.',
//     imgSrc: 'https://i.postimg.cc/KjQBYJv7/t2.jpg',
//   },
//     {
//     personName: 'Joel Mukanya',
//     infoText: 'Imraan is the definition of a dedicated and professional young talent who has already proven to us that he is work-ready. He gained knowledge of web development, databases, APIs, and more.He volunteers as a lecturer assistant, and his duties are to assist students with their tasks and mark their assignments.',
//     imgSrc: '...',
//   },
//   {
//     personName: 'Candice Amon',
//     infoText: '...',
//     imgSrc: '...',
//   },
//   {
//     personName: 'Oslin Johnson',
//     infoText: '...',
//     imgSrc: '...',
//   },
//   {
//     personName: 'Lindokuhle Mgoqi',
//     infoText: 'Imo has a huge amount of dedication. He is always on time and he make sure that his job is done. He has a humble personality and a good approach.',
//     imgSrc: 'https://i.postimg.cc/SQtcH13q/t3.jpg',
//   },
//   {
//     personName: 'Konke Makubalo',
//     infoText: 'He has displayed extraordinary potential of being a very talented full stack developer. Imraan ideas are unique, seems impossible but are amazing when executed.',
//     imgSrc: 'https://i.postimg.cc/QN5WnNQg/t4.jpg',
//   },
//   {
//     personName: 'Aliyah Du Toit',
//     infoText: 'He is a hard-working and compassionate individual. He never hesitates to assist others in need and is committed to achieving his goals. His determined attitude and welcoming personality allows him to prosper when collaborating with all types of personalities, making him an asset in group projects, as well as individual work.',
//     imgSrc: 'https://i.postimg.cc/mkwdYYVV/t6.jpg',
//   }
// ]
// }
//   }
}
</script>
<style scoped>

#testimonial {
  padding: 40px 0 100px 0;
}

img {
  border-radius: 50%;
}

img {
  border-radius: 8px;
}

/*
.card { 
  border-radius: 20px;
  box-shadow: 3px -3px 3px 3px black;
}
.card:hover {
  border-radius: 20px;
  box-shadow: 3px -3px 3px 3px white;
}
*/
</style>
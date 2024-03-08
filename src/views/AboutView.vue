<!-- <template>
  <div class="about" :style="image">
    <h1>This is an about page</h1>
  </div>
</template> -->

<template>
  <div class="about" :style="image">
    <NavBarComp />
    <div class="profile">
      <h1>Player Profile</h1>
      <div class="infoBlocks container-fluid">
        <div class="leftSide">
          <h2 class="personal">Personal Information</h2>
          <ul>
            <li>Date Of Birth: 27-04-2000</li>
            <li>Location: Mitchells Plain, Cape Town</li>
            <li class="mail">Email: cheslynherman1169@gmail.com</li>
            <li>Mobile Number: 0662647512</li>
            <li>Gender: Male</li>
            <li>Languages: English, Afrikaans</li>
          </ul>
          <h2 >Bio</h2>
          <p >I aspire for greatness. I am someone who is disciplined,
            hardworking and goal driven. My willingness to learn allows me to constantly seek new challenges and I can
            adapt to any environment. I work efficiently and effectively both within a team as well as individually.


          </p><br>
          <p>I'm a gamer, love playing football, going on hikes and swimming. I think crypto is super cool and one day
            I'll own a couple of supercars. Just a few random things for you to know about me. Hope you enjoy the rest
            of this portfolio and have fun!</p>
        </div>
        <div class="rightSide">
          <div class="picture">

            <img src="https://i.ibb.co/6rjzDSm/C12-Cheslyn-Herman.jpg" alt="Cheslyn" class="pic img-fluid">

          </div>
          <div class="specialities">
            <h2>Specialities</h2>
            <ul>
              <li>Resiliance</li>
              <li>Hardworking</li>
              <li>Adaptability</li>
              <li>Discipline</li>
              <li>Confidence</li>
              <li>Humor</li>
            </ul>
          </div>
        </div>

      </div>
    </div>

    <div class="passionBoard">
      <h2>Passions & Visions</h2>
      <p class="swipe">Swipe To What I Like And What My Future Holds</p>
      <div class="slider container-fluid">
        <div class="card">
          <img src="https://i.postimg.cc/RV2SYby3/crypto.jpg" alt="Crypto" />
          <div class="card__content">
            <h3>Crypto</h3>
          </div>
        </div>
        <div class="card">
          <img src="https://i.postimg.cc/d1STWBj6/Unity-Dashboard-Kit.jpg" alt="Web Design" />
          <div class="card__content">
            <h3>Web <br>Design</h3>
          </div>
        </div>
        <div class="card">
          <img src="https://i.postimg.cc/fyXxx8bS/Pin-de-Eliseo-Perez-en-Wallape-R-Portadas-de-revistas-de-arte-Dibujos-P-steres-vintage.jpg" alt="Marvel" />
          <div class="card__content">
            <h3>Marvel</h3>
          </div>
        </div>
        <div class="card">
          <img src="https://i.postimg.cc/MKYnhnvQ/Jujutsu-Kaisen.jpg" alt="Anime" />
          <div class="card__content">
            <h3>Anime</h3>
          </div>
        </div>
        <div class="card">
          <img src="https://i.postimg.cc/3wzjdkjw/Dark-knight-z51-instagram.jpg" alt="Supercars" />
          <div class="card__content">
            <h3>Supercars</h3>
          </div>
        </div>
        <div class="card">
          <img src="https://i.postimg.cc/MGB500pB/pubg-girl-wallpaper.jpg" alt="PUBG" />
          <div class="card__content">
            <h3>PUBG <br>Mobile</h3>
          </div>
        </div>
        <div class="card">
          <img src="https://i.postimg.cc/0j9rXvdv/japan.jpg" alt="Japan" />
          <div class="card__content">
            <h3>Japan</h3>
          </div>
        </div>
        <div class="card">
          <img src="https://i.postimg.cc/k43kmXp0/40-Times-Designers-Went-All-In-And-Designed-The-Most-Fabulous-Examples-Of-Modern-Architecture.jpg" alt="Houses" />
          <div class="card__content">
            <h3>Real <br>Estate</h3>
          </div>
        </div>
        <div class="card">
          <img src="https://i.postimg.cc/HkZCMgPK/What-a-cool-gaming-setup-idea.jpg" alt="PC" />
          <div class="card__content">
            <h3>Future <br>PC Setup</h3>
          </div>
        </div>
        <div class="card">
          <img src="https://i.postimg.cc/Nj3cswCw/Trekking-the-Tour-Du-Mont-Blanc-Stunning-Photos.jpg" alt="Hiking" />
          <div class="card__content">
            <h3>Hiking</h3>
          </div>
        </div>
        <div class="card">
          <img src="https://i.postimg.cc/7L4KnxK9/8dd47022-d806-40d1-8b63-1cdd86f25deb.jpg" alt="Air Max" />
          <div class="card__content">
            <h3>Airmax <br>Collection</h3>
          </div>
        </div>
        
      </div>
      
    </div>


    <div class="startbtn">
      <router-link to="/projects">

        <button class="start">
          Next Level
        </button>
      </router-link>
    </div>
    <FooterComp />
  </div>
</template>

<script>
import FooterComp from '@/components/FooterComp.vue';
import NavBarComp from '@/components/NavBarComp.vue';

export default {
  components: { NavBarComp, FooterComp },
  data() {
    return {
      image: {
        backgroundImage: "url(https://i.postimg.cc/QN0CV7Q0/wp9595650.png)"
      }
    }
  }
}
</script>

<style scoped>
.about {
  background-position: center;
  background-attachment: fixed;
  background-repeat: no-repeat;
  background-size: cover;
  object-fit: cover;
  color: white;

}

.infoBlocks {
  border: 1px solid white;
  max-width: 1700px;
  display: flex;
  margin-top: 20px;
  margin-bottom: 20px;
}
.personal {
  text-align: left !important;
}
.rightSide {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin: auto !important;
}

.leftSide {
  width: 68%;
  border-right: 1px solid white;
}

ul {
  text-align: left;
  margin-top: 30px;
  margin-bottom: 20px;
}

li {
  margin-top: 20px;
}

h1 {
  margin-bottom: 30px;
  margin-top: 20px;
}

h2 {
  margin: 20px;
}

.pic {
  border-radius: 150px;
  width: 250px;
  margin: auto;
}

p {
  line-height: 25px;
}

.picture {
  margin: 20px;
}

.slider {
  display: flex;
  overflow: auto;
  white-space: nowrap;
  padding: 20px;
  
}
.swipe {
    font-size: 12px;
}
.card {
  min-width: 16rem;
  height: 50vh;
  background-color: transparent !important;
  color: #ede4e0 !important;
  border-radius: 0px !important;
  border: 0px !important;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  perspective: 1000px;
  box-shadow: 0 0 0 5px #ffffff80;
  transition: all 0.6s cubic-bezier(0.175, 0.885, 0.32, 1.275);
  margin: 20px;
}
.card img {
  height: 50vh;
  border-radius: 0px !important;
  transition: all 0.6s cubic-bezier(0.175, 0.885, 0.32, 1.275);
}
.card:hover {
  transform: scale(1.05);
  box-shadow: 0 8px 16px rgba(255, 255, 255, 0.2);
  box-shadow: 0 0 0 5px #ffffff80;
}
.card__content {
  position: absolute;
  /* top: 0;
  left: 0; */
  display: flex;
  justify-content: center;
  align-items: center !important;
  height: 100%;
  padding: 20px !important;
  box-sizing: border-box;
  border-radius: 20px !important;
  background-color: transparent;
  transform: rotateX(-90deg);
  transform-origin: bottom;
  transition: all 0.6s cubic-bezier(0.175, 0.885, 0.32, 1.275);
  
}
.card__content h3 {
  font-size: 24px;
}
.card:hover .card__content {
  transform: rotateX(0deg);
}
.card:hover img {
  scale: 0;
}

.startbtn {
  margin-top: 30px;
}

.start {
  padding: 15px;
  width: 450px;
  color: white;
  background: transparent;
  border: 1px solid white;
  box-shadow: 0 0 0 0 transparent;
    -webkit-transition: all 0.2s ease-in;
    -moz-transition: all 0.2s ease-in;
    transition: all 0.2s ease-in;
}

.start:hover {
  box-shadow: 0 0 30px 5px white;
    -webkit-transition: all 0.2s ease-out;
    -moz-transition: all 0.2s ease-out;
    transition: all 0.2s ease-out;
}

@media only screen and (max-width: 1700px){
  .infoBlocks {
    width: 90%;
  }
}
@media only screen and (max-width: 960px){
  .infoBlocks {
    width: 100%;
    flex-direction: column;
    border: none;
  }
  .leftSide {
    border: none;
    margin: auto;
  }
  .personal, ul {
    text-align: center !important;
    text-wrap: wrap;
  }
}
@media only screen and (max-width: 480px) {
  .start {
    width: 90%;
  }
}
@media only screen and (max-width: 570px) {
  .mail {
    font-size: 12px;
  }
}
@media only screen and (max-width: 440px) {
  .mail {
    font-size: 10px;
  }
  .rightSide {
    margin: 0px !important;
    width: 100%;
}
.leftSide {
  width: 100% !important;
}
}
@media only screen and (max-width: 372px) {
  .mail {
    font-size: 9px;
  }
  .personal {
    font-size: 20px;
    text-wrap: wrap;
    margin: 0px;
  }
  .specialities {
    width: 100%;
    /* margin: 0px !important; */
    /* padding: 0px !important; */
}
h2 {
  margin: 10px;
}
}
</style>
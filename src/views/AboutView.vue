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
          <h2>Personal Information</h2>
          <ul>
            <li>Date Of Birth: 27-04-2000</li>
            <li>Location: Mitchells Plain, Cape Town</li>
            <li>Email: cheslynherman1169@gmail.com</li>
            <li>Gender: Male</li>
            <li>Languages: English, Afrikaans</li>
            <li>Willing to Relocate: Yes</li>
          </ul>
          <h2>Bio</h2>
          <p>I aspire for greatness. I am someone who is disciplined,
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
          <div>
            <h2>Specialities</h2>
            <ul>
              <li>Humor</li>
              <li>Confidence</li>
              <li>Looks</li>
              <li>Stylish</li>
              <li>Iconic</li>
              <li>Greatest Of All Time</li>
            </ul>
          </div>
        </div>

      </div>
    </div>

    <div class="passionBoard">
      <h2>Passions & Visions</h2>
      <div class="slider container-fluid">
        <div class="card" style="width: 18rem">
          <img src="" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
              content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
        <div class="card" style="width: 18rem">
          <img src="" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
              content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
        <div class="card" style="width: 18rem">
          <img src="" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
              content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
        <div class="card" style="width: 18rem">
          <img src="" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
              content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
        <div class="card" style="width: 18rem">
          <img src="" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
              content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
        <div class="card" style="width: 18rem">
          <img src="" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
              content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
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
  padding: 10px;
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
}
</style>
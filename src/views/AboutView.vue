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
          <p>I'm a gamer, love playing football, going on hikes and swimming. I think crypto is super cool and one day I'll own a couple of supercars. Just a few random things for you to know about me. Hope you enjoy the rest of this portfolio and have fun!</p>
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

    <div class="skills container-fluid">
      <h2>Soft Skills</h2>
      <div class="skills m-auto">
        <label for="progress-bar" class="d-flex justify-content-center"
          >Leadership Skills</label
        >
        <div
          class="progress m-2"
          role="progressbar"
          aria-label="Animated striped example 20px high"
          aria-valuenow="75"
          aria-valuemin="0"
          aria-valuemax="100"
        >
          <div
            class="progress-bar progress-bar-striped progress-bar-animated"
            style="width: 85%"
          ></div>
        </div>
        <label for="progress-bar" class="d-flex justify-content-center"
          >Interpersonal Skills</label
        >
        <div
          class="progress m-2"
          role="progressbar"
          aria-label="Animated striped example 20px high"
          aria-valuenow="75"
          aria-valuemin="0"
          aria-valuemax="100"
        >
          <div
            class="progress-bar progress-bar-striped progress-bar-animated"
            style="width: 70%"
          ></div>
        </div>
        <label for="progress-bar" class="d-flex justify-content-center"
          >Analytical Skills</label
        >
        <div
          class="progress m-2"
          role="progressbar"
          aria-label="Animated striped example 20px high"
          aria-valuenow="75"
          aria-valuemin="0"
          aria-valuemax="100"
        >
          <div
            class="progress-bar progress-bar-striped progress-bar-animated"
            style="width: 80%"
          ></div>
        </div>
        <label for="progress-bar" class="d-flex justify-content-center"
          >Communication Skills</label
        >
        <div
          class="progress m-2"
          role="progressbar"
          aria-label="Animated striped example 20px high"
          aria-valuenow="75"
          aria-valuemin="0"
          aria-valuemax="100"
        >
          <div
            class="progress-bar progress-bar-striped progress-bar-animated"
            style="width: 91%"
          ></div>
        </div>
        <label for="progress-bar" class="d-flex justify-content-center"
          >Organizational Skills</label
        >
        <div
          class="progress m-2"
          role="progressbar"
          aria-label="Animated striped example 20px high"
          aria-valuenow="75"
          aria-valuemin="0"
          aria-valuemax="100"
        >
          <div
            class="progress-bar progress-bar-striped progress-bar-animated"
            style="width: 69%"
          ></div>
        </div>
      </div>
    </div>
    <div class="tech container-fluid">
      <h2>
        Technical Skills
      </h2>
      <div class="skill-imgs">
        <div class="blocks">
          <img src="https://i.postimg.cc/0QdX6dpv/icons8-bootstrap-150.png" alt="Bootstrap" class="logos img-fluid">
          <p>Bootstrap</p>
        </div>
        <div class="blocks">
          <img src="https://i.postimg.cc/DyfHXDjM/icons8-css-150.png" alt="CSS" class="logos img-fluid">
          <p>CSS</p>
        </div>
        <div class="blocks">
          <img src="https://i.postimg.cc/kMvLD9cS/icons8-figma-150-1.png" alt="Figma" class="logos img-fluid">
          <p>Figma</p>
        </div>
        <div class="blocks">
          <img src="https://i.postimg.cc/FH8BwK9M/icons8-html-150.png" alt="HTML" class="logos img-fluid">
          <p>HTML</p>
        </div>
        <div class="blocks">
          <img src="https://i.postimg.cc/sXR0D0GK/icons8-js-150-1.png" alt="JS" class="logos img-fluid">
          <p>JS</p>
        </div>
      </div>
      <div class="skill-imgs2">
        <div class="blocks">
          <img src="https://i.postimg.cc/zXBJY5HJ/icons8-mysql-100-1.png" alt="MySQL" class="logos img-fluid">
          <p>MySQL</p>
        </div>
        <div class="blocks">
          <img src="https://i.postimg.cc/JzGFTXW3/icons8-wordpress-150-1.png" alt="Wordpress" class="logos img-fluid">
          <p>WordPress</p>
        </div>
        <div class="blocks">
          <img src="https://i.postimg.cc/JhX28W0G/icons8-vuejs-128.png" alt="Vue" class="logos img-fluid">
          <p>Vue.JS</p>
        </div>
        <div class="blocks">
          <img src="https://i.postimg.cc/Kv9VrNCv/icons8-node-js-128.png" alt="Node" class="logos img-fluid">
          <p>Node.JS</p>
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
.skills {
  margin-top: 50px;
  width: 85%;
}

.progress-bar {
  background-color: transparent;
  color: white !important;
}

.progress {
  background-color: transparent;
  border: 1px solid white;
  border-radius: 0px;
  height: 30px;
}

.progress-bar-striped {
    background-image: linear-gradient(45deg,rgba(255,255,255,100) 25%,transparent 25%,transparent 50%,rgba(255,255,255,100) 50%,rgba(255,255,255,100) 75%,transparent 75%,transparent);
    background-size: var(--bs-progress-height) var(--bs-progress-height);
}
.tech {
  margin-top: 50px;
  margin-bottom: 50px;
}
.skill-imgs {
  display: flex;
  justify-content: space-between;
  margin: 20px;
}
.skill-imgs2 {
  display: flex;
  justify-content: space-around;
  margin: 20px;
}

.logos {
  /* aspect-ratio: 5/4; */
  height: 100px; 
  margin-bottom: 20px;
}
.blocks {
  padding: 20px;
  border: 1px solid white;
  width: 250px;
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
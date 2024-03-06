<template>
  <div class="resume" :style="image">
    <NavBarComp />
    <div class="education container-fluid">
      <h1>Education and Experience</h1>
      <div class="container-fluid">
        <ul class="timeline">
          <li class="timeline-inverted">
            <div class="timeline-badge warning"><i class="glyphicon glyphicon-credit-card"></i></div>
            <div class="timeline-panel">
              <div class="timeline-heading">
                <h4 class="timeline-title">LC Studios</h4>
              </div>
              <div class="timeline-body">
                <p>Duration: Oct 2023 - Current</p>
                <p>Position: Intern</p>
                <p>Duties: Working on projects and continuously upskilling each and everyday.</p>
              </div>
            </div>
          </li>
          <li>
            <div class="timeline-badge"><i class="glyphicon glyphicon-check"></i></div>
            <div class="timeline-panel">
              <div class="timeline-heading">
                <h4 class="timeline-title">Life Choices Coding Academy</h4>
              </div>
              <div class="timeline-body">
                <p>Duration: Apr 2023 - Sept 2023</p>
                <p>Qualification: Software and Web Development Course</p>
                <p>Completed</p>
              </div>
            </div>
          </li>
          <li class="timeline-inverted">
            <div class="timeline-badge warning"><i class="glyphicon glyphicon-credit-card"></i></div>
            <div class="timeline-panel">
              <div class="timeline-heading">
                <h4 class="timeline-title">Sigma Connected</h4>
              </div>
              <div class="timeline-body">
                <p>Duration: Nov 2021 - Mar 2023</p>
                <p>Position: Customer Advisor</p>
                <p>Duties: Taking inbound calls and making outbound calls to customers within the UK. Listening to
                  customer needs and providing solutions to customer queries. Liasing with team leader and junior
                  operations manager.</p>
              </div>
            </div>
          </li>
          <li>
            <div class="timeline-badge danger"><i class="glyphicon glyphicon-credit-card"></i></div>
            <div class="timeline-panel">
              <div class="timeline-heading">
                <h4 class="timeline-title">Cape Peninsula University of Technology</h4>
              </div>
              <div class="timeline-body">
                <p>Duration: Jan 2018 - Dec 2020</p>
                <p>Qualification: Diploma in Public Administration and Governance</p>
                <p>Completed</p>
              </div>
            </div>
          </li>
          <!-- <li class="timeline-inverted">
            <div class="timeline-panel">
              <div class="timeline-heading">
                <h4 class="timeline-title">Mussum ipsum cacilds</h4>
              </div>
              <div class="timeline-body">
                <p>Mussum ipsum cacilds, vidis litro abertis. Consetis adipiscings elitis. Pra lá , depois divoltis
                  porris, paradis. Paisis, filhis, espiritis santis. Mé faiz elementum girarzis, nisi eros vermeio, in
                  elementis mé pra quem é amistosis quis leo. Manduma pindureta quium dia nois paga. Sapien in monti
                  palavris qui num significa nadis i pareci latim. Interessantiss quisso pudia ce receita de bolis, mais
                  bolis eu num gostis.</p>
              </div>
            </div>
          </li> -->
          <li class="timeline-inverted">
            <div class="timeline-badge info"><i class="glyphicon glyphicon-floppy-disk"></i></div>
            <div class="timeline-panel">
              <div class="timeline-heading">
                <h4 class="timeline-title">Studio 88</h4>
              </div>
              <div class="timeline-body">
                <p>Duration: Sept 2018 - Jan 2020</p>
                <p>Position: Sales Assistant (Part-Time)</p>
                <p>Duties: Greet customers upon entering store. Assisting with queries and offering excellent customer
                  service. Cleaning the store. Maintain outstanding store condition and visual merchandising standards.
                </p>
              </div>
            </div>
          </li>
          <li>
            <div class="timeline-badge info"><i class="glyphicon glyphicon-floppy-disk"></i></div>
            <div class="timeline-panel">
              <div class="timeline-heading">
                <h4 class="timeline-title">Mondale High School</h4>
              </div>
              <div class="timeline-body">
                <p>Duration: Jan 2013 - Dec 2017</p>
                <p>Qualification: Matric</p>
                <p>Completed</p>
              </div>
            </div>
          </li>
          <!-- <li class="timeline-inverted">
            <div class="timeline-badge success"><i class="glyphicon glyphicon-thumbs-up"></i></div>
            <div class="timeline-panel">
              <div class="timeline-heading">
                <h4 class="timeline-title">Mussum ipsum cacilds</h4>
              </div>
              <div class="timeline-body">
                <p>Mussum ipsum cacilds, vidis litro abertis. Consetis adipiscings elitis. Pra lá , depois divoltis
                  porris, paradis. Paisis, filhis, espiritis santis. Mé faiz elementum girarzis, nisi eros vermeio, in
                  elementis mé pra quem é amistosis quis leo. Manduma pindureta quium dia nois paga. Sapien in monti
                  palavris qui num significa nadis i pareci latim. Interessantiss quisso pudia ce receita de bolis, mais
                  bolis eu num gostis.</p>
              </div>
            </div>
          </li> -->
        </ul>
        <a href="../file/Cheslyn Herman Resumé (1).pdf"  target="_blank"   download class="cv">
          <button class="cv-button">
            CV
          </button>
        </a>
      </div>
    </div>
    <div class="certificates container-fluid">
      <h2>Certificates</h2>
      <div class="images">
        <div class="card">
          <img src="https://i.postimg.cc/CLBS3htj/ca79a3f48fe04db786cbb1a453ea1d7b-1.png"
            class="certs img-fluid card-img-top" alt="">
          <div class="card-body">
            <p class="card-text">Hubspot SEO Certificate</p>
          </div>
        </div>
        <div class="card">
          <img src="https://i.postimg.cc/tCWMrzLs/certificate.png" class="certs img-fluid card-img-top" alt="">
          <div class="card-body">
            <p class="card-text">Grizzly New Marketing SEO Certificate</p>
          </div>
        </div>

      </div>
    </div>
    <div class="skills container-fluid">
      <h2>Soft Skills</h2>
      <div class="skills m-auto">
        <label for="progress-bar" class="d-flex justify-content-center">Leadership Skills</label>
        <div class="progress m-2" role="progressbar" aria-label="Animated striped example 20px high" aria-valuenow="75"
          aria-valuemin="0" aria-valuemax="100">
          <div class="progress-bar progress-bar-striped progress-bar-animated" style="width: 85%"></div>
        </div>
        <label for="progress-bar" class="d-flex justify-content-center">Interpersonal Skills</label>
        <div class="progress m-2" role="progressbar" aria-label="Animated striped example 20px high" aria-valuenow="75"
          aria-valuemin="0" aria-valuemax="100">
          <div class="progress-bar progress-bar-striped progress-bar-animated" style="width: 70%"></div>
        </div>
        <label for="progress-bar" class="d-flex justify-content-center">Analytical Skills</label>
        <div class="progress m-2" role="progressbar" aria-label="Animated striped example 20px high" aria-valuenow="75"
          aria-valuemin="0" aria-valuemax="100">
          <div class="progress-bar progress-bar-striped progress-bar-animated" style="width: 80%"></div>
        </div>
        <label for="progress-bar" class="d-flex justify-content-center">Communication Skills</label>
        <div class="progress m-2" role="progressbar" aria-label="Animated striped example 20px high" aria-valuenow="75"
          aria-valuemin="0" aria-valuemax="100">
          <div class="progress-bar progress-bar-striped progress-bar-animated" style="width: 91%"></div>
        </div>
        <label for="progress-bar" class="d-flex justify-content-center">Organizational Skills</label>
        <div class="progress m-2" role="progressbar" aria-label="Animated striped example 20px high" aria-valuenow="75"
          aria-valuemin="0" aria-valuemax="100">
          <div class="progress-bar progress-bar-striped progress-bar-animated" style="width: 69%"></div>
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
      <router-link to="/contact">

        <button class="start">
          Final Level
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
  components: {
    NavBarComp,
    FooterComp
  },
  data() {
    return {
      image: { backgroundImage: 'url(https://i.postimg.cc/BbXttFyp/wp12437846.jpg)' }
    }
  }
}
</script>

<style scoped>
.resume {
  color: white;
  background-attachment: fixed;
  background-repeat: no-repeat;
  background-size: cover;
  object-fit: cover;
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
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 100) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 100) 50%, rgba(255, 255, 255, 100) 75%, transparent 75%, transparent);
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
.cv {
  margin: 40px;
}
.start, .cv-button {
  padding: 15px;
  width: 450px;
  color: white;
  background: transparent;
  border: 1px solid white;
}

.timeline {
  list-style: none;
  padding: 20px 0 20px;
  position: relative;
  /* margin: 20px; */
}

.timeline:before {
  top: 0;
  bottom: 0;
  position: absolute;
  content: " ";
  width: 3px;
  background-color: #eeeeee;
  left: 50%;
  margin-left: -1.5px;
}

.timeline>li {
  margin-bottom: 20px;
  position: relative;
}

.timeline>li:before,
.timeline>li:after {
  content: " ";
  display: table;
}

.timeline>li:after {
  clear: both;
}

.timeline>li:before,
.timeline>li:after {
  content: " ";
  display: table;
}

.timeline>li:after {
  clear: both;
}

.timeline>li>.timeline-panel {
  width: 46%;
  float: left;
  border: 1px solid #d4d4d4;
  border-radius: 2px;
  padding: 20px;
  position: relative;
  -webkit-box-shadow: 0 1px 6px rgba(0, 0, 0, 0.175);
  box-shadow: 0 1px 6px rgba(0, 0, 0, 0.175);
}

.timeline>li>.timeline-panel:before {
  position: absolute;
  top: 26px;
  right: -15px;
  display: inline-block;
  border-top: 15px solid transparent;
  border-left: 15px solid #ccc;
  border-right: 0 solid #ccc;
  border-bottom: 15px solid transparent;
  content: " ";
}

.timeline>li>.timeline-panel:after {
  position: absolute;
  top: 27px;
  right: -14px;
  display: inline-block;
  border-top: 14px solid transparent;
  border-left: 14px solid #fff;
  border-right: 0 solid #fff;
  border-bottom: 14px solid transparent;
  content: " ";
}

.timeline>li>.timeline-badge {
  color: #fff;
  width: 50px;
  height: 50px;
  line-height: 50px;
  font-size: 1.4em;
  text-align: center;
  position: absolute;
  top: 16px;
  left: 50%;
  margin-left: -25px;
  background-color: white;
  z-index: 100;
  border-top-right-radius: 50%;
  border-top-left-radius: 50%;
  border-bottom-right-radius: 50%;
  border-bottom-left-radius: 50%;
}

.timeline>li.timeline-inverted>.timeline-panel {
  float: right;
}

.timeline>li.timeline-inverted>.timeline-panel:before {
  border-left-width: 0;
  border-right-width: 15px;
  left: -15px;
  right: auto;
}

.timeline>li.timeline-inverted>.timeline-panel:after {
  border-left-width: 0;
  border-right-width: 14px;
  left: -14px;
  right: auto;
}

.timeline-badge.primary {
  background-color: white !important;
}

.timeline-badge.success {
  background-color: white !important;
}

.timeline-badge.warning {
  background-color: white !important;
}

.timeline-badge.danger {
  background-color: white !important;
}

.timeline-badge.info {
  background-color: white !important;
}

.timeline-title {
  margin-top: 0;
  color: inherit;
}

.timeline-body>p,
.timeline-body>ul {
  margin-bottom: 0;
}

.timeline-body>p+p {
  margin-top: 5px;
}

.images {
  display: flex;
  justify-content: space-around;
  margin: 20px;
}

.certs {
  width: 350px;
  border-radius: 0px !important;
}
.card {
  width: 350px;
  background: transparent !important;
  border: 1px solid white;
  border-radius: 0px;
  color: white;
}
.card-img-top {
 
}
</style>
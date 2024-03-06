<template>
    <div class="projects" :style="image">
        <NavBarComp />
        <!-- <div id="carouselExampleInterval" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item active" data-bs-interval="10000">
                    <img src="" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item" data-bs-interval="2000">
                    <img src="" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                    <img src="" class="d-block w-100" alt="...">
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleInterval"
                data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleInterval"
                data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div> -->
        <h1>Projects</h1>
        <div class="accordion accordion-flush" id="accordionFlushExample">
            <div class="accordion-item">
                <h2 class="accordion-header">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                        data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
                        Sannies
                    </button>
                </h2>
                <div id="flush-collapseOne" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
                    <div class="accordion-body">
                        <img src="https://i.ibb.co/7n7nd96/Screenshot-2024-02-26-090759.png" alt="Sannies"
                            class="project-imgs img-fluid">
                        <p class="desc">The final project on the Grizzly SEO learning journey was to create this website
                            on Wordpress. It is based on a design by Grizzly.</p>
                        <a href="https://extra-13.grizzlymarketing.co.za/" target="_blank"><button class="pro-link">Live
                                Link</button></a>

                    </div>
                </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                        data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
                        Automotive Consultancy
                    </button>
                </h2>
                <div id="flush-collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
                    <div class="accordion-body">
                        <img src="https://i.ibb.co/5nHGkSy/Screenshot-2024-02-26-090532.png"
                            alt="Automotive Consultancy" class="project-imgs img-fluid">
                        <p class="desc">The first project on the Grizzly SEO learning journey was to create this website
                            on Wordpress. It is based on a design by Grizzly.</p>
                        <a href="https://dev-13.grizzlymarketing.co.za/" target="_blank"><button class="pro-link">Live
                                Link</button></a>

                    </div>
                </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                        data-bs-target="#flush-collapseThree" aria-expanded="false" aria-controls="flush-collapseThree">
                        Kaiser Pops
                    </button>
                </h2>
                <div id="flush-collapseThree" class="accordion-collapse collapse"
                    data-bs-parent="#accordionFlushExample">
                    <div class="accordion-body">
                        <img src="https://i.ibb.co/5sr8CrN/capstone.png" alt="Kaiser Pops"
                            class="project-imgs img-fluid">
                        <p class="desc">My Capstone fullstack project. The concept is an e-commerce store for a funko
                            pops store.</p>
                        <div class="buttons">
                            <a href="https://kaiser-pops-store.web.app/" target="_blank"><button class="pro-link">Live
                                    Link</button></a>
                            <a href="https://github.com/cheslynherman/Kaiser-Pops" target="_blank"><button
                                    class="pro-link">Github</button></a>
                        </div>

                    </div>
                </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                        data-bs-target="#flush-collapseFour" aria-expanded="false" aria-controls="flush-collapseFour">
                        Appliance Cartel
                    </button>
                </h2>
                <div id="flush-collapseFour" class="accordion-collapse collapse"
                    data-bs-parent="#accordionFlushExample">
                    <div class="accordion-body">
                        <img src="https://i.ibb.co/LvR2LWV/node.png" alt="Appliance Cartel"
                            class="project-imgs img-fluid">
                        <p class="desc">A Fullstack project in which I had a partner who worked on the backend and I
                            worked on the frontend.</p>
                        <div class="buttons">
                            <a href="https://appliance-cartel-node.web.app/" target="_blank"><button
                                    class="pro-link">Live
                                    Link</button></a>
                            <a href="https://github.com/cheslynherman/node-fullstack-eomp" target="_blank"><button
                                    class="pro-link">Github</button></a>
                        </div>

                    </div>
                </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                        data-bs-target="#flush-collapseFive" aria-expanded="false" aria-controls="flush-collapseFive">
                        First Vue Portfolio
                    </button>
                </h2>
                <div id="flush-collapseFive" class="accordion-collapse collapse"
                    data-bs-parent="#accordionFlushExample">
                    <div class="accordion-body">
                        <img src="https://i.ibb.co/dG4zgcJ/Screenshot-2023-10-06-120508.png" alt="Vue Portfolio"
                            class="project-imgs img-fluid">
                        <p class="desc">My first project using Vue.js was to recreate my portfolio. The color scheme was
                            me deciding not to use white for once.</p>
                        <div class="buttons">
                            <a href="https://vue-portfolio-aec91.web.app/" target="_blank"><button class="pro-link">Live
                                    Link</button></a>
                            <a href="https://github.com/cheslynherman/vue-portfolio-eomp" target="_blank"><button
                                    class="pro-link">Github</button></a>
                        </div>

                    </div>
                </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                        data-bs-target="#flush-collapseSix" aria-expanded="false" aria-controls="flush-collapseSix">
                        The Quirky Studio
                    </button>
                </h2>
                <div id="flush-collapseSix" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
                    <div class="accordion-body">
                        <img src="https://i.ibb.co/p4FMdPk/js.png" alt="The Quirky Studio"
                            class="project-imgs img-fluid">
                        <p class="desc">An e-commerce store that was created using JS for the cart functions. The
                            concept is a costume store</p>
                        <div class="buttons">

                            <a href="https://quirkystudio-store.netlify.app/" target="_blank"><button
                                    class="pro-link">Live
                                    Link</button></a>
                            <a href="https://github.com/cheslynherman/js-eomp" target="_blank"><button
                                    class="pro-link">Github</button></a>

                        </div>

                    </div>
                </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                        data-bs-target="#flush-collapseSeven" aria-expanded="false" aria-controls="flush-collapseSeven">
                        BMI Calculator
                    </button>
                </h2>
                <div id="flush-collapseSeven" class="accordion-collapse collapse"
                    data-bs-parent="#accordionFlushExample">
                    <div class="accordion-body">
                        <img src="https://i.ibb.co/J2dKCTv/bmi-calculator.png" alt="BMI Calculator"
                            class="project-imgs img-fluid">
                        <p class="desc">A BMI calculator created using JS for the functionality.</p>
                        <div class="buttons">

                            <a href="https://peppy-bublanina-aea0a3.netlify.app/" target="_blank"><button
                                    class="pro-link">Live Link</button></a>
                            <a href="https://github.com/cheslynherman/bmi-calc" target="_blank"><button
                                    class="pro-link">Github</button></a>
                        </div>

                    </div>
                </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                        data-bs-target="#flush-collapseEight" aria-expanded="false" aria-controls="flush-collapseEight">
                        JS Calculator
                    </button>
                </h2>
                <div id="flush-collapseEight" class="accordion-collapse collapse"
                    data-bs-parent="#accordionFlushExample">
                    <div class="accordion-body">
                        <img src="https://i.ibb.co/ssRVFxC/calc-screenshot.png" alt="JS Calculator"
                            class="project-imgs img-fluid">
                        <p class="desc">A calculator created using JS for the functionality</p>
                        <div class="buttons">

                            <a href="https://resplendent-madeleine-6f8d4e.netlify.app/" target="_blank"><button
                                    class="pro-link">Live Link</button></a>
                            <a href="https://github.com/cheslynherman/calculator" target="_blank"><button
                                    class="pro-link">Github</button></a>
                        </div>

                    </div>
                </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                        data-bs-target="#flush-collapseNine" aria-expanded="false" aria-controls="flush-collapseNine">
                        Bootstrap Portfolio
                    </button>
                </h2>
                <div id="flush-collapseNine" class="accordion-collapse collapse"
                    data-bs-parent="#accordionFlushExample">
                    <div class="accordion-body">
                        <img src="https://i.ibb.co/16VrNTS/bootstrap-portfolio.png" alt="Bootstrap Portfolio"
                            class="project-imgs img-fluid">
                        <p class="desc">My very first project. Built my portfolio using HTML, CSS and bootstrap. Didnt
                            expect it to look so nice honestly speaking but I'm proud of how I've grown since then.</p>
                        <div class="buttons">

                            <a href="https://cheslynherman-bootstrap-portfolio.netlify.app/" target="_blank"><button
                                    class="pro-link">Live Link</button></a>
                            <a href="https://github.com/cheslynherman/bootstrap-project" target="_blank"><button
                                    class="pro-link">Github</button></a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <h2 class="peer">Peer Reviews</h2>
        <p class="swipe">Swipe To See What The Peeps Are Saying About Me</p>
        <div class="slider">
            <!-- <div class="card" >
                <img src="https://i.ibb.co/G9kNrLh/C12-C1-Caryn-Lodewyk-2.jpg" class="card-img-top" alt="Caryn">
                
                <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <p class="card-text"></p>
                    
                </div>
            </div>
            <div class="card" >
                <img src="" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <p class="card-text"></p>
                   
                </div>
            </div>
            <div class="card" >
                <img src="" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <p class="card-text"></p>
                   
                </div>
            </div>
            <div class="card" >
                <img src="" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <p class="card-text"></p>
                    
                </div>
            </div>
            <div class="card" >
                <img src="" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <p class="card-text"></p>
                   
                </div>
            </div>
            <div class="card" >
                <img src="" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <p class="card-text"></p>
                    
                </div>
            </div>
            <div class="card" >
                <img src="" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <p class="card-text"></p>
                    
                </div>
            </div> -->
            <div class="reviews container-fluid">
                <h3>Caryn-Jane Lodewyk</h3>
                <img src="https://i.ibb.co/G9kNrLh/C12-C1-Caryn-Lodewyk-2.jpg" alt="">
                <p>One of Cheslyn's strong suits are communication and teamwork. I've had the pleasure of working with
                    Cheslyn and what I can say from our interactions is that he is a dedicated and hardworking
                    individual.</p>
            </div>
            <div class="reviews container-fluid">
                <h3>Caryn-Jane Lodewyk</h3>
                <img src="https://i.ibb.co/G9kNrLh/C12-C1-Caryn-Lodewyk-2.jpg" alt="">
                <p>One of Cheslyn's strong suits are communication and teamwork. I've had the pleasure of working with
                    Cheslyn and what I can say from our interactions is that he is a dedicated and hardworking
                    individual.</p>
            </div>
            <div class="reviews container-fluid">
                <h3>Caryn-Jane Lodewyk</h3>
                <img src="https://i.ibb.co/G9kNrLh/C12-C1-Caryn-Lodewyk-2.jpg" alt="">
                <p>One of Cheslyn's strong suits are communication and teamwork. I've had the pleasure of working with
                    Cheslyn and what I can say from our interactions is that he is a dedicated and hardworking
                    individual.</p>
            </div>
            <div class="reviews container-fluid">
                <h3>Caryn-Jane Lodewyk</h3>
                <img src="https://i.ibb.co/G9kNrLh/C12-C1-Caryn-Lodewyk-2.jpg" alt="">
                <p>One of Cheslyn's strong suits are communication and teamwork. I've had the pleasure of working with
                    Cheslyn and what I can say from our interactions is that he is a dedicated and hardworking
                    individual.</p>
            </div>
            <div class="reviews container-fluid">
                <h3>Caryn-Jane Lodewyk</h3>
                <img src="https://i.ibb.co/G9kNrLh/C12-C1-Caryn-Lodewyk-2.jpg" alt="">
                <p>One of Cheslyn's strong suits are communication and teamwork. I've had the pleasure of working with
                    Cheslyn and what I can say from our interactions is that he is a dedicated and hardworking
                    individual.</p>
            </div>
            <div class="reviews container-fluid">
                <h3>Caryn-Jane Lodewyk</h3>
                <img src="https://i.ibb.co/G9kNrLh/C12-C1-Caryn-Lodewyk-2.jpg" alt="">
                <p>One of Cheslyn's strong suits are communication and teamwork. I've had the pleasure of working with
                    Cheslyn and what I can say from our interactions is that he is a dedicated and hardworking
                    individual.</p>
            </div>
            <div class="reviews container-fluid">
                <h3>Caryn-Jane Lodewyk</h3>
                <img src="https://i.ibb.co/G9kNrLh/C12-C1-Caryn-Lodewyk-2.jpg" alt="">
                <p>One of Cheslyn's strong suits are communication and teamwork. I've had the pleasure of working with
                    Cheslyn and what I can say from our interactions is that he is a dedicated and hardworking
                    individual.</p>
            </div>
            <div class="reviews container-fluid">
                <h3>Caryn-Jane Lodewyk</h3>
                <img src="https://i.ibb.co/G9kNrLh/C12-C1-Caryn-Lodewyk-2.jpg" alt="">
                <p>One of Cheslyn's strong suits are communication and teamwork. I've had the pleasure of working with
                    Cheslyn and what I can say from our interactions is that he is a dedicated and hardworking
                    individual.</p>
            </div>
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
            image: { backgroundImage: 'url(https://i.postimg.cc/4d8mJP8n/wp12332028.jpg)' }
        }
    }
}
</script>

<style scoped>
.projects {
    color: white;
    background-attachment: fixed;
    background-repeat: no-repeat;
    background-size: cover;
    object-fit: cover;
}

h1,
.peer {
    margin-bottom: 30px;
    margin-top: 20px;
}

h2 {
    margin: 10px;
}

.accordion {
    width: 75%;
    margin: auto;
    --bs-accordion-bg: transparent;
    --bs-accordion-btn-icon: url(https://i.postimg.cc/hvn8tSJ8/icons8-minecraft-sword-48.png);
    --bs-accordion-btn-active-icon: url(https://i.postimg.cc/Y0PvSWxm/icons8-minecraft-axe-48.png);
}

button.accordion-button.collapsed {
    color: white;
    background: transparent !important;
}

.accordion-button:not(.collapsed) {
    color: #ffffff;
    background-color: #cfe2ff00;
    box-shadow: inset 0 calc(-1* var(--bs-accordion-border-width)) 0 #ffffff;
}

.accordion-header {
    color: white !important;
}

.accordion-body {
    background: transparent !important;
    color: white !important;
    padding: 50px;
}

.project-imgs {
    width: 500px;
    margin-bottom: 20px;
}

.desc {
    margin-bottom: 20px;
}

.pro-link {
    padding: 15px;
    width: 350px;
    color: white;
    background: transparent;
    border: 1px solid white;
    margin-bottom: 15px;
}

.buttons {
    display: flex;
    flex-direction: column;
}

.swipe {
    font-size: 12px;
}

.reviews {
    background: transparent;
    color: white;
    border: 1px solid white;
    border-radius: 0px;
    height: 36em;
    margin: 20px;
    min-width: 400px !important;
    text-wrap: wrap;
}

.slider {
    display: flex;
    overflow-x: auto;
    white-space: nowrap;
    padding: 10px;
    
}
</style>
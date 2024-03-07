<template>
    <div>
        <nav class="navbar bg-body-tertiary">
            <div class="container-fluid">
                <!-- <a class="navbar-brand" href="#">Offcanvas navbar</a> -->
                <button class="navbar-toggler menu" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbar"
                    aria-controls="offcanvasNavbar" aria-label="Toggle navigation">
                    <!-- <span class="navbar-toggler-icon"></span> -->
                    <img src="https://i.postimg.cc/7L9ZfDCf/Screenshot-2024-02-27-090253-removebg-preview-1.png" alt="logo" >
                </button>
                <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasNavbar"
                    aria-labelledby="offcanvasNavbarLabel">
                    <div class="offcanvas-header">
                        <button type="button" class="btn" data-bs-dismiss="offcanvas" aria-label="Close">
                            <img src="https://i.postimg.cc/1XZByJTD/icons8-alien-48-1.png" alt="close" class="close-btn">
                        </button>
                    </div>
                    <div class="offcanvas-body">
                        <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
                            <li class="nav-item">
                                <router-link to="/">Home</router-link>
                            </li>
                            <li class="nav-item">
                                <router-link to="/about">About</router-link>
                            </li>
                            <li class="nav-item">
                                <router-link to="/projects">Projects</router-link>

                            </li>
                            <li class="nav-item">
                                <router-link to="/resume">Resum&eacute;</router-link>

                            </li>
                            <li class="nav-item">
                                <router-link to="/contact">Contact</router-link>

                            </li>
                        </ul>

                    </div>
                </div>
            </div>
        </nav>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
img {
    width: 100px;
}

.menu {
    padding: 0px !important;
    border: 3px solid white;
    border-radius: 0px;
}
.navbar {
    background-color: transparent !important;
}

.nav-item {
    border-top: 2px solid white;
    border-bottom: 2px solid white;
    padding: 30px;
    color: white !important;
}

.offcanvas {
    background-color: transparent !important;
}
.offcanvas-header {
    margin-left: auto;
}
.close-btn {
    width: 40px;
}
.btn {
    width: 65px;
    height: 65px; 
    border: 3px solid white;
    padding: 10px;
    border-radius: 0px;
}

.navbar-toggler, .btn {
    box-shadow: 0 0 0 0 transparent;
    -webkit-transition: all 0.2s ease-in;
    -moz-transition: all 0.2s ease-in;
    transition: all 0.2s ease-in;
}
.navbar-toggler:hover, .btn:hover {
    box-shadow: 0 0 30px 5px white;
    -webkit-transition: all 0.2s ease-out;
    -moz-transition: all 0.2s ease-out;
    transition: all 0.2s ease-out;
}
</style>
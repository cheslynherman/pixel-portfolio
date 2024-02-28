<template>
    <div class="contact" :style="image">
        <NavBarComp />
        <h1>Final Round !!!</h1>
        <div class="form">
            <form action="https://formspree.io/f/mjvnravv" method="POST">
                <div class="inputbox">
                    <input name="name" class="form-control" id="exampleFormControlInput1" placeholder="First Name *" required>
                </div>
                <div class="inputbox">
                    <input name="name" class="form-control" id="exampleFormControlInput1" placeholder="Last Name *" required>
                </div>
                <div class="inputbox">
                    <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="Email Address *" required>
                </div>
                <div class="inputbox">

                    <textarea class="form-control" id="exampleFormControlTextarea1" rows="5" placeholder="Leave a Message *" required></textarea>
                </div>
                <div>
                    <button type="reset" class="formbuttons">Reset</button>
                </div>
                <div>
                    <button type="submit" class="formbuttons">Submit</button>
                </div>
            </form>
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
            image: { backgroundImage: "url(https://i.ibb.co/K9q47N0/world.jpg)" }
        }
    }
}
</script>

<style scoped>
h1 {
    color: white;
    margin-bottom: 70px;
    margin-top: 20px;
}
.contact {
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;

}

.form {
    width: 50%;
    height: 70vh;
    margin: auto;
}
::placeholder{
    color: white;
}
input, textarea {
    background: transparent;
    border-radius: 0px;
    padding: 15px;
    color: white;
}
input:hover, textarea:hover {
    background: transparent;
    color: white;
}
.inputbox {
    width: 100%;
    margin: auto;
}
.formbuttons {
    width: 100%;
    color: white;
    background: transparent;
    border: 1px solid white;
    padding: 15px;
    height: 80px;
}
.formbuttons:hover {
    background: white;
    color: black;
}
input {
    height: 80px;
}
</style>
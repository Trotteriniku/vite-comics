<template>
    <footer>
        <IconMenuComponent/>
        <div class="footermenu overflow-hidden">
            <div class="container d-flex justify-content-between p-0   ">

            <div class="d-flex gap-5">
                <div class="me-3 pt-5">
                <h3 class="text-light fw-semibold ">DC COMICS</h3>
                <ul class=" list-unstyled ">
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                </ul>
                <h3 class="text-light fw-semibold">SHOP</h3>
                <ul class=" list-unstyled ">
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                </ul>
            </div>

            <div class="me-5 pt-5">
                <h3 class="text-light fw-semibold">DC</h3>
                <ul class=" list-unstyled ">
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                </ul>
            </div>


            <div class="pt-5 me-5 ">
                <h3 class="text-light fw-semibold">SITES</h3>
                <ul class=" list-unstyled ">
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                    <li><a href="" class=" text-secondary text-decoration-none ">link</a></li>
                </ul>
            </div>
            </div>

            <div>
                <img  src="../assets/images/dc-logo-bg.png" alt="dc logo bg">
            </div>
        </div>
        </div>

        <div class="container p-0  py-4 d-flex justify-content-between ">
            <button type="button" class="btn btn-outline-primary rounded-0 text-light fw-semibold  ">SIGN-UP NOW!</button>

            <div class="d-flex gap-3   align-items-center ">
                <h5 class=" fw-semibold text-primary m-0 ">FOLLOW US</h5>
           
                <div v-for="photoindex in 5">
                    
                 <img  :src="'/images/social'+photoindex+'.png'" alt="profile" > 
                </div>
                
            </div>
        </div>
    </footer>
</template>

<script>
import IconMenuComponent from './IconMenuComponent.vue';
    export default {
    name: 'FooterComponent',
    components : {
    IconMenuComponent
},
    data(){
        return{

        }
    },
    methods:{

    }
    }
</script>

<style lang="scss" scoped>
@use '../assets/variabiles' as *;
footer{
    background-color: $grey--bg-footer;
    .footermenu{
        max-height: 450px;
        background-image: url(../assets/images/footer-bg.jpg);
        background-size: cover;
        background-repeat: no-repeat;

        img{
            margin-top: -101px;
            width: 630px;
        }

    }


}

</style>
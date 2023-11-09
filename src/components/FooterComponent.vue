<template>
    <footer>
        <div class="container d-flex justify-content-between p-0 overflow-hidden  ">
            
            
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
            
            <div class=" overflow-hidden">
                <img  src="../assets/images/dc-logo-bg.png" alt="dc logo bg">
            </div>

            
        </div>
    </footer>
</template>

<script>
    export default {
    name: 'FooterComponent',
    components : {
       
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
    footer{
        max-height: 450px;
        background-image: url(../assets/images/footer-bg.jpg);
        background-size: cover;
        background-repeat: no-repeat;

        img{
            margin-top: -101px;
            width: 630px;
        }
        
    }
</style>
<template>
    <header >
        <div class=" d-flex justify-content-lg-evenly py-4  ">
            <img src="../assets/images/dc-logo.png" alt="dc logo">

            <ul class="nav align-content-center justify-content-end ms-5">
                <li class="nav-item">
                    <a class="nav-link text-secondary"  href.prevent="#">CHARACTERS</a>
                </li>
                <li class="nav-item abar">

                    <a class="nav-link text-secondary" href.prevent="#">COMICS
                        <div class=" bg-primary text-end d-none "></div>
                    </a>
                    
                </li>
                <li class="nav-item">
                    <a class="nav-link text-secondary" href.prevent="#">MOVIES</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-secondary" href.prevent="#">TV</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-secondary" href.prevent="#">GAMES</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-secondary" href.prevent="#">COLLECTIBLES</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-secondary" href.prevent="#">VIDEOS</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-secondary" href.prevent="#">FANS</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-secondary" href.prevent="#">NEWS</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-secondary" href.prevent="#">SHOP</a>
                </li>
            </ul>
        </div>
        
    </header>
</template>

<script>
    export default {
    name: 'HeaderComponent',
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
@use '../assets/variabiles' as *;
    header{
        li{
        font-weight: 700;
        }

        
        img{
          max-width: 90px;
        }
    }

    .abar:hover{
           
        color: red;
        div{
        width: 100%;
        height: 7px;
        display: block;
        }
    } 
       
    
</style>
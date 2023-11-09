<template>
    <header >
        <div class=" d-flex justify-content-lg-evenly py-4  ">
            <img src="../assets/images/dc-logo.png" alt="dc logo">

        <ul class="nav align-content-center justify-content-end ms-5">
            <li class="nav-item">
                <a class="nav-link text-secondary"  href="#">CHARACTERS</a>
            </li>
            <li class="nav-item">
                <a class="nav-link text-secondary" href="#">COMICS</a>
            </li>
            <li class="nav-item">
                <a class="nav-link text-secondary" href="#">MOVIES</a>
            </li>
            <li class="nav-item">
                <a class="nav-link text-secondary" href="#">TV</a>
            </li>
            <li class="nav-item">
                <a class="nav-link text-secondary" href="#">GAMES</a>
            </li>
            <li class="nav-item">
                <a class="nav-link text-secondary" href="#">COLLECTIBLES</a>
            </li>
            <li class="nav-item">
                <a class="nav-link text-secondary" href="#">VIDEOS</a>
            </li>
            <li class="nav-item">
                <a class="nav-link text-secondary" href="#">FANS</a>
            </li>
            <li class="nav-item">
                <a class="nav-link text-secondary" href="#">NEWS</a>
            </li>
            <li class="nav-item">
                <a class="nav-link text-secondary" href="#">SHOP</a>
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
    header{
        li{
        font-weight: 700;
        }
        img{
          max-width: 90px;
        }
    }
    
</style>
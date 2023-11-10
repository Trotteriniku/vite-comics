<template>
    <main>
        <div class="Myjumbotron"></div>

        <div class="container  py-5 px-0 ">
            <div class=" d-flex flex-wrap " > 
                <CardComponent
                v-for="card in cards"
                :thumb="card.thumb" 
                :price="card.price" 
                :series="card.series" 
                :type="card.type" 
                />
                
            </div>    
        </div> 
        
            

        
    </main>
</template>

<script>
import CardComponent from './CardComponent.vue';
import {cards} from '../data/data.js';

    export default {
    name: 'MainComponent',
    components : {
    CardComponent,
},
    data(){
        return{
            cards,
        }
    },
    methods:{

    }   
    }
</script>

<style lang="scss" scoped>
@use '../assets/variabiles' as *;
main{

    background-color: $black--bg;
    .Myjumbotron{
        background-image: url(../assets/images/jumbotron.jpg);
        height:450px;
    }
    
}
</style>
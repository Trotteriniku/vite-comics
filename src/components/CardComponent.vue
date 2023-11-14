<template>
    
            
    <div class="card rounded-0 p-0 border-0 my-3  " style="max-width: 250px;" >
        <div class="myimgcard">
            <img :src="thumb" class="card-img-top w-100  " alt="series">
        </div>
        
        <div class="card-body px-0">
            <h6 class="card-title text-uppercase text-light">{{series}}</h6> 
        </div>
    </div>
            
            
        
</template>

<script>
    export default {
        name: 'CardComponent',
        data(){
            return{
                
                
                
            }
        },
        props: {
                thumb: String, 
                price: String,
                series: String, 
                type: String 
                }
    }
</script>

<style lang="scss" scoped>
@use '../assets/variabiles' as *;

        .card{
            background-color: $black--bg;
            .myimgcard{
                width: 200px;
                height: 200px;
                overflow: hidden;
            }
        }
    
</style>
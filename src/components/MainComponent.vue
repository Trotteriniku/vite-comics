<template>
    <main>
        <div class="container  py-5   ">
            <p class=" text-light fs-3 fw-bold "> => Content goes Here &lt= </p>
        </div>
    </main>
</template>

<script>
    export default {
    name: 'MainComponent',
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
main{
    background-color: $black--bg;
}
</style>
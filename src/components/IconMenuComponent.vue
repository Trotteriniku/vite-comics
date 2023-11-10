<template>

    <div class="bg-primary">
        <div class=" container py-4 ">
            <div class=" row justify-content-between flex-nowrap " >
                <div class="d-flex  mx-0 justify-content-center align-items-center  col-12 col-md-auto" v-for="el in IconMenuList">
                    <img  :src="el.image" alt="profile">
                    <h6 class="ps-3 text-light fw-semibold ">{{el.scope}}</h6>
                </div>
            </div>
        </div>
    </div>

</template>

<script>
    export default {
        name:'IconMenuComponent',
            data(){
                return{
                    IconMenuList:[
                        {
                            image: '/images/icon1.png',
                            scope: 'DIGITAL COMICS'
                        },
                        {
                            image: '/images/icon2.png',
                            scope: 'DC MERCHANDISE'
                        },
                        {
                            image: '/images/icon3.png',
                            scope: 'SUBSCRIPTION'
                        },
                        {
                            image: '/images/icon4.png',
                            scope: 'COMIC SHOP LOCATOR'
                        },
                        {
                            image: '/images/icon5.svg',
                            scope: 'DC POWER VISA'
                        }
                    ]
                }
            }
    }
</script>

<style lang="scss" scoped>
@use '../assets/variabiles' as *;
    img{
        width: 50px;
    }
</style>
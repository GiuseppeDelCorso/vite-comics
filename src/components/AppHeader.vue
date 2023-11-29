<script >

    export default{
        name: "AppHeader",
        data(){
            return{
                link:[
                    {
                     text: "Charatter",
                     url: "www.google.com"
                    },
                    {
                     text: "COMICS",
                     url: "www.google.com"
                    },
                    {
                     text: "MOVIES",
                     url: "www.google.com"
                    },
                    {
                     text: "TV",
                     url: "www.google.com"
                    },
                    {
                     text: "GAMES",
                     url: "www.google.com"
                    },
                    {
                     text: "COLLECTIBLES",
                     url: "www.google.com"
                    },
                    {
                     text: "VIDEOS",
                     url: "www.google.com"
                    },
                    {
                     text: "FANS",
                     url: "www.google.com"
                    },
                    {
                     text: "NEWS",
                     url: "www.google.com"
                    },
                    {
                     text: "SHOP",
                     url: "www.google.com"
                    },
                ]
            }
        }
    }
</script>

<template>
    <div class="container">
        <div class="row">
            <div class="col-4">
                <img class="styleImg my-2" src="/assets/dc-logo.png" alt="">
            </div>
            <div class="col-8 pt-4 ">
                <div class="row text-center d-flex justify-content-evenly pt-3">
                    <div class="col-1 px-0" v-for="testo in link">
                        <a class="fs-7" :href="testo.url">
                            <p >{{ testo.text }}</p>
                        </a>

                    </div>
                </div>

            </div>
        </div>

    </div>

</template>

<style scoped>

    .fs-7{
        font-size: 12px;
        color: black;
        text-decoration: none;
    }
    .styleImg{
        width: 80px;
        height: 80px;
    }

</style>

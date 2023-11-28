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
            <div class="col-2">
                <img src="/ass" alt="">
            </div>
            <div class="col-10">
                <div class="row justify-content-between  text-center">
                    <div class="col-1 px-0" v-for="testo in link">
                        <a :href="testo.url">
                            <p class="fs-6">{{ testo.text }}</p>
                        </a>

                    </div>
                </div>

            </div>
        </div>

    </div>

</template>

<style scoped>

    .fs-6{
        font-size: 2px;
        color: black;
    }

</style>

<script>

export default{

    name: "AppFooter",
    components: {

    }


}

</script>

<template>

    <div class="bgDc">
        <div class="container">
            <div class="row">
                <div class="col-6">
                    <div>
                        <ul class="text-white StyleList pt-4">
                            <li class="fw-bold">DC COMICS</li>
                                <li class="fs-8 py-1 TextColor">
                                    Charatter
                                </li>
                                <li class="fs-8 py-1 TextColor">
                                    COMICS
                                </li>
                                <li class="fs-8 py-1 TextColor">
                                    MOVIES
                                </li>
                                <li class="fs-8 py-1 TextColor">
                                    TV
                                </li>
                                <li class="fs-8 py-1 TextColor">
                                    GAMES
                                </li>
                                <li class="fs-8 py-1 TextColor">
                                    GAMES
                                </li>
                                <li class="fs-8 py-1 TextColor">
                                    COLLECTIBLES
                                </li>
                                <li class="fs-8 py-1 TextColor">
                                    VIDEOS
                                </li>
                                <li class="fs-8 py-1 TextColor">
                                    FANS
                                </li>
                                <li class="fs-8 py-1 TextColor">
                                    NEWS
                                </li>
                                <li class="fs-8 py-1 TextColor">SHOP

                                </li>
                        </ul>
                    </div>
                </div>
                <div class="col-6">
                    <img class="sizeImg" src="/assets/dc-logo-bg.png" alt="">
                </div>
            </div>
        </div>
    </div>

</template>

<style scoped>
    .bgDc{
        background-image: url(/assets/footer-bg.jpg);
    }
    .sizeImg{
        width: 400px;
        height: 400px;
    }
    .StyleList{
        list-style: none;
    }
    .fs-8{
        font-size: 10px;
    }
    .TextColor{
        color: #5b5d5c;
    }


</style>
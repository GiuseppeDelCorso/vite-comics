<script>

export default{

    name: "AppInfoSection",
    data(){
        return{
            buyList: [
                {
                    img: "/assets/buy-comics-digital-comics.png",
                    text: "DIGITAL COMICS"
                },
                {
                    img: "/assets/buy-comics-merchandise.png",
                    text: "DC MERCHANDISE"
                },
                {
                    img: "/assets/buy-comics-shop-locator.png",
                    text: "SUBSCRIPTION"
                },
                {
                    img: "/assets/buy-comics-subscriptions.png",
                    text: "COMIC SHOP LOCATOR"
                },
                {
                    img: "/assets/buy-dc-power-visa.svg",
                    text: "DC POWER VISA"
                },
            ]
        }
    }
}

</script>

<template>

    <div class="BgAzzurre">
        <div class="container">
            <div class="row justify-content-around">
                <div class="col-2 d-flex align-items-center" v-for="buyInfo in buyList">
                    <img class="img-fluid sizeImg my-5" :src="buyInfo.img" alt="">
                    <p class="pt-3 fs-7 text-white px-2">{{ buyInfo.text }}</p>
                </div>
            </div>
        </div>
    </div>

</template>

<style scoped>
.BgAzzurre{
    background-color: cornflowerblue;
}
.sizeImg{
    width: 50px;
    height: 50px;
}.fs-7{
    font-size: 11px;
}

</style>
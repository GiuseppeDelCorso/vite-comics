<script>

export default{
    
    name: "AppMain",
    props: ["series"],
    data() {
        return{

        }
    }


}

</script>

<template>
    <div class="BgNero">
        <div class="container">
            <div class="row">
                <div class="col-2 d-flex flex-column align-items-center" v-for="product in series">
                    <img class="imgStyle" :src="product.thumb" alt="">
                    <div class="py-4 text-white fs-7 text-center">{{product.series}}</div>
                </div>
            </div>
        </div>
        <div class="container">
            <div class="row">
                <div class="col-12">
                    
                </div>
            </div>
        </div>
    </div>        


</template>

<style scoped>

h1{
    background-color: black;
    color: white;
}
.BgNero{
    background-color: black;
}
.imgStyle{
    width: 150px;
    height: 150px;
    object-fit: cover;
    

}
.fs-7{
        font-size: 12px;
       font-weight: bold;
    }

</style>
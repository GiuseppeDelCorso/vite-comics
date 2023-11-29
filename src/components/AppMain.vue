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
        <div>
            <img class="imgJuboStyle" src="/assets/jumbotron.jpg" alt="">
            <button class="styleJuboButton">CURRENT SERIES</button>
        </div>
        <div class="container">
            <div class="row mt-5">
                <div class="col-2 d-flex flex-column align-items-center" v-for="product in series">
                    <img class="imgStyle" :src="product.thumb" alt="">
                    <div class="py-4 text-white fs-7 text-center">{{product.series}}</div>
                </div>
            </div>
        </div>
        <div class="container">
            <div class="row d-flex justify-content-center py-3">
                <div class="col-2">
                    <button class="styleButton">LOAD MORE</button>
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
.imgJuboStyle{
    height: 400px;
    width: 100%;
    object-fit: cover;
    object-position: top;
}
.styleJuboButton{
    width: 200px;
    height: 40px;
    background-color: #0383f9;
    color: white;
    font-weight: bold;
    font-size: 15px;
    border: none;
    position: relative;
    bottom: 20px;
    left: 300px;
}
.fs-7{
        font-size: 12px;
       font-weight: bold;
    }
.styleButton{
    
    width: 170px;
    height: 35px;
    background-color: #0383f9;
    color: white;
    font-weight: bold;
    font-size: 15px;
    border: none;
    
}
</style>
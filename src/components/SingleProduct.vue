<template>
    <div class="product">
        <div class="product-img">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
        </div>
        <div class="product-title">
            Prova
        </div>
    </div>
</template>

<script>
export default {
    name:'SingleProduct'
}
</script>

<style lang="scss"  scoped>

.product{
    width:calc( (100% / 6) - 20px);
    height: auto;
    margin: 30px 10px;
    padding: 0 10px;

    .product-img{
        width: 100%;
        height: 200px;
        overflow: hidden;
        margin-bottom: 20px;
    }

    .product-title{
        text-transform: uppercase;
        

    }

}


</style>
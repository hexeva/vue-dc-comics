<template>
    <div class="product">
        <div class="product-img">
            <img :src="SingleObject.thumb" :alt="SingleObject.type">
        </div>
        <div class="product-title">
            <h3>{{SingleObject.series}}</h3>
        </div>
    </div>
</template>

<script>
export default {
    name:'SingleProduct',
    props:['SingleObject'],
}
</script>

<style lang="scss"  scoped>
@import '../style/variables.scss';;

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
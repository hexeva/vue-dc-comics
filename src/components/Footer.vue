<template>
    <footer>
        io sono il footer
    </footer>
</template>

<script>
    export default{
        name:'Footer',

}
</script>




<style lang="scss" scoped>
@import '../style/variables.scss';
@import '../style/mixins.scss';


footer {
    width: 100%;
    background-image: url(../assets/img/footer-bg.jpg);
    @include background_general;
    
    // test
    height: 400px;
}

</style>
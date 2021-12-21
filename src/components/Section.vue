<template>

    <section>
        <div class="container">
            <div class="logos">
                <!-- single template -->
                <div class="logo-contents">
                    <div class="single-logo">
                        <img src="../assets/img/buy-comics-digital-comics.png" alt="dc logo">
                    </div>
                    <span>digital comics</span>
                </div>
                <!-- fine single template -->
                <!-- single template -->
                <div class="logo-contents">
                    <div class="single-logo">
                        <img src="../assets/img/buy-comics-merchandise.png" alt="merchandise logo">
                    </div>
                    <span>dc merchandise</span>
                </div>
                <!-- fine single template -->
                <!-- single template -->
                <div class="logo-contents">
                    <div class="single-logo">
                        <img src="../assets/img/buy-comics-subscriptions.png" alt="subscription logo">
                    </div>
                    <span>Subscription</span>
                </div>
                <!-- fine single template -->
                <!-- single template -->
                <div class="logo-contents">
                    <div class="single-logo">
                        <img src="../assets/img/buy-comics-shop-locator.png" alt="shop locator logo">
                    </div>
                    <span>comic shop locator</span>
                </div>
                <!-- fine single template -->
                <!-- single template -->
                <div class="logo-contents">
                    <div class="single-logo">
                        <img src="../assets/img/buy-dc-power-visa.svg" alt="dc battery logo">
                    </div>
                    <span>dc power visa</span>
                </div>
                <!-- fine single template -->
                
            </div>
        </div>
    </section>
    
</template>

<script>
export default{
    name:'Section',
}
</script>

<style lang="scss" scoped>
@import '../style/variables.scss';

section{
    width: 100%;
    height: 160px;
    background-color: $brand_hover_color;
    color: white;
    text-transform: uppercase;
    font-size: 15px;
}

.logos{
    width:100%;
    height: 100%;
    display: flex;
    justify-content: space-around;
    

    .logo-contents{
        display: flex;
        align-items: center;

         .single-logo{
            width: 45px;
            margin-right: 20px;
        }

    }

   
}

</style>
<template>
    <section>
        <div class="container">
            <div class="footer-btn">
                <a href="#">SIGN-UP-NOW</a>
            </div>
            <div class="links">
                <ul>
                    <li>
                        <a href="#">FOLLOW US</a>
                    </li>
                    <li>
                        <img src="../assets/img/footer-facebook.png" alt="facebook logo">
                    </li>
                    <li>
                        <img src="../assets/img/footer-twitter.png" alt="twitter logo">
                    </li>
                    <li>
                        <img src="../assets/img/footer-youtube.png" alt="youtube logo">
                    </li>
                    <li>
                        <img src="../assets/img/footer-pinterest.png" alt="pinterest logo">
                    </li>
                    <li>
                        <img src="../assets/img/footer-periscope.png" alt="periscopo logo">
                    </li>
                </ul>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name:'FooterBottom',

}
</script>


<style lang="scss" scoped>
@import '../style/variables.scss';

section{
    background-color: darken($brand_footer_color, 30%);
    width: 100%;
    // test
    height: 100px;

    .container{
        display: flex;
        
        .footer-btn{
            width: 50%;
            height: 100%;
            display: flex;
            align-items: center;

                 a{
                    font-size: 20px;
                    color:$brand_secondary_color;
                    background-color: darken($brand_footer_color, 30%);
                    border: 2px solid $brand_hover_color;
                    padding:13px 22px;
                }
   
        }
        .links{
            width: 50%;
            height: 100%;
            ul{
                height: 100%;
                display: flex;
                align-items: center;
                justify-content: end;

                li{
                    margin: 0 20px;
                    a{
                        color: $brand_hover_color;
                        font-size: 20px;
                    }
                }
            }
        }
    }
    // end container
   
}

</style>
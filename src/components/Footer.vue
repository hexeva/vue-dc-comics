<template>
    <footer>
        <div class="footer-top">
            <div class="container">
                  <!-- links section -->
                    <div class="links-section">
                        <div class="links">
                            <h2>dc comics</h2>
                            <ul>
                                <li>
                                    <a href="#">Characters</a>
                                </li>
                                <li>
                                    <a href="#">Comics</a>
                                </li>
                                <li>
                                    <a href="#">Movies</a>
                                </li>
                                <li>
                                    <a href="#">TV</a>
                                </li>
                                <li>
                                    <a href="#">Games</a>
                                </li>
                                <li>
                                    <a href="#">Videos</a>
                                </li>
                                <li>
                                    <a href="#">News</a>
                                </li>
                            </ul>
                            <h2>shop</h2>
                            <ul>
                                <li>
                                    <a href="#">Shop DC</a>
                                </li>
                                <li>
                                    <a href="#">Shop DC Collectibles</a>
                                </li>
                            </ul>
                        </div>
                        <!-- end links -->
                        <div class="links">
                            <h2>dc</h2>
                            <ul>
                                <li>
                                    <a href="#">Terms of Use</a>
                                </li>
                                <li>
                                    <a href="#">Privacy policy (New)</a>
                                </li>
                                <li>
                                    <a href="#">Ad choices</a>
                                </li>
                                <li>
                                    <a href="#">Advertising</a>
                                </li>
                                <li>
                                    <a href="#">Jobs</a>
                                </li>
                                <li>
                                    <a href="#">Subscriptions</a>
                                </li>
                                <li>
                                    <a href="#">Talent Workshops</a>
                                </li>
                                 <li>
                                    <a href="#">CPSC Certificated</a>
                                </li>
                                <li>
                                    <a href="#">Rating</a>
                                </li>
                                <li>
                                    <a href="#">Shop Help</a>
                                </li>
                                <li>
                                    <a href="#">Contact Us</a>
                                </li>
                            </ul>
                            
                        </div>
                        <!-- end links -->
                        <div class="links">
                            <h2>sites</h2>
                            <ul>
                                <li>
                                    <a href="#">DC</a>
                                </li>
                                <li>
                                    <a href="#">MAD Magazine</a>
                                </li>
                                <li>
                                    <a href="#">DC Kids</a>
                                </li>
                                <li>
                                    <a href="#">Dc Universe</a>
                                </li>
                                <li>
                                    <a href="#">DC Power Visa</a>
                                </li>
                                
                            </ul>
                           
                        </div>
                        <!-- end links -->
                    </div>

                    <!-- end links sections -->
                    <div class="dc_logo">
                        <img src="../assets/img/dc-logo-bg.png" alt="dc logo">
                    </div>
            </div>
                <!-- end container -->
                
        </div>
        <!-- END FOOTER TOP -->

        <FooterBottom />
          
          
    </footer>
</template>

<script>

import FooterBottom from "./FooterBottom.vue";

    export default{
        name:'Footer',
        components:{
            FooterBottom,
        },

}
</script>




<style lang="scss" scoped>
@import '../style/variables.scss';
@import '../style/mixins.scss';


footer {
    width: 100%;

        .footer-top{
            background-image: url(../assets/img/footer-bg.jpg);
            @include background_general;
            overflow: hidden;

            .container{
                    display: flex;
                    position: relative;

                        .links-section{
                            width: 60%;
                            padding: 35px 0;
                            display: flex;

                            .links{
                                margin-right:30px;

                                li{
                                margin: 8px 0;
                                a{
                                    color:$brand_footer_color;
                                }
                            }

                            }
                            
                        }

                        .dc_logo{
                            width: 40%;
                            position: absolute;
                            top:-29%;
                            right: 0;
                        }


                }
                // end container

            
           

           
        }
        // end footer top

        

        
    
}
h2{
    margin:20px 0;
}

</style>
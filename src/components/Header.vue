<template>
    <header>

        <div class="container">
            <div class="left-col">
                <div class="logo">
                    <img src="../assets/img/dc-logo.png" alt="logo dc">

                </div>
            </div>
            <div class="right-col">
                <ul>
                    <li v-for="(link,index) in links" :key="index">
                        <a :class="{active: link.current}" :href="link.url">{{link.text}}</a>
                    </li>
                   

                    

                </ul>
            </div>

        </div>
    </header>
</template>

<script>
    export default{
        name:'Header',
        data:function(){
            return{

                links:[
                    {
                        text:'characters',
                        url:'#',
                        current:false,
                    },
                       {
                        text:'comics',
                        url:'#',
                        current:true,
                    },
                       {
                        text:'movies',
                        url:'#',
                        current:false,
                    },
                       {
                        text:'tv',
                        url:'#',
                        current:false,
                    },
                       {
                        text:'games',
                        url:'#',
                        current:false,
                    },
                       {
                        text:'collectibles',
                        url:'#',
                        current:false,
                    },
                       {
                        text:'video',
                        url:'#',
                        current:false,
                    },
                       {
                        text:'fans',
                        url:'#',
                        current:false,
                    },
                       {
                        text:'news',
                        url:'#',
                        current:false,
                    },
                       {
                        text:'shop',
                        url:'#',
                        current:false,
                    },

                ],

            };
        }

}
</script>


<style lang="scss" scoped>
@import '../style/variables.scss';




    header{
        width: 100%;
        height: 120px;
        line-height: 120px;
        font-weight: bold;
        text-transform: uppercase;
        color:$brand_primary_color;
        margin-bottom: 5px;
       
        

          .left-col{
        height: 100%;
        width: 30%;
        float: left;
        
        
        }
    
     .right-col{
        width: 70%;
        min-width:400px;
        height: 100%;
        float: left; 
        text-align: right;

             ul li{
            display: inline-block;
            margin-right: 30px;
                a {
                    display: inline-block;
                   

                }
            }

        }

      
    }
  
    .logo{
        width: 85px;
        display: inline-block;

        img{
            vertical-align: middle;
        }
    }

    .active{
        border-bottom: 5px solid $brand_hover_color;
        color:$brand_hover_color
    }
   
    
</style>

<template>
    <header>
        <div class="menu-container">
            <div class="left-col">
                <div class="logo">
                    <img src="../assets/img/dc-logo.png" alt="logo dc">

                </div>
            </div>
            <div class="right-col">
                <ul>
                    <li>
                        <a href="#">characters</a>
                    </li>
                    <li>
                        <a href="#">Comics</a>
                    </li>
                    <li>
                        <a href="#">Movies</a>
                    </li>
                    <li>
                        <a href="#">tv</a>
                    </li>
                    <li>
                        <a href="#">games</a>
                    </li>
                    <li>
                        <a href="#">Prova</a>
                    </li>
                    <li>
                        <a href="#">Prova</a>
                    </li>
                    <li>
                        <a href="#">Prova</a>
                    </li>
                    <li>
                        <a href="#">Prova</a>
                    </li>
                    <li>
                        <a href="#">Prova</a>
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
                        current:false,
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
        color:$brand_primary_color;
       
        

          .left-col{
        height: 100%;
        width: 40%;
        float: left;
        
        
        }
    
     .right-col{
        width: 60%;
        height: 100%;
        float: left; 

             ul li{
            display: inline-block;
            margin-right: 30px;
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
   
    
</style>

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
                    <li>CHARACTERS</li>
                    <li>CHARACTERS</li>
                    <li>CHARACTERS</li>
                    <li>CHARACTERS</li>
                    <li>CHARACTERS</li>
                    <li>CHARACTERS</li>
                    <li>CHARACTERS</li>
                    <li>CHARACTERS</li>
                    <li>CHARACTERS</li>
                    <li>CHARACTERS</li>

                </ul>
            </div>

        </div>
    </header>
</template>

<script>
    export default{
        name:'Header',

}
</script>


<style scoped>
    header{
        width: 100%;
        height: 120px;
        line-height: 120px;
        /* test */
        background-color: aquamarine;
    }
    .left-col{
        height: 100%;
        width: 50%;
        float: left;
        
        
    }
    .right-col{
        width: 50%;
        height: 100%;
        float: left; 
    }

    .right-col ul li{
        display: inline-block;
    }
    .logo{
        width: 85px;
        display: inline-block;
    }
    .logo img{
        vertical-align: middle;
    }
    
</style>

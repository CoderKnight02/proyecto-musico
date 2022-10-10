<template>
    

    <h2>Lo Mas reciente</h2>  
    
    <div>
        <ul>
            <li> Canciones </li>
            <li> Videos </li>
            <li> Fotos </li>
        </ul>
        <div class="box"></div>
    </div>
    
</template>

<style scoped>
    
    h2{
        font-size: 3rem;
    }
    li,h2{
        color: white;
    }
    ul{
        display: flex;
        gap: 20px;
        list-style-type: none;
        padding: 0;
    }
    li{
        margin: 0;
        font-size: 2rem;
    }
    .box{
        background-color: white;
        border-radius: 10px;
        width: 500px;
        height: 500px;
    }
</style>
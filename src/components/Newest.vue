<template>
    

    <h2 id="new">Lo más reciente</h2>  
    
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
        margin-top: 10vmax;
    }
    ul{
        display: flex;
        gap: 20px;
    }
    li{
        font-size: var(--fs-base);
    }
    .box{
        background-color: white;
        border-radius: 10px;
        width: min(80vw, 500px);
        height: min(80vw, 500px);
    }

    @media (max-width: 850px){
        h2{
            text-align: center;
        }
        .box{
            margin-inline: auto;

        }
        ul{
            position: relative;
            display: flex;
            justify-content: center;
        }
        
    }

</style>
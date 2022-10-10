<template>
    <nav>
        <h1>Alec</h1>
        <ul>
            <li class="list"><a href="#">Sobre mi</a></li>
            <li class="list"><a href="#">Lo más reciente</a></li>
            <li class="list"><a href="#">Contáctame</a></li>
        </ul>
    </nav>
</template>

<style scoped>
    
    nav{
        display: flex;
        justify-content: space-evenly;
        align-items: center;
    }
    ul{
        display: flex;
        justify-content: flex-end;
        margin-left: auto;
        flex-basis: 45%;
        gap: 10px;
        list-style-type: none;
        margin: 0;
        padding: 0;
    }
    li{
        margin-right: 10px;
    }
    a{
        font-size: 1.5rem;
        text-decoration: none;
        color: white;
    }
    h1{
        color: white;
        text-align: right;
        flex-basis: 40%;
        font-size: 5rem;
    }
</style>
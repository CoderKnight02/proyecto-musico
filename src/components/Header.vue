<template>
    <nav>
        <h1>Alec</h1>
        <ul>
            <li class="list"><a href="#about">Sobre mi</a></li>
            <li class="list"><a href="#">Lo más reciente</a></li>
            <li class="list"><a href="#">Contáctame</a></li>
        </ul>
    </nav>
    <div>

        <p>
            Hola mi nombre es Alec.
            <span>Un placer tenerte por aca.</span>
        </p>

        <a class="butt">Contactame!</a>

    </div>
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
    }
    li{
        margin-right: 10px;
    }
    
    li a{
        font-size: 1.5rem;
    }
    span{
        display: block;
        color: #f42c04;

    }

    p{
        margin-top: 150px;
        font-size: 2.2rem;
    }

</style>
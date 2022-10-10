<template>
    <nav>
        <h1>Alec</h1>
        <ul>
            <li class="list"><a href="#">Sobre mi</a></li>
            <li class="list"><a href="#">Lo más reciente</a></li>
            <li class="list"><a href="#">Contáctame</a></li>
        </ul>
    </nav>
    <div>

        <p>
            Hola mi nombre es Alec.
            <span>Un placer tenerte por aca.</span>
        </p>

        <a class="butt">Contactame</a>

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
        list-style-type: none;
        margin: 0;
        padding: 0;
    }
    li{
        margin-right: 10px;
    }
    
    li a{
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

    span{
        display: block;
        color: #f42c04;

    }

    .butt{
        border-radius: 10px;
        color: white;
        background-color: #f42c04;
        padding: 10px 15px ;
        font-size: 2rem;
        font-weight: 600;
        text-transform: uppercase;
        letter-spacing: .1rem;
        transition: .3s;
    }
    .butt:hover{
        color: #f42c04;
        background-color: white;
    }
    .butt:active{
        background-clip: #aaa;
    }

    div{
        margin-left: 10vw;
    }
    p{
        margin-top: 150px;
        color: white;
        font-size: 2.2rem;
    }

</style>
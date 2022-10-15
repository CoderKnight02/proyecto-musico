<template>
    <nav>
        <h1>Alec</h1>
        <ul>
            <li class="list"><a href="#about">Sobre mi</a></li>
            <li class="list"><a href="#new">Lo más reciente</a></li>
            <li class="list"><a href="#contact">Contáctame</a></li>
        </ul>
    </nav>
    <div>

        <p class="ph">
            Hola mi nombre es Alec.
            <span>Un placer tenerte por aca.</span>
        </p>

        <a href="#contact" class="butt">Contactame!</a>

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
        gap: 25px;
        margin-right: 20px;
    }
    /* li{
        margin-right: 10px;
    } */
    
    li a{
        font-size: 1.5rem;
    }
    span{
        display: block;
        color: #f42c04;

    }

    .ph{
        margin-top: 150px;
        font-size: 2.2rem;
    }

    @media (max-width: 1110px) {
        li a{
            font-size: 1.5rem; 
        }
        .ph{
            font-size: 1.8rem;
        }
        .butt{
            font-size: 1.9rem;
        }
        ul{
            flex-basis: unset;
        }

    }

    @media (max-width: 880px) {
        li a{
            font-size: 1.2rem; 
        }
        .ph{
            font-size: 1rem;
        }
        .butt{
            font-size: 1rem;
        }
        ul{
            flex-basis: unset;
        }

    }

    @media (max-width: 610px) {
        li a{
            font-size: .9rem; 
        }
        .ph{
            font-size: .9rem;
        }
        .butt{
            font-size: .9rem;
        }
        ul{
            flex-basis: unset;
        }

    }


</style>
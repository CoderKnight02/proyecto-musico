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
    :root{
        --fs-base: clamp(1rem, 2vw, 2.2rem);
    }
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
    
    li a{
        font-size: var(--fs-base);
    }
    span{
        display: block;
        color: #f42c04;

    }
    .ph{
        margin-top: 150px;
        font-size: var(--fs-base-ph);
    }

    @media (max-width: 1110px) {
        ul{
            flex-basis: unset;
        }

    }

    @media (max-width: 880px) {
        ul{
            flex-basis: unset;
        }

    }

    @media (max-width: 610px) {
        ul{
            flex-basis: unset;
        }

    }


</style>

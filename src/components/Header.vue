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

<!-- 

--font-size-sm: clamp(0.8rem, 0.16vw + 0.76rem, 0.89rem);
--font-size-base: clamp(1rem, 0.33vw + 0.92rem, 1.19rem);
--font-size-md: clamp(1.25rem, 0.59vw + 1.11rem, 1.58rem);
--font-size-lg: clamp(1.56rem, 0.97vw + 1.34rem, 2.11rem);
--font-size-xl: clamp(1.95rem, 1.52vw + 1.6rem, 2.81rem);
--font-size-xxl: clamp(2.44rem, 2.31vw + 1.9rem, 3.75rem);
--font-size-xxxl: clamp(3.05rem, 3.44vw + 2.25rem, 5rem);

 -->
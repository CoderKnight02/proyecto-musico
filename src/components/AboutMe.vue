<template>
    <div class="cont" id="about">
        <div>
            <h2>
                Sobre mi
            </h2>
            <p>
                Soy Alec, cantante y compositor cubano. He estado trabajando duro para construir mi base de fans. Comencé publicando mi música en redes sociales como YouTube y Facebook. Luego comencé a recibir solicitudes de fans de todo el mundo para que mis canciones se publicaran en otras plataformas. Si te interesa y quieres saber lo que hago solo hecha un vistazo<span class="visible"> a la derecha.</span>
            </p>
        </div>

        <ul>
            <h3>Géneros</h3>
            <div class="separator">
                <li>Balada</li>
                <li>Pop</li>
            </div>
            <div class="separator">
                <li>Dancehall</li>
                <li>Urbano</li>
            </div>
        </ul>
    </div>
</template>

<style scoped>

    .cont{
        background-image: url(../assets/images/VectorCirculo.svg);
        background-position: top 50% right 0;
        background-size: contain;
        background-repeat: no-repeat;
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-top: clamp(2rem, 38vw,60rem);
        
    }

    h3{
        font-size: 2rem;
    }
    p{
        width: 50vw;
        font-size: clamp(1.25rem, 2vw, 1.8rem);
    }

    ul{
        list-style-type: none;
        padding: 0;
    }

    li{
        text-align: center;
        font-size: 1.6rem;
        background-color: #4f2e2e;
        padding: 5px 15px;
        border-radius: 20px;
        margin: 5px;
        display: inline;
    }
    .vect{
        height: 100%;
        position: relative;
        flex-basis: 50%;
    }
    .separator{
        margin-top: 20px;
    }

    img{
        top: 0;
        right:-20px;
        position: absolute;
        z-index: -1;
        width: 500px;
    }

    @media (max-width: 850px) {
        .visible{
            display: none;
        }
        .cont{
            flex-direction: column;
            background-image: none;
            padding: 0;
        }
        .cont > * > *{
            width: 90vw;
        }
    }

</style>
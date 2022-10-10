<template>
    <div class="cont" id="about">
        <div>
            <h2>
                Sobre mi
            </h2>
            <p>
                Soy Alec, cantante y compositor cubano. He estado trabajando duro para construir mi base de fans. Comencé publicando mi música en redes sociales como YouTube y Facebook. Luego comencé a recibir solicitudes de fans de todo el mundo para que mis canciones se publicaran en otras plataformas. Si te interersa y quieres saber lo que hago solo hecha un vistazo a la derecha.
            </p>
        </div>

        <div class="vect">
            <h3>Géneros</h3>

            <img src="../assets/images/VectorCirculo.svg" alt="Circulo">
            
            <ul>
                <div class="separator">
                    <li>Valada</li>
                    <li>Pop</li>
                </div>
                <div class="separator">
                    <li>Dancehall</li>
                    <li>Urbano</li>
                </div>
            </ul>
        </div>
    </div>
</template>

<style scoped>

    .cont{
        height: 400px;
        display: flex;
        justify-content: space-around;
        margin-top: 600px;
    }

    h3{
        font-size: 2rem;
        position:absolute;
        top: 25%;
        left: 30%;
    }
    p{
        width: 50vw;
        font-size: 1.6rem;
    }

    ul{
        list-style-type: none;
        padding: 0;
    }

    ul{
        position: absolute;
        top: 40%;
        left: 40%;
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

</style>
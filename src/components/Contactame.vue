<template>
    <div class="wraper">

        <h2 id="contact">Contáctame</h2>
        <div class="form">
            <nav>
                <ul>
                    <li><a href="#"><i class="ri-youtube-fill"></i></a></li>
                    <li><a href="#"><i class="ri-spotify-fill"></i></a></li>
                    <li><a href="#"><i class="ri-facebook-circle-fill"></i></a></li>
                    <li><a href="#"><i class="ri-twitter-fill"></i></a></li>
                    <li><a href="#"><i class="ri-apple-fill"></i></a></li>
                </ul>
            </nav>
            
            <form>
                <label for="name">Nombre</label>
                <input type="text" id="name" name="name">
                <label for="email">Correo</label>
                <input type="email" id="email" name="email">
                <label for="msg">Mensaje</label>
                <textarea name="msg" id="msg" cols="30" rows="10"></textarea>
                <a class="butt butt-comp">Contactame!</a>
            </form>
        </div>

    </div>
</template>

<style scoped>
    .wraper{
        margin-left: -100px;
        margin-top: 300px;
        display: flex;
        align-items: center;
        flex-direction: column;
    }
    .form{
        display: flex;
        gap: 10px;
    }
    
    form{
        width: 400px;
        border-radius: 10px;
        background-color: #222020;
        padding: 20px;
    }

    label{
        margin: 10px 0;
        display: block;
    }
    
    li{
        margin-bottom: 20px;
    }

    ul a{
        transition: color .3s;
        font-size: 3rem;
        color: #f42c04;
        text-decoration: none;
    }

    ul a:hover{
        color: white;
    }

    input, textarea{
        width: 100%;
        display: block;
        background-color: #2d2b2b;
        padding: 10px;
        border-radius: 10px;
        border: 1px solid #5e5c5c;
    }
    textarea{
        margin-bottom: 30px;
    }
    .butt-comp{
        float: right;
        font-size: 1rem;
    }

</style>
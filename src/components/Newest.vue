<script>

    export default{
        methods:{
            activate(event){
                const ul = document.getElementById('tab')
                const divs = document.getElementById('newestCont')
                
                if(event.target.children.length == 0)
                {

                    for(let i = 0; i < ul.children.length; i++){
                        ul.children[i].classList.remove('active')
                        divs.children[i].classList.remove('active')    
                    }
                    event.target.classList.add('active')
                    
                    for(let i = 0; i < ul.children.length; i++){
                        if(ul.children[i].classList.contains('active'))
                        divs.children[i].classList.add('active')   
                    }
                }
            }
        }
    }

</script>

<template>
    

    <h2 id="new">Lo más reciente</h2>  
    
    <div>
        <ul id="tab" @click="activate">
            <li class="active"> Canciones </li>
            <li> Videos </li>
            <li> Fotos </li>
        </ul>
        <div id="newestCont">
            <div class="canciones active"></div>
            <div class="videos">2</div>
            <div class="fotos">3</div>
        </div>

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
        transition: .2s;
    }
    .fotos , .canciones, .videos{
        background-color: white;
        border-radius: 10px;
        width: min(80vw, 500px);
        height: min(80vw, 500px);
        display: none;
    }

    div.canciones{
        background-color: coral !important;;
    }

    li.active{
        border-bottom: 3px solid  #f42c04;
    }
    div#newestCont .active{
        display: block;
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
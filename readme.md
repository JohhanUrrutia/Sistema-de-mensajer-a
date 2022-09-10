Profesor, corregí lo mencionado respecto a las ubicaciones del archivo style.css y además las imagenes del desafío; respecto a lo que menciona acerca de la ultima imagen del chat de la lista de contactos no encuentro del detalle, utilize background-image y además esta centrado 😁

.contact-user-chat-image-8{
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background-image: url(../imgs/Screen\ Shot\ 2018-11-28\ at\ 15.28.04.jpg);
    background-size: contain;
    background-position: center;
    margin: 10px;
}

Acerca del botón de "Nuevo Chat" lo centré con flex:

Caja en HTML:

<!--<div class="chat-button">
                <a class="chat-button-press" href="index.html">
                    <p class="nuevo-chat">Nuevo Chat</p>
                </a>
            </div>
-->


Estilo en CSS:

.chat-button{
    width: 100%;
    height: 150px;
    display: flex;
    justify-content: center;
    align-items: center;
    border: 1px solid #BEC1BB;
}

.chat-button-press:hover{
    transform: scale(1.05);
    transition: .5s;
}

.chat-button-press{
    width: 60%;
    height: auto;
    padding: 10px;
    background-color: #A491D2;
    display: flex;
    justify-content: center;
    align-items: center;
    text-decoration: none;
}

.nuevo-chat{
    color: #fff;
    margin: 0;
    text-decoration: none;
}
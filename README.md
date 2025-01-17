@-moz-document domain("github.com"), domain("gist.github.com") {
    /* Adicionar mensagem personalizada no topo */
    .header {
        position: relative;
    }

    .header::before {
        content: "Olá, meu nome é Elizabete Ribeiro";
        display: block;
        background-color: #81c784; /* Fundo verde */
        color: #ffffff; /* Texto branco */
        padding: 10px;
        font-size: 16px;
        text-align: center;
        position: absolute;
        width: 100%;
        top: 0;
        left: 0;
        z-index: 1000;
    }

    /* Ajustar o conteúdo para descer abaixo da mensagem */
    .application-main {
        margin-top: 40px; /* Ajuste conforme necessário */
    }
}
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desafio do Dia dos Pais</title>
    <style>
        :root {
            --cor-fundo: #000;
            --cor-principal: #f8d347;
            --cor-texto: #fff;
            --cor-drama: #ff5555;
            --cor-borda: #f8d347;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: var(--cor-fundo);
            color: var(--cor-texto);
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            padding: 20px;
            background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTn2uaqQhvcfOVuDDVc8_xJVW7qUMqnn86LxQ&s');
            background-size: cover;
            background-position: center;
            background-attachment: fixed; /* Opcional: faz a imagem de fundo ser fixa */
        }

        .container {
            background-color: rgba(0, 0, 0, 0.8); /* Fundo um pouco mais escuro para melhor contraste */
            border: 3px solid var(--cor-borda);
            border-radius: 15px;
            padding: 30px;
            max-width: 90%; /* Se adapta a qualquer largura de tela */
            box-shadow: 0 0 20px rgba(248, 211, 71, 0.5); /* Sombra mais destacada */
            backdrop-filter: blur(5px); /* Efeito de vidro fosco, se o navegador suportar */
        }

        h1 {
            color: var(--cor-principal);
            font-size: 2.5rem; /* Usando rem para responsividade */
            text-shadow: 0 0 15px var(--cor-principal);
            margin-bottom: 20px;
        }

        p {
            font-size: 1.2rem;
            line-height: 1.6;
            margin: 20px 0;
        }

        .drama {
            color: var(--cor-drama);
            font-weight: bold;
            font-size: 1.4rem;
            text-transform: uppercase;
            animation: pulse 1.5s infinite; /* Adiciona uma animação */
        }

        .btn {
            display: inline-block;
            padding: 1rem 2rem; /* Usando rem */
            font-size: 1.2rem;
            background-color: var(--cor-principal);
            color: var(--cor-fundo);
            text-decoration: none;
            border-radius: 50px;
            margin-top: 30px;
            font-weight: bold;
            transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
        }

        .btn:hover {
            background-color: #ffdf60;
            transform: scale(1.1); /* Efeito de aumento mais suave */
            box-shadow: 0 5px 15px rgba(248, 211, 71, 0.4);
        }

        .music-note {
            font-size: 1.5rem;
            margin-top: 20px;
            display: block;
            color: #999;
        }

        /* Animação para o texto dramático */
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }

        /* Media query para telas menores */
        @media (max-width: 600px) {
            h1 {
                font-size: 2rem;
            }
            p {
                font-size: 1rem;
            }
            .btn {
                font-size: 1rem;
                padding: 0.8rem 1.5rem;
            }
            .container {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Desafio do Dia dos Pais</h1>
        
        <p>Oi pai! Feliz Dia dos Pais! Eu lhe fiz um presente que fiz com muito carinho, espero que goste...</p>
        
        <p class="drama">QUÊ?! VOLTE AQUI! NÃO!! NÃO!!</p>
        
        <p>Argh, droga! Parece que sua surpresa foi roubada por um corinthiano safado!</p>
        
        <p>Droga pai, parece que você terá que ir pelo caminho mais difícil.</p>
        
        <a href="desafio1.html" class="btn">Clique aqui para ir para o primeiro desafio!</a>
        
        
    </div>

    </body>
</html>

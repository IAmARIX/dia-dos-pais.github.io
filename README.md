# vader.github.io
Dia dos pais
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desafio do Dia dos Pais</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 20px;
            background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTn2uaqQhvcfOVuDDVc8_xJVW7qUMqnn86LxQ&s'); /* Imagem de um corinthiano fugindo */
            background-size: cover;
            background-position: center;
        }
        .container {
            background-color: rgba(0, 0, 0, 0.7);
            border: 3px solid #f8d347;
            border-radius: 15px;
            padding: 30px;
            max-width: 800px;
            margin: 50px auto;
        }
        h1 {
            color: #f8d347;
            font-size: 2.5em;
            text-shadow: 0 0 10px #f8d347;
        }
        p {
            font-size: 1.2em;
            line-height: 1.6;
            margin: 20px 0;
        }
        .drama {
            color: #ff5555;
            font-weight: bold;
            font-size: 1.4em;
            text-transform: uppercase;
        }
        .btn {
            display: inline-block;
            padding: 15px 30px;
            font-size: 1.2em;
            background-color: #f8d347;
            color: #000;
            text-decoration: none;
            border-radius: 50px;
            margin-top: 30px;
            font-weight: bold;
            transition: all 0.3s;
        }
        .btn:hover {
            background-color: #ffdf60;
            transform: scale(1.05);
        }
        .music-note {
            font-size: 1.5em;
            margin-top: 20px;
            display: block;
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
        
        <span class="music-note">🎵 <em>Música: "Pai" (Gonzaguinha) tocando...</em> 🎵</span>
    </div>

    <!-- Música de fundo (autoplay em loop) -->
    <audio autoplay loop>
        <!-- Opção 2: Pai - Gonzaguinha (emocionante) -->
        <source src="https://www.youtube.com/watch?v=dn7Ks4tBE8g&ab_channel=MundoFonogr%C3%A1ficoTv" type="audio/mpeg">
        
        Seu navegador não suporta áudio :(
    </audio>

    <script>
        // Força o autoplay (pode precisar de interação do usuário em alguns navegadores)
        document.addEventListener('click', function() {
            document.querySelector('audio').play();
        });
    </script>
</body>
</html>

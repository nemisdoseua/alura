                                                                # alura
aluraproject
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slide com Imagens do Naruto</title>
    <style>
        /* Estilo para o corpo da página */
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(to bottom, black, orange); /* Degradê de preto para laranja */
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }m

        /* Estilo para o slide */
        .slide {
            width: 80%;
            height: 80%;
            background-color: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            display: flex;
            justify-content: flex-start;
            align-items: center;
            padding: 20px;
        }

        /* Estilo para o container das imagens */
        .image-container {
            display: flex;
            flex-direction: column;
            gap: 20px; /* Espaço entre as imagens */
            padding-left: 20px; /* Espaço do lado esquerdo */
        }

        /* Estilo para as imagens */
        .image-container img {
            width: 200px; /* Largura de cada imagem */
            height: auto;
            border-radius: 10px; /* Bordas arredondadas nas imagens */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* Sombra para as imagens */
        }
    </style>
</head>
<body>
    <div class="slide">
        <div class="image-container">
            <!-- Imagens dos personagens -->
            <img src="https://via.placeholder.com/200x300.png?text=Naruto" alt="Naruto">
            <img src="https://via.placeholder.com/200x300.png?text=Sakura" alt="Sakura">
            <img src="https://via.placeholder.com/200x300.png?text=Itachi" alt="Itachi">
            <img src="https://via.placeholder.com/200x300.png?text=Naruto+2" alt="Naruto">
            <img src="https://via.placeholder.com/200x300.png?text=Sakura+2" alt="Sakura">
        </div>
    </div>
</body>
</html>

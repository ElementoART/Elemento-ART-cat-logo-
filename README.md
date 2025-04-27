<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elemento ART – Catálogo</title>
    <style>
        body { font-family: Arial, sans-serif; background-color: #f5f5f5; margin: 0; padding: 0; }
        header { background-color: #222; color: #fff; padding: 20px 0; text-align: center; }
        header h1 { margin: 0; font-size: 2em; }
        header p { margin: 5px 0 0; font-size: 1em; color: #ccc; }
        .catalogo { display: flex; flex-direction: column; align-items: center; padding: 20px; }
        .produto { background: #fff; width: 90%; max-width: 600px; margin-bottom: 30px; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); overflow: hidden; }
        .produto img { width: 100%; height: auto; }
        .produto-conteudo { padding: 15px; }
        .produto h2 { margin-top: 0; }
        .produto p { margin: 5px 0; color: #555; }
        .whatsapp-button { display: inline-block; background-color: #25D366; color: white; padding: 10px 20px; margin-top: 10px; border: none; border-radius: 5px; text-decoration: none; font-weight: bold; }
        .whatsapp-button:hover { background-color: #1ebe5d; }
    </style>
</head>
<body>

<header>
    <h1>Elemento ART</h1>
    <p>Conforto, estilo e qualidade para o seu dia</p>
</header>

<div class="catalogo">
    <div class="produto">
        <img src="https://via.placeholder.com/600x400" alt="Fusô Microgorgurinho">
        <div class="produto-conteudo">
            <h2>Fusô Microgorgurinho</h2>
            <p><strong>Tamanhos:</strong> P, M, G, GG</p>
            <p><strong>Cor:</strong> Preta</p>
            <p><strong>Preço:</strong> R$ 189,90</p>
            <p><strong>Descrição:</strong> Fusô confeccionada em tecido microgorgurinho da Pettenati, oferecendo toque macio, conforto e alta elasticidade para melhor ajuste ao corpo. Ideal para compor looks versáteis e modernos.</p>
            <a class="whatsapp-button" href="https://wa.me/5555992347811?text=Olá!%20Tenho%20interesse%20na%20Fusô%20Microgorgurinho%20preta.">Comprar pelo WhatsApp</a>
        </div>
    </div>
</div>

</body>
</html>

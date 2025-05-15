<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>God Usopp - O Bravo Guerreiro do Mar</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fff8e6;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 20px;
        }

        section {
            padding: 20px;
            text-align: center;
        }

        .carrossel img {
            width:350px;
            height:400px;
            border-radius: 10px;
            display: none;
        }

        .carrossel img.ativo {
            display: block;
            margin: 0 auto;
        }

        .zoom img {
            width: 300px;
            transition: transform 0.3s;
            border-radius: 10px;
        }

        .balao {
            background-color: #ffffcc;
            border: 2px dashed #ff9900;
            padding: 15px;
            margin: 15px auto;
            width: 80%;
            border-radius: 10px;
            box-shadow: 3px 3px 5px rgba(0,0,0,0.1);
        }

        .titulo {
            font-weight: bold;
            color: #cc3300;
        }

        h2 {
            color: #333;
            margin-top: 40px;
        }
    </style>
</head>
<body>

<header>
    <h1>God Usopp - O Bravo Guerreiro do Mar</h1>
</header>

<section>
    <h2>Carrossel de Imagens</h2>
    <div class="carrossel">
        <img class="ativo" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSBXK26FVJdzItIMioPKmvbTv1qxKYLHZxUfw&usqp=CAU" alt="Usopp 1">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR4M1VxFCYqk62VlCMXNwerOG6lg5sZXg9Hhw&usqp=CAU" alt="Usopp 2">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTQ8ZMNX7nCT5Ne5edImFK9Kho6fMt3nbNSSvEsOL2omGSP6qFVRqLsAkBbbTaLlAYjWAE&usqp=CAU alt="Usopp 3">
    </div>

    <h2>As Lendárias aventuras do Capitão Usopp</h2>

    <div class="balao">
        <p class="titulo">1. O Despertar do Herói:</p>
        <p>Em uma manhã chuvosa, Usopp acordou em sua fortaleza invisível — um castelo flutuante que só ele podia ver.</p>
    </div>

    <div class="balao">
        <p class="titulo">2. O Dragão de Três Cabeças:</p>
        <p>Logo foi atacado por um dragão de três cabeças, que derrotou com um estilingue feito de ossos de reis lendários e munição de pimenta.</p>
    </div>

    <div class="balao">
        <p class="titulo">3. O Exército de Gigantes:</p>
        <p>Sem tempo para descansar, enfrentou um exército de gigantes armados com canhões. Usopp venceu todos com seu tapa supersônico que move continentes.</p>
    </div>

    <div class="balao">
        <p class="titulo">4. O Mordomo Monstro:</p>
        <p>Ao chegar numa ilha deserta, domesticou um monstro marinho de 100 metros e o ensinou a cozinhar sushi. A criatura virou seu mordomo fiel.</p>
    </div>

    <div class="balao">
        <p class="titulo">5. A Fundação de Usopptânia:</p>
        <p>Na mesma ilha, fundou o reino de Usopptânia, onde todos usam narizes falsos em sua homenagem. Foi coroado rei, general e eleito o mais bonito dos mares — três vezes no mesmo dia.</p>
    </div>

    <div class="balao">
        <p class="titulo">6. A Sereia Ninja:</p>
        <p>Salvou uma princesa que, na verdade, era uma sereia ninja disfarçada. Ela pediu sua mão em casamento, mas Usopp recusou — afinal, "ser herói é mais importante que o amor."</p>
    </div>

    <div class="balao">
        <p class="titulo">7. O Retorno Glorioso:</p>
        <p>Depois de tudo, voltou ao navio e disse com humildade: "Nem foi tão difícil... Só mais um dia comum para mim!"</p>
    </div>
    
    <div class="zoom">
        <img id="imagemZoom" src="https://cdn.mall.adeptmind.ai/https%3A%2F%2Fcdn11.bigcommerce.com%2Fs-azatr4%2Fimages%2Fstencil%2F1280x1280%2Fproducts%2F16554%2F18317%2F22278__80070.1635055945.jpg%3Fc%3D2_medium.webp" alt="Usopp Zoom">
    </div>
</section>

<script>
    const imagem = document.getElementById("imagemZoom");

    imagem.addEventListener("mouseenter", () => {
        imagem.style.transform = "scale(1.2)";
    });

    imagem.addEventListener("mouseleave", () => {
        imagem.style.transform = "scale(1)";
    });

    let imagens = document.querySelectorAll(".carrossel img");
    let indice = 0;

    function trocarImagem() {
        imagens[indice].classList.remove("ativo");
        indice = (indice + 1) % imagens.length;
        imagens[indice].classList.add("ativo");
    }

    setInterval(trocarImagem, 3000);
</script>

</body>
</html>

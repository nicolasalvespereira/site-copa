<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Jogadores da Copa do Mundo de 2018</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f2f2f2;
    }

    header {
      background-image: url('https://images01.nicepage.io/12/bc/12bc5c5c95ee9a9e57e165f3c5ba1615.png');
      background-size: cover;
      background-position: center 30%;
      background-color: #000;
      height: 700px;
      position: relative;
      overflow: hidden;
    }

    .logo-pequena {
      position: absolute;
      top: 20px;
      left: 20px;
      width: 100px;
      z-index: 2;
    }

    .conteudo-lateral {
      display: flex;
      gap: 20px;
      margin: 40px 0 0 40px;
      align-items: stretch;
    }

    .quadro-vermelho {
      background-color: red;
      color: white;
      padding: 20px;
      width: 500px;
      height: 210px;
      border-radius: 20px;
      font-weight: bold;
      font-size: 22px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }

    .imagem-lateral {
      width: 450px;
      height: 250px;
      border-radius: 20px;
      object-fit: cover;
      margin-left: 5px;
    }

    .imagem-central {
      width: 450px;
      height: 250px;
      border-radius: 20px;
      object-fit: cover;
    }

    section {
      padding: 40px 20px;
      max-width: 1200px;
      margin: auto;
    }

    .intro {
      text-align: center;
    }

    .intro img {
      width: 100%;
      max-width: 800px;
      border-radius: 10px;
      margin-top: 20px;
    }

    footer {
      background-color: #1a1a1a;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <img class="logo-pequena" src="https://images01.nicepage.io/83/36/833627309a21e4d5ddd4c86f220db9bf.png" alt="Logo pequena">
  </header>

  <!-- Quadrado vermelho e imagens -->
  <div class="conteudo-lateral">
    <div class="quadro-vermelho">
      Conheça os principais jogadores da Copa do Mundo de 2018
    </div>
    <img class="imagem-central" src="https://assets.goal.com/images/v3/blt95a3663504fddb0d/c781de25853d8e84167f94279de023baea774bbe.jpg?auto=webp&format=pjpg&width=3840&quality=60">
    <img class="imagem-lateral" src="https://imagenes.elpais.com/resizer/v2/5GX65QJCYNHRE2RDRKPNFLWS6E.jpg?auth=b4f7622adaf9009120565c52a4c2b54184910f34a273079cee9f670b3860a8b0&width=414" alt="Jogadores">
  </div>

  <!-- Texto e imagem de Mbappé lado a lado -->
  <div style="display: flex; align-items: flex-start; margin: 60px 40px 0 40px; gap: 40px;">
    <div>
      <div style="font-size: 26px; font-weight: bold; color: #000; margin-bottom: 10px;">
        Melhor Jovem Jogador da Copa
      </div>
      <p style="font-size: 18px; color: #333; max-width: 600px; margin: 0;">
        Kylian Mbappé foi um dos grandes destaques da Copa do Mundo de 2018 na Rússia. Com apenas 19 anos, marcou 4 gols no torneio, incluindo um gol na final contra a Croácia. Sua velocidade, habilidade e maturidade impressionaram o mundo. Ele foi essencial na campanha da França, ajudando a equipe a conquistar o título após 20 anos. Como reconhecimento, Mbappé recebeu o prêmio de Melhor Jogador Jovem do torneio.
      </p>
    </div>

    <img src="https://conteudo.imguol.com.br/c/copadomundo/2018/Imagem/16/2018/07/15/o-atacante-mbappe-beija-o-trofeu-da-copa-do-mundo-1531677311778_v2_3x4.jpg"
         alt="Mbappé em ação"
         style="height: 400px; width: 300px; border-radius: 10px; object-fit: cover;">
  </div>

  <!-- Texto e imagem de Modric, layout invertido -->
  <div style="display: flex; flex-direction: row-reverse; align-items: flex-start; margin: 60px 40px 0 40px; gap: 40px;">
    <div>
      <div style="font-size: 26px; font-weight: bold; color: #000; margin-bottom: 10px;">
        Melhor Jogador da Copa
      </div>
      <p style="font-size: 18px; color: #333; max-width: 600px; margin: 0;">
        Luka Modric foi eleito o Melhor Jogador da Copa do Mundo de 2018. O meio-campista croata liderou sua seleção até a final, algo inédito para o país. Com grande visão de jogo, passes precisos e liderança, Modric se destacou em praticamente todas as partidas. Apesar da derrota na final contra a França, sua atuação durante o torneio foi reconhecida com a Bola de Ouro da FIFA.
      </p>
    </div>

    <img src="https://omundoeumabola.blogfolha.uol.com.br/files/2018/08/Modric-2.jpg"
         alt="Modric em ação"
         style="height: 400px; width: 300px; border-radius: 10px; object-fit: cover;">
  </div>

  <!-- Texto e imagem de Hazard, layout invertido (imagem à direita) -->
<div style="display: flex; justify-content: space-between; align-items: flex-start; margin: 10px 200px 0 40px; gap: 40px;">
  <div>
    <div style="font-size: 26px; font-weight: bold; color: #000; margin-bottom: 10px;">
      Destaque da Bélgica
    </div>
    <p style="font-size: 18px; color: #333; max-width: 600px; margin: 0;">
      Eden Hazard foi um dos principais jogadores da Bélgica na Copa do Mundo de 2018. Atuando como capitão, o meia-atacante brilhou com sua habilidade, dribles e liderança em campo. Conduziu a seleção belga até as semifinais, garantindo o terceiro lugar, a melhor campanha do país na história das Copas. Seu desempenho foi amplamente elogiado e consolidou sua reputação como um dos melhores jogadores do torneio.
    </p>
  </div>

  <img src="https://ogimg.infoglobo.com.br/in/22863369-112-991/FT1086A/O-belga-Hazard-foi-um-dos-destaques-das-quartas-de-final.jpg"
       alt="Hazard em ação"
       style="height: 400px; width: 300px; border-radius: 10px; object-fit: cover;">
</div>


<!-- Texto e imagem de Grizzman, layout invertido -->
  <div style="display: flex; flex-direction: row-reverse; align-items: flex-start; margin: 60px 40px 0 40px; gap: 40px;">
    <div>
      <div style="font-size: 26px; font-weight: bold; color: #000; margin-bottom: 10px;">
        O Cérebro Ofensivo da França
      </div>
      <p style="font-size: 18px; color: #333; max-width: 600px; margin: 0;">
        Antoine Griezmann foi um dos protagonistas da França na Copa do Mundo de 2018. Com atuações decisivas, marcou quatro gols e deu assistências importantes, incluindo um gol e participação direta em dois outros na final contra a Croácia. Sua inteligência tática, habilidade nas bolas paradas e liderança ofensiva foram fundamentais para a conquista do título. Griezmann terminou o torneio com a Bola de Bronze, como o terceiro melhor jogador da competição.
      </p>
    </div>

    <img src="https://jpimg.com.br/uploads/2018/07/636672747158474847w.jpg"
     alt="Grizzman em ação"
     style="height: 400px; width: 300px; border-radius: 10px; object-fit: cover;">
  </div>

  <footer>
    <p>&copy; 2025 - Site sobre a Copa do Mundo 2018</p>
  </footer>

</body>
</html>

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Game Fish - Site Oficial</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #0d1a26;
            color: #e0f7fa;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            text-align: center;
        }
        .header {
            background-color: #013243;
            color: white;
            padding: 3rem 1rem;
        }
        .header h1 {
            margin: 0;
            font-size: 3.5rem;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        .header p {
            font-style: italic;
        }
        .container {
            max-width: 900px;
            margin: 2rem auto;
            padding: 0 1rem;
        }
        .section {
            background-color: #014358;
            padding: 2.5rem;
            border-radius: 12px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
            margin-bottom: 2rem;
            text-align: left;
            border: 1px solid #026670;
        }
        .section h2 {
            color: #8cdeff;
            border-bottom: 2px solid #8cdeff;
            padding-bottom: 0.5rem;
            margin-top: 0;
        }
        .gameplay-details {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 1.5rem;
        }
        .gameplay-item {
            flex: 1;
            background-color: #034b6c;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: inset 0 0 10px rgba(0, 0, 0, 0.2);
        }
        .link-button {
            display: inline-block;
            background-color: #0288d1;
            color: white;
            padding: 1rem 2rem;
            margin-top: 1.5rem;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
            transition: background-color 0.3s ease;
        }
        .link-button:hover {
            background-color: #0277bd;
        }
        .team-list {
            list-style-type: none;
            padding: 0;
        }
        .team-list li {
            background: #013d52;
            margin-bottom: 0.5rem;
            padding: 0.75rem 1rem;
            border-radius: 6px;
        }
        .image-container {
            text-align: center;
            margin: 2rem 0;
        }
        .game-image {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            border: 2px solid #026670;
        }
        .footer {
            text-align: center;
            padding: 1.5rem;
            background-color: #012b36;
            color: #b0c4de;
            margin-top: 2rem;
        }
    </style>
</head>
<body>

    <header class="header">
        <h1>The Game Fish</h1>
        <p>A aventura de um peixe pela sobrevivência!</p>
    </header>

    <main class="container">
        <section class="section">
            <h2>Sobre o Jogo</h2>
            <p><strong>The Game Fish</strong> é uma emocionante aventura no fundo do mar, onde você controla um peixe que luta para sobreviver. Para crescer e se manter vivo, ele precisa se alimentar de outros peixes menores, mas também deve evitar predadores maiores que espreitam nas profundezas. É um jogo sobre a cadeia alimentar e a constante busca pela sobrevivência.</p>
            <p>O visual do jogo pode ser visto na imagem abaixo. O peixe no centro é o nosso protagonista!</p>
            <div class="image-container">
                <img class="game-image" src="https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/06696bd6-a0eb-4bdf-91eb-aec705f7acfc.webp" alt="O peixe principal do jogo, em Voxel Art, no ambiente marinho.">
            </div>
        </section>

        <section class="section">
            <h2>Gameplay e Mecânicas</h2>
            <p>No jogo, seu objetivo é simples: crescer. Cada peixe menor que você consome aumenta seu tamanho e suas chances de sobrevivência. Mas cada decisão conta:</p>
            
            <div class="gameplay-details">
                <div class="gameplay-item">
                    <h3>Alimentação e Crescimento</h3>
                    <p>Você começa pequeno e vulnerável. Para evoluir, deve caçar e comer peixes como lulas e arraias. Consumir a presa correta é a chave para se tornar um peixe maior e mais forte.</p>
                </div>
                <div class="gameplay-item">
                    <h3>O Perigo das Profundezas</h3>
                    <p>O oceano está cheio de perigos. Peixes predadores maiores que você podem aparecer a qualquer momento. Você precisa ser rápido e estratégico para fugir e não se tornar a próxima refeição.</p>
                </div>
            </div>
        </section>

        <section class="section">
            <h2>O Mapa do Jogo</h2>
            <p>O mundo de <strong>The Game Fish</strong> é gerado de forma procedural, o que significa que cada novo jogo cria um mapa totalmente único. Inspirado no estilo de criação de mundo do Minecraft, você nunca vai explorar o mesmo cenário duas vezes. Cada mergulho é uma nova aventura!</p>
            <p>O conceito por trás do jogo foi inspirado pelo vídeo abaixo. Confira para ver a base da nossa ideia!</p>
            <p style="text-align: center;">
                <a href="https://youtu.be/z0hHAkpuA1Q?si=jJZGKTqSBvomZI-V" target="_blank" class="link-button">Ver Jogo de Inspiração</a>
            </p>
        </section>

        <section class="section">
            <h2>Linha de Arte</h2>
            <p>Todo o visual do jogo é construído em <strong>Voxel Art</strong>, uma técnica que usa pequenos "cubos" tridimensionais para criar um estilo único e detalhado para os personagens e o ambiente marinho. A imagem abaixo exemplifica bem esse estilo de arte com poucos polígonos.</p>
            <div class="image-container">
                <img class="game-image" src="https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/efb7eb8f-6f38-45a1-a232-3c14355d0b02.webp" alt="Exemplo do estilo de arte com poucos polígonos, parecido com o Voxel Art do jogo.">
            </div>
        </section>

        <section class="section">
            <h2>Nossa Equipe</h2>
            <p>O projeto <strong>The Game Fish</strong> foi desenvolvido com dedicação e paixão pelo <strong>Time 1</strong>.</p>
            <ul class="team-list">
                <li>Arthur Moura</li>
                <li>Nicolas Miguel</li>
                <li>José Alexsandro</li>
                <li>Renato Miguel</li>
                <li>Luiz Otávio</li>
            </ul>
        </section>
    </main>

    <footer class="footer">
        <p>&copy; 2025 Time 1. Todos os direitos reservados.</p>
    </footer>

</body>
</html>


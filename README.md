<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Refügium - Download Oficial</title>
    <style>
        /* Reset de margens e configuração básica para todos os elementos */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        /* Configuração do fundo escuro da página */
        body {
            background-color: #121212;
            color: #ffffff;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        /* Estilo do cabeçalho onde fica o nome do jogo */
        header {
            background-color: #0a0a0a;
            padding: 30px 20px;
            text-align: center;
            border-bottom: 2px solid #2a2a2a;
        }

        header h1 {
            font-size: 3rem;
            letter-spacing: 4px;
            color: #e0e0e0;
            text-transform: uppercase;
        }

        /* Área central com a descrição e o botão */
        main {
            flex: 1;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 50px 20px;
            text-align: center;
        }

        .game-description {
            max-width: 600px;
            margin-bottom: 50px;
            line-height: 1.6;
            font-size: 1.2rem;
            color: #b3b3b3;
        }

        /* Estilo detalhado do botão de download */
        .download-btn {
            background-color: #d32f2f; /* Cor vermelha para dar destaque */
            color: #ffffff;
            text-decoration: none;
            padding: 18px 40px;
            font-size: 1.5rem;
            font-weight: bold;
            border-radius: 8px;
            transition: background-color 0.3s ease, transform 0.2s ease;
            box-shadow: 0 4px 15px rgba(211, 47, 47, 0.4);
        }

        /* Efeito de quando o mouse passa por cima do botão */
        .download-btn:hover {
            background-color: #b71c1c;
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(211, 47, 47, 0.6);
        }

        /* Estilo do rodapé */
        footer {
            background-color: #0a0a0a;
            text-align: center;
            padding: 20px;
            font-size: 0.9rem;
            color: #666666;
            border-top: 1px solid #2a2a2a;
        }
    </style>
</head>
<body>

    <header>
        <h1>Refügium</h1>
    </header>

    <main>
        <p class="game-description">
            Prepare-se para entrar neste universo. Clique no botão abaixo para baixar a versão mais recente e iniciar a sua jornada.
        </p>

        <a href="#" class="download-btn" target="_blank" rel="noopener noreferrer">
            BAIXAR O JOGO
        </a>
    </main>

    <footer>
        <p>&copy; 2026 Rorinaldo. Todos os direitos reservados.</p>
    </footer>

</body>
</html>

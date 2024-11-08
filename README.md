DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Investir em Criptomoedas</title>
    <style>
        /* Estilos Gerais */
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            background-color: #f9f9f9;
            color: #333;
            margin: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: flex-start;
            height: 100vh;
            padding: 20px;
            background-image: url('background.jpg'); /* Adicione uma imagem de fundo leve, se desejado */
            background-size: cover;
            background-position: center;
        }

        header {
            width: 100%;
            padding: 15px 0;
            background-color: rgba(255, 255, 255, 0.8);
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            position: fixed;
            top: 0;
            left: 0;
            z-index: 1000;
        }

        h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            color: #1d1d1f;
            margin-top: 70px; /* Para espaçamento abaixo do header */
        }

        h2 {
            font-weight: 600;
            color: #1d1d1f;
            margin-bottom: 20px;
        }

        /* Estilos do Formulário de Login */
        .login-form {
            width: 100%;
            max-width: 360px;
            padding: 20px;
            background-color: #fff;
            border-radius: 12px;
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.1);
            text-align: left;
            margin-top: 20px;
        }

        .login-form input {
            width: 100%;
            padding: 12px;
            margin: 8px 0;
            border: 1px solid #d1d1d6;
            border-radius: 8px;
            font-size: 16px;
            background-color: #f9f9f9;
            color: #1d1d1f;
            transition: border-color 0.2s ease;
        }

        .login-form input:focus {
            border-color: #0071e3;
            outline: none;
        }

        .login-form button {
            width: 100%;
            padding: 12px;
            font-size: 16px;
            color: #fff;
            background-color: #0071e3;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: background-color 0.2s ease, transform 0.2s ease;
            margin-top: 10px;
        }

        .login-form button:hover {
            background-color: #005bb5;
            transform: translateY(-1px);
        }

        /* Seção de Introdução */
        .intro {
            text-align: center;
            margin: 20px 0;
            max-width: 600px;
        }

        .intro p {
            font-size: 1.1em;
            color: #666;
        }

        /* Botões de Investimento */
        .crypto-buttons {
            display: flex;
            flex-wrap: wrap;
            gap: 12px;
            justify-content: center;
            margin-top: 30px;
        }

        .crypto-button {
            display: inline-block;
            padding: 12px 20px;
            font-size: 16px;
            color: #0071e3;
            background-color: #fff;
            border: 1px solid #d1d1d6;
            border-radius: 8px;
            cursor: pointer;
            text-decoration: none;
            transition: box-shadow 0.2s ease, transform 0.2s ease;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.08);
            width: 200px;
            text-align: center;
        }

        .crypto-button:hover {
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transform: translateY(-2px);
            background-color: #e8f0fe; /* Efeito de brilho */
        }

        /* Responsividade */
        @media (max-width: 600px) {
            h1 {
                font-size: 2em;
            }
            .crypto-button {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>CryptoInvest</h1>
    </header>
    <div class="intro">
        <p>Descubra o mundo das criptomoedas e comece a investir de forma segura e confiável.</p>
    </div>
    <div class="login-form">
        <h2>Login</h2>
        <form action="/login" method="post">
            <input type="text" name="username" placeholder="Usuário" required>
            <input type="password" name="password" placeholder="Senha" required>
            <button type="submit">Entrar</button>
        </form>
    </div>
    <div class="crypto-buttons">
        <a href="https://freebc10.wordpress.com/wp-content/uploads/2024/11/screenshot_20241101_192534_canva8943127649350626190.jpg?w=998" class="crypto-button">Investir em Bitcoin</a>
        <a href="https://freebc10.wordpress.com/wp-content/uploads/2024/11/10000285252634412545730954480.jpg?w=1024" class="crypto-button">Investir em Ethereum</a>
        <a href="https://freebc10.wordpress.com/wp-content/uploads/2024/11/10000285252634412545730954480.jpg?w=1024" class="crypto-button">Investir em Solana</a>
        <a href="https://freebc10.wordpress.com/sol/?preview=true" class="crypto-button">Investir em Bot Trader</a>
    </div>
</body>
</html>

# Siqueira
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Siqueira Polimentos Express</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
            margin: 0;
            background: linear-gradient(120deg, #f2f2f2, #e6e6e6);
            color: #333;
        }

        header {
            text-align: center;
            padding: 40px 20px 20px 20px;
        }

        header img {
            max-width: 180px;
            transition: transform 0.5s;
        }

        header img:hover {
            transform: scale(1.1);
        }

        h1 {
            margin: 10px 0 0 0;
            font-size: 2em;
            color: #111;
        }

        .container {
            max-width: 900px;
            margin: auto;
            padding: 20px;
        }

        .service {
            background: #fff;
            padding: 25px 20px;
            border-radius: 15px;
            margin-bottom: 20px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .service:hover {
            transform: translateY(-5px);
            box-shadow: 0 12px 25px rgba(0,0,0,0.15);
        }

        .service h2 {
            margin: 0 0 10px 0;
        }

        .description {
            font-size: 0.95em;
            color: #555;
            margin-bottom: 15px;
        }

        .btn {
            margin: 8px;
            padding: 12px 20px;
            font-size: 1em;
            border: none;
            border-radius: 12px;
            cursor: pointer;
            color: white;
            transition: all 0.3s;
        }

        .btn-polimentos { background-color: #4CAF50; }
        .btn-faros { background-color: #2196F3; }
        .btn-vitrificacao { background-color: #FF9800; }
        .btn-instagram { background-color: #E1306C; }
        .btn-whatsapp { background-color: #25D366; }

        .btn:hover { opacity: 0.9; }

        .btn-polimentos::before { content: "🛠️ "; }
        .btn-faros::before { content: "💡 "; }
        .btn-vitrificacao::before { content: "✨ "; }
        .btn-instagram::before { content: "📸 "; }
        .btn-whatsapp::before { content: "💬 "; }

        @media(max-width:600px){
            header img { max-width: 140px; }
            .service { padding: 20px; }
            .btn { padding: 10px 16px; font-size: 0.9em; }
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.png" alt="Siqueira Polimentos Express">
        <h1>Siqueira Polimentos Express</h1>
    </header>

    <div class="container">
        <!-- Polimento Técnico -->
        <div class="service">
            <h2>Polimento Técnico</h2>
            <div class="description">Restaura e protege a pintura do veículo, removendo riscos superficiais e marcas leves.</div>
            <button class="btn btn-polimentos" onclick="window.open('https://wa.me/5521996775181', '_blank')">Solicitar via WhatsApp</button>
        </div>

        <!-- Polimento de Faróis -->
        <div class="service">
            <h2>Polimento de Faróis</h2>
            <div class="description">Renova faróis amarelados ou opacos, garantindo melhor visibilidade e estética.</div>
            <button class="btn btn-faros" onclick="window.open('https://wa.me/5521996775181', '_blank')">Solicitar via WhatsApp</button>
        </div>

        <!-- Vitrificação -->
        <div class="service">
            <h2>Vitrificação</h2>
            <div class="description">Protege a pintura com camada de vitrificação, aumentando durabilidade e brilho intenso.</div>
            <button class="btn btn-vitrificacao" onclick="window.open('https://wa.me/5521996775181', '_blank')">Solicitar via WhatsApp</button>
        </div>

        <!-- Redes sociais -->
        <div class="service">
            <h2>Fale Conosco</h2>
            <button class="btn btn-instagram" onclick="window.open('https://www.instagram.com/_s.polimentos', '_blank')">Instagram</button>
            <button class="btn btn-whatsapp" onclick="window.open('https://wa.me/5521996775181', '_blank')">WhatsApp</button>
        </div>
    </div>
</body>
</html>

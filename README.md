<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fernando Angeli • Desenvolvedor</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #0d1117;
            color: #c9d1d9;
        }
        header {
            padding: 40px 20px;
            text-align: center;
            background: #161b22;
            border-bottom: 1px solid #30363d;
        }
        header img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-bottom: 20px;
            object-fit: cover;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
            color: #58a6ff;
        }
        header p {
            margin: 10px 0 0;
            color: #8b949e;
        }
        section {
            max-width: 900px;
            margin: 40px auto;
            padding: 0 20px;
        }
        h2 {
            color: #58a6ff;
            border-bottom: 1px solid #30363d;
            padding-bottom: 10px;
        }
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .card {
            background: #161b22;
            padding: 20px;
            border-radius: 8px;
            border: 1px solid #30363d;
        }
        .card h3 {
            margin-top: 0;
            color: #58a6ff;
        }
        .card p {
            color: #8b949e;
        }
        footer {
            text-align: center;
            padding: 20px;
            margin-top: 40px;
            color: #8b949e;
            border-top: 1px solid #30363d;
        }
        a {
            color: #58a6ff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<header>
    <!-- Imagem enviada por você — salve no repositório como "logo.png" -->
    <img src="logo.png" alt="Logo">
    <h1>Fernando Angeli</h1>
    <p>Desenvolvedor • Linux • Android • Redes • VPN • Servidores</p>
    <p>Telegram: <a href="https://t.me/fernandoangeli" target="_blank">@fernandoangeli</a></p>
</header>

<section>
    <h2>Sobre Mim</h2>
    <p>
        Sou desenvolvedor focado em soluções para Android, otimização de redes,
        servidores Linux, VPN, IPTVs, backend e ferramentas de segurança.
        Este site serve como meu portfólio e centralização dos meus projetos públicos.
    </p>
</section>

<section>
    <h2>Projetos</h2>
    <div class="projects">

        <div class="card">
            <h3>Projeto 1</h3>
            <p>Descrição completa do projeto. Exemplo: app Android, API, automação, ferramenta CLI etc.</p>
            <a href="#" target="_blank">Ver projeto</a>
        </div>

        <div class="card">
            <h3>Projeto 2</h3>
            <p>Sistema, ferramenta de rede, dashboard, app em Flask ou serviço backend.</p>
            <a href="#" target="_blank">Ver projeto</a>
        </div>

        <div class="card">
            <h3>Projeto 3</h3>
            <p>Scripts, utilitários Linux, ferramentas para servidores ou projetos GitHub.</p>
            <a href="#" target="_blank">Ver projeto</a>
        </div>

    </div>
</section>

<footer>
    © 2025 • Fernando Angeli • GitHub Pages
</footer>

</body>
</html>

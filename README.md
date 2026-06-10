<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>AGRO FORTE, FUTURO SUSTENTÁVEL</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8f5;
            color: #333;
        }

        header {
            background-color: #2e7d32;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav {
            margin-top: 10px;
        }

        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        section {
            padding: 40px 20px;
            max-width: 1200px;
            margin: auto;
        }

        section h2 {
            color: #2e7d32;
            margin-bottom: 20px;
            font-size: 2em;
        }

        .cards {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .card {
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            width: 300px;
            padding: 20px;
            transition: transform 0.2s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card h3 {
            margin-top: 0;
            color: #388e3c;
        }

        footer {
            background-color: #2e7d32;
            color: #fff;
            text-align: center;
            padding: 15px 0;
            margin-top: 40px;
        }

        /* Responsividade */
        @media(max-width: 768px) {
            .cards {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>AGRO FORTE</h1>
    <nav>
        <a href="#sobre">Sobre</a>
        <a href="#projetos">Projetos</a>
        <a href="#sustentabilidade">Sustentabilidade</a>
        <a href="#contato">Contato</a>
    </nav>
</header>

<section id="sobre">
    <h2>Futuro Sustentável: Equilíbrio entre Produção e Meio Ambiente</h2>
    <p>
        O projeto "Agro Forte" busca promover práticas agrícolas que garantam a produtividade, preservando o meio ambiente e promovendo o desenvolvimento sustentável. Nosso objetivo é criar um futuro onde a agricultura seja forte, eficiente e responsável com o planeta.
    </p>
</section>

<section id="projetos">
    <h2>Projetos e Iniciativas</h2>
    <div class="cards">
        <div class="card">
            <h3>Prática de Agricultura Orgânica</h3>
            <p>Implementação de técnicas de agricultura sem o uso de químicos, promovendo a saúde do solo e da água.</p>
        </div>
        <div class="card">
            <h3>Reflorestamento e Conservação</h3>
            <p>Projetos de reflorestamento para preservar biodiversidade e equilibrar o ecossistema agrícola.</p>
        </div>
        <div class="card">
            <h3>Técnicas de Irrigação Sustentável</h3>
            <p>Utilização de sistemas de irrigação eficientes que economizam água e reduzem impactos ambientais.</p>
        </div>
    </div>
</section>

<section id="sustentabilidade">
    <h2>Compromisso com a Sustentabilidade</h2>
    <p>
        Nosso compromisso é integrar práticas agrícolas sustentáveis que beneficiem tanto a produção quanto o meio ambiente. Acreditamos que a inovação, o respeito à natureza e a responsabilidade social são essenciais para um futuro promissor.
    </p>
</section>

<section id="contato">
    <h2>Contato</h2>
    <p>Para saber mais sobre nossos projetos ou colaborar com a iniciativa, envie um email para <a href="mailto:contato@agroforte.com">contato@agroforte.com</a>.</p>
</section>

<footer>
    <p>&copy; 2024 Agro Forte. Todos os direitos reservados.</p>
</footer>

</body>
</html>

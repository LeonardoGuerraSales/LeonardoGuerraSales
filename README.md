<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apresentação - Leonardo Sales</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #0a0a0a, #1c1c1c, #2e2e2e);
            color: #ffffff;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 900px;
            margin: auto;
            padding: 30px;
            text-align: center;
        }

        h1 {
            font-size: 42px;
            margin-bottom: 10px;
            color: #76c7ff;
        }

        h2 {
            font-size: 28px;
            margin-top: 40px;
            color: #ffd76c;
        }

        p {
            font-size: 18px;
        }

        .tech-box {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 20px;
        }

        .card {
            background: #222;
            border: 2px solid #444;
            padding: 20px;
            width: 180px;
            border-radius: 12px;
            transition: 0.3s;
        }

        .card:hover {
            transform: scale(1.08);
            background: #333;
            border-color: #76c7ff;
        }

        .btn {
            display: inline-block;
            margin: 15px 10px;
            padding: 12px 22px;
            background: #76c7ff;
            color: #000;
            text-decoration: none;
            font-weight: bold;
            border-radius: 10px;
            transition: 0.3s;
        }

        .btn:hover {
            background: #ffd76c;
        }

        footer {
            margin-top: 40px;
            opacity: 0.6;
            font-size: 14px;
        }
    </style>
</head>

<body>

    <div class="container">

        <h1>👋 Olá, eu sou Leonardo Sales!</h1>
        <p>Estudante de **Tecnólogo em Ciência de Dados** pela <strong>Universidade Maurício de Nassau (UNINASSAU)</strong>.</p>

        <h2>🛠 Tecnologias que estudo</h2>

        <div class="tech-box">

            <div class="card">
                <h3>🐍 Python</h3>
                <p>Pacotes:</p>
                <ul style="text-align:left;">
                    <li>Pandas</li>
                    <li>NumPy</li>
                </ul>
            </div>

            <div class="card">
                <h3>🗄 SQL</h3>
                <p>Consultas, joins,<br>modelagem de dados.</p>
            </div>

            <div class="card">
                <h3>📊 Power BI</h3>
                <p>Dashboards<br>e análise de dados.</p>
            </div>

        </div>

        <h2>📬 Contato</h2>

        <a class="btn" href="mailto:leo.sales.br@gmail.com">📧 Enviar Email</a>
        <a class="btn" href="https://www.linkedin.com/in/sales-leo" target="_blank">🔗 LinkedIn</a>

        <footer>© 2025 - Leonardo Sales</footer>

    </div>

</body>
</html>

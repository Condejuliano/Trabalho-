
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hello World - Exemplo HTML</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f4f6f8;
            color: #333;
        }
        h1 {
            color: #111;
        }
        /* Estilos para a Seção de Serviços e Cards */
        .secao-servicos {
            margin-top: 40px;
            padding: 20px;
            background: #ffffff;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }
        .cards-container {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        .card {
            flex: 1;
            min-width: 250px;
            background: #ffffff;
            border: 1px solid #e1e4e8;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.02);
        }
        .card h3 {
            color: #0066cc;
            margin-top: 0;
        }
    </style>
</head>
<body>
    <!-- Cabeçalho principal -->
    <h1>Olá, Mundo! (Hello World)</h1>
    
    <!-- Parágrafo de texto -->
    <p>Este é um exemplo básico estruturado com as principais tags do <strong>HTML</strong>.</p>
    
    <!-- Lista com itens -->
    <ul>
        <li>Item 1: Estrutura</li>
        <li>Item 2: Semântica</li>
        <li>Item 3: Navegador</li>
    </ul>
    
    <!-- Link de exemplo -->
    <p>Aprenda mais na <a href="https://developer.mozilla.org/pt-BR/docs/Learn_web_development/Core/Structuring_content/Basic" target="_blank">documentação da MDN</a>.</p>

    <hr>

    <!-- 2. Seção de Serviços (O Que Fazemos) -->
    <section class="secao-servicos">
        <h2>O Que Fazemos</h2>
        <p>Apresentar de forma detalhada e organizada os três pilares da empresa: Apps, Sites e Design/UI/UX.</p>
        
        <div class="cards-container">
            <!-- Card 1: Aplicativos Mobile -->
            <div class="card">
                <h3>Aplicativos Mobile</h3>
                <p>Desenvolvimento nativo e híbrido para iOS e Android, com foco em desempenho e experiência do usuário.</p>
            </div>
            
            <!-- Card 2: Criação de Sites -->
            <div class="card">
                <h3>Criação de Sites</h3>
                <p>Websites institucionais, lojas virtuais e landing pages otimizadas para SEO e conversão.</p>
            </div>
            
            <!-- Card 3: Design & Layouts (UI/UX) -->
            <div class="card">
                <h3>Design & Layouts (UI/UX)</h3>
                <p>Criação de protótipos, interfaces e identidade visual com foco em facilidade de uso.</p>
            </div>
        </div>
    </section>
</body>
</html>

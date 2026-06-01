# agrinho
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cultivando o Futuro - Agricultura Familiar</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header class="main-header">
        <div class="logo">
            <span class="logo-icon">🌱</span> AgroTech Autoral
        </div>
        <nav class="main-nav">
            <a href="#sobre">Sobre</a>
            <a href="#dados">Dados Reais</a>
            <a href="#fontes">Fontes & Créditos</a>
        </nav>
    </header>

    <section class="hero-section">
        <div class="hero-content">
            <h1>A Força da Agricultura Familiar</h1>
            <p>Conectando tecnologia, sustentabilidade e dados reais para transformar o campo.</p>
        </div>
    </section>

    <main class="container">
        <section id="dados" class="data-section">
            <h2>Dados Reais do Campo</h2>
            <p class="subtitle">Informações baseadas no Censo Agropecuário para contextualizar nossa realidade.</p>
            
            <div class="grid-cards">
                <div class="card">
                    <h3>77%</h3>
                    <p>Dos estabelecimentos agrícolas do país pertencem à agricultura familiar.</p>
                </div>
                <div class="card">
                    <h3>67%</h3>
                    <p>Dos profissionais ocupados na agropecuária trabalham nesse setor.</p>
                </div>
                <div class="card">
                    <h3>Alimento na Mesa</h3>
                    <p>Setor responsável pela base da produção dos alimentos consumidos diariamente pelos brasileiros.</p>
                </div>
            </div>
        </section>

        <hr>

        <section id="fontes" class="sources-section">
            <h2>Uso Ético de Mídias e Fontes</h2>
            <p>Em respeito aos direitos de autoria e transparência de dados, listamos abaixo todas as referências utilizadas neste projeto:</p>
            
            <ul class="sources-list">
                <li>
                    <strong>Dados Estatísticos:</strong> Instituto Brasileiro de Geografia e Estatística (IBGE) - Censo Agropecuário.
                </li>
                <li>
                    <strong>Imagem de Fundo (Hero):</strong> Fotografia de domínio público obtida via Wikimedia Commons / Pixabay (Licença Creative Commons CC0).
                </li>
                <li>
                    <strong>Identidade Visual & Ícones:</strong> Desenvolvidos do zero pelo autor utilizando a ferramenta Canva/Piskel.
                </li>
            </ul>
        </section>
    </main>

    <footer class="main-footer">
        <p>&copy; 2026 - Projeto Desenvolvido de Forma Autoral para a Competição.</p>
    </footer>

</body>
</html>


/* Configurações Gerais e Cores Base (Identidade Agro) */
:root {
    --primary-color: #2c5e3b; /* Verde folha escuro */
    --accent-color: #8b5a2b;  /* Tom terra/madeira */
    --light-bg: #f4f7f5;      /* Fundo claro suave */
    --dark-text: #2b2b2b;
    --white: #ffffff;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
    background-color: var(--light-bg);
    color: var(--dark-text);
    line-height: 1.6;
}

.container {
    max-width: 1100px;
    margin: 0 auto;
    padding: 20px;
}

/* Cabeçalho */
.main-header {
    background-color: var(--primary-color);
    color: var(--white);
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 40px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

.logo {
    font-size: 1.5rem;
    font-weight: bold;
}

.main-nav a {
    color: var(--white);
    text-decoration: none;
    margin-left: 20px;
    font-weight: 500;
    transition: color 0.3s;
}

.main-nav a:hover {
    color: #a3e2a4;
}

/* Banner Hero */
.hero-section {
    background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://picsum.photos/1200/400?blur=1') no-repeat center center/cover;
    height: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: var(--white);
    padding: 20px;
}

.hero-content h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

/* Seção de Dados (Cards) */
.data-section {
    padding: 40px 0;
    text-align: center;
}

.subtitle {
    color: #666;
    margin-bottom: 30px;
}

.grid-cards {
    display: flex;
    gap: 20px;
    justify-content: space-between;
    flex-wrap: wrap;
}

.card {
    background-color: var(--white);
    flex: 1;
    min-width: 250px;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    border-top: 5px solid var(--accent-color);
    transition: transform 0.3s;
}

.card:hover {
    transform: translateY(-5px);
}

.card h3 {
    font-size: 2.5rem;
    color: var(--primary-color);
    margin-bottom: 10px;
}

/* Fontes e Créditos */
.sources-section {
    padding: 40px 0;
}

.sources-list {
    margin-top: 20px;
    list-style-position: inside;
    background-color: #eaefe9;
    padding: 20px;
    border-radius: 8px;
}

.sources-list li {
    margin-bottom: 10px;
}

hr {
    border: 0;
    height: 1px;
    background: #ddd;
    margin: 40px 0;
}

/* Rodapé */
.main-footer {
    background-color: #1e3d26;
    color: #b3cbb8;
    text-align: center;
    padding: 20px;
    margin-top: 40px;
    font-size: 0.9rem;
}

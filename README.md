<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Objetivos de Desenvolvimento Sustentável (ODS)</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Objetivos de Desenvolvimento Sustentável</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#objetivo1">Objetivo 1</a></li>
            <li><a href="#objetivo2">Objetivo 2</a></li>
            <li><a href="#objetivo3">Objetivo 3</a></li>
            <!-- Adicione mais links para outros ODS conforme necessário -->
        </ul>
    </nav>
    <main>
        <section>
            <h2>Introdução aos ODS</h2>
            <p>Os Objetivos de Desenvolvimento Sustentável (ODS) são um apelo global à ação para acabar com a pobreza, proteger o planeta e garantir que todas as pessoas desfrutem de paz e prosperidade.</p>
        </section>
        <section>
            <h2>Detalhamento dos ODS</h2>
            <article id="objetivo1">
                <h3>Objetivo 1: Erradicação da Pobreza</h3>
                <p>Descrição do objetivo e ações para erradicar a pobreza.</p>
                <p>Informações adicionais e estratégias de combate à pobreza.</p>
                <p>Como a sociedade pode contribuir para a erradicação da pobreza.</p>
            </article>
            <article id="objetivo2">
                <h3>Objetivo 2: Fome Zero e Agricultura Sustentável</h3>
                <p>Descrição do objetivo e ações para combater a fome.</p>
                <p>Iniciativas para promover a agricultura sustentável.</p>
                <p>Como organizações internacionais estão atuando nesse âmbito.</p>
            </article>
            <!-- Continue adicionando artigos para os outros ODS -->
        </section>
        <section>
            <h2>Detalhamento Interativo dos ODS</h2>
            <div class="accordion">
                <button class="accordion-button">Objetivo 1: Erradicação da Pobreza</button>
                <div class="accordion-content">
                    <p>Descrição do objetivo e ações para erradicar a pobreza.</p>
                </div>
                <button class="accordion-button">Objetivo 2: Fome Zero e Agricultura Sustentável</button>
                <div class="accordion-content">
                    <p>Descrição do objetivo e ações para combater a fome.</p>
                </div>
                <!-- Continue adicionando botões e conteúdos para outros ODS -->
            </div>
        </section>
    </main>
    <footer>
        <p>Informações adicionais, créditos e links úteis.</p>
    </footer>
    <script>
        // Script para funcionalidade do accordion
        const accordions = document.querySelectorAll('.accordion-button');
        accordions.forEach(button => {
            button.addEventListener('click', () => {
                const content = button.nextElementSibling;
                content.style.display = content.style.display === 'block' ? 'none' : 'block';
            });
        });
    </script>
</body>
</html>
/* Estilos básicos para o corpo */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}

/* Estilo do cabeçalho */
header {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 1em 0;
}

/* Estilo da barra de navegação */
nav {
    background-color: #333;
    overflow: hidden;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    padding: 14px 20px;
    display: block;
}

/* Estilo para as seções */
section {
    padding: 20px;
    margin: 10px;
    background: white;
    border-radius: 8px;
}

/* Estilo do rodapé */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1em 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}

/* Estilos para o accordion */
.accordion-button {
    background-color: #4CAF50;
    color: white;
    border: none;
    padding: 15px;
    text-align: left;
    width: 100%;
    cursor: pointer;
    outline: none;
    transition: background-color 0.4s;
    margin-top: 10px;
    border-radius: 4px;
}

accordion-button:hover {
    background-color: #45a049;
}

accordion-content {
    display: none;
    padding: 15px;
    background-color: #f9f9f9;
    border-radius: 4px;
    margin-top: 5px;
}# site

# a-es-do-mundo
ações que transformam o mundo 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Ações Transformadoras</title>
</head>
<body>
    <header>
        <h1>Ações Transformadoras</h1>
        <nav>
            <ul>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#projetos">Projetos</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="sobre">
        <h2>Sobre Nós</h2>
        <p>Conheça nossa missão de transformar o mundo através de ações positivas.</p>
    </section>

    <section id="projetos">
        <h2>Projetos</h2>
        <div class="project">
            <img src="project1.jpg" alt="Projeto 1">
            <h3>Projeto 1</h3>
            <p>Descrição do Projeto 1.</p>
        </div>

        <div class="project">
            <img src="project2.jpg" alt="Projeto 2">
            <h3>Projeto 2</h3>
            <p>Descrição do Projeto 2.</p>
        </div>
    </section>

    <section id="contato">
        <h2>Entre em Contato</h2>
        <form>
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <textarea id="mensagem" name="mensagem" placeholder="Digite sua mensagem..." required></textarea>

            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2023 Ações Transformadoras</p>
    </footer>
</body>
</html> 

body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1em;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav a {
    text-decoration: none;
    color: #fff;
}

section {
    padding: 40px;
}

.project {
    margin-bottom: 40px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em;
}

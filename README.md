<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Portfólio Pessoal</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
}

header {
    background: #222;
    color: white;
    text-align: center;
    padding: 20px;
}

nav ul {
    list-style: none;
}

nav li {
    display: inline-block;
    margin: 10px;
}

nav a {
    color: white;
    text-decoration: none;
}

main {
    max-width: 1000px;
    margin: auto;
    padding: 20px;
}

section {
    background: white;
    margin-bottom: 20px;
    padding: 20px;
    border-radius: 10px;
}

.cards {
    display: flex;
    gap: 15px;
    flex-wrap: wrap;
}

.card {
    background: #eee;
    padding: 15px;
    flex: 1;
    min-width: 250px;
    border-radius: 8px;
}

button {
    background: #0077cc;
    color: white;
    border: none;
    padding: 10px;
    border-radius: 5px;
    cursor: pointer;
}

input,
textarea {
    width: 100%;
    margin-top: 10px;
    padding: 10px;
}

footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 15px;
}

@media (max-width: 768px) {

    nav li {
        display: block;
    }

    .cards {
        flex-direction: column;
    }
}
</style>

</head>
<body>

<header>
    <h1>Meu Portfólio</h1>

    <nav>
        <ul>
            <li><a href="#sobre">Sobre</a></li>
            <li><a href="#projetos">Projetos</a></li>
            <li><a href="#contato">Contato</a></li>
        </ul>
    </nav>
</header>

<main>

<section id="sobre">
    <h2>Sobre Mim</h2>

    <p>
        Sou estudante de Engenharia de Software e estou aprendendo
        desenvolvimento Front-End com HTML5, CSS3 e JavaScript.
    </p>
</section>

<section id="projetos">

    <h2>Projetos</h2>

    <div class="cards">

        <div class="card">
            <h3>Projeto 1</h3>
            <p>Site responsivo.</p>
        </div>

        <div class="card">
            <h3>Projeto 2</h3>
            <p>Landing page.</p>
        </div>

        <div class="card">
            <h3>Projeto 3</h3>
            <p>Sistema de estudos.</p>
        </div>

    </div>

</section>

<section>

    <h2>Interatividade</h2>

    <button onclick="mostrarMensagem()">
        Clique Aqui
    </button>

    <p id="mensagem"></p>

</section>

<section id="contato">

    <h2>Contato</h2>

    <form>

        <input type="text" placeholder="Nome">

        <input type="email" placeholder="E-mail">

        <textarea placeholder="Mensagem"></textarea>

        <button type="submit">
            Enviar
        </button>

    </form>

</section>

</main>

<footer>
    <p>© 2026 - Meu Portfólio</p>
</footer>

<script>
function mostrarMensagem() {
    document.getElementById("mensagem").innerHTML =
    "Olá! Esta mensagem foi exibida utilizando JavaScript.";
}
</script>

</body>
</html># IMPLEMENTA-O-FRONT-END

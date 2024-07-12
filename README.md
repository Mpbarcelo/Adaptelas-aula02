# Tarefa - Fundamentos de HTML

## Descrição

Para iniciarmos nossas atividades com a programação Web, vamos começar criando o esqueleto da nossa página web. Nesta tarefa, você irá utilizar as tags HTML apresentadas em sala para montar toda a estrutura do site. Não se preocupe em estilizar essa página, pois vamos aprender isso nas próximas aulas.

## Objetivo

- Aprender a estrutura básica de um documento HTML.
- Utilizar corretamente as tags HTML para criar a estrutura do site.

## Instruções

1. Crie um novo arquivo chamado `index.html`.
2. Utilize as seguintes tags HTML para montar a estrutura da página:
   - `<!DOCTYPE html>`
   - `<html>`
   - `<head>`
   - `<title>`
   - `<meta charset="UTF-8">`
   - `<body>`
   - `<header>`
   - `<nav>`
   - `<main>`
   - `<section>`
   - `<article>`
   - `<footer>`
3. No `<head>`, inclua:
   - A declaração do tipo de documento com `<!DOCTYPE html>`.
   - A tag `<meta charset="UTF-8">` para definir a codificação de caracteres.
   - A tag `<title>` para dar um título à sua página.
4. No `<body>`, organize a estrutura da sua página utilizando as tags de cabeçalho (`<header>`), navegação (`<nav>`), conteúdo principal (`<main>`, `<section>`, `<article>`) e rodapé (`<footer>`).

### Exemplo de Estrutura HTML

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Título da Página</title>
</head>
<body>
    <header>
        <h1>Bem-vindo ao meu site</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#sobre">Sobre</a></li>
            <li><a href="#contato">Contato</a></li>
        </ul>
    </nav>
    <main>
        <section id="home">
            <h2>Home</h2>
            <p>Esta é a seção Home.</p>
        </section>
        <section id="sobre">
            <h2>Sobre</h2>
            <p>Esta é a seção Sobre.</p>
        </section>
        <section id="contato">
            <h2>Contato</h2>
            <p>Esta é a seção Contato.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Meu Site</p>
    </footer>
</body>
</html>

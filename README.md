# Exerc-cios---HTML
1. Função das Tags, Corpo e Atributos de um Elemento HTML
Tags: As tags são usadas para definir os elementos HTML e suas propriedades. Elas geralmente vêm em pares: uma tag de abertura (<tag>) e uma tag de fechamento (</tag>), com o conteúdo a ser exibido entre elas. As tags são usadas para estruturar o conteúdo da página, por exemplo, <h1>, <p>, <a>, etc.

Corpo: O corpo do elemento HTML refere-se à parte interna de uma tag. O conteúdo que aparece na página do navegador fica entre as tags de abertura e de fechamento. Por exemplo, no código <h1>Bem-vindo</h1>, a palavra "Bem-vindo" é o corpo do elemento <h1>.

Atributos: Os atributos são informações adicionais que podem ser adicionadas a uma tag HTML para modificar seu comportamento ou aparência. Eles ficam dentro da tag de abertura. Por exemplo, o atributo href em uma tag <a> define o link de destino: <a href="https://example.com">Link</a>. Atributos comuns incluem class, id, src, alt, href, entre outros.

2. Elemento Vazio: O que é e Exemplos
Elemento Vazio: Um elemento vazio (ou auto-fechado) é um elemento HTML que não possui um corpo ou conteúdo entre a tag de abertura e de fechamento. Eles são usados para inserir objetos na página ou para aplicar efeitos sem adicionar conteúdo textual. Esses elementos não têm uma tag de fechamento.

Funcionalidade: O propósito dos elementos vazios é permitir a inclusão de funcionalidades ou recursos, como imagens, links, ou campos de formulário, sem conteúdo textual.

Exemplos:

<img src="imagem.jpg" alt="Descrição da imagem"> — A tag <img> é um elemento vazio que insere uma imagem.
<br> — A tag <br> é usada para quebrar uma linha em um parágrafo, sem conteúdo adicional.
<!DOCTYPE html>
<html>
    <body>
        <h1>Bem-vindo</h1>
        <p>
            Seja bem-vindo a essa página, terrestre. Tenho uma <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ">surpresa</a> pra vc.
        </p>
    </body>
</html>
<!DOCTYPE html>
<html>
    <head>
        <title>Aninhamento HTML</title>
    </head>
    <body>
        <header>
            <h1>Bem-vindo ao Meu Site</h1>
            <nav>
                <ul>
                    <li><a href="#">Página Inicial</a></li>
                    <li><a href="#">Sobre</a></li>
                    <li><a href="#">Contato</a></li>
                </ul>
            </nav>
        </header>

        <main>
            <article>
                <h2>Artigo 1</h2>
                <p>Este é o primeiro artigo do meu site. Contém informações importantes.
                    <strong>Leia atentamente</strong> antes de continuar.
                </p>
                <a href="#">Saiba mais</a>
            </article>

            <article>
                <h2>Artigo 2</h2>
                <p>O segundo artigo aborda um tópico diferente. É igualmente relevante.
                    <strong>Fique ligado</strong> para mais atualizações.
                </p>
                <a href="#">Detalhes aqui</a>
            </article>
        </main>

        <footer>
            <p>&copy; 2023 Meu Site. Todos os direitos reservados.</p>
        </footer>
    </body>
</html>
a. Quais elementos são os vizinhos de <main>?
Os elementos vizinhos de <main> são:
<header>: Está imediatamente antes de <main>.
<footer>: Está imediatamente depois de <main>.
b. Quais elementos são os ancestrais de <ul>?
Os ancestrais de <ul> são:
<html>
<body>
<header>
<nav> (O <ul> está dentro do <nav>, então o <nav> é o ancestral direto de <ul>).
c. Quais elementos são filhos de <header>?
Os filhos de <header> são:
<h1>
<nav>
d. Qual o nível de profundidade do aninhamento entre <html> e <strong> do primeiro artigo?
A profundidade de aninhamento entre <html> e <strong> no primeiro artigo é de 6 níveis. O caminho seria o seguinte:
<html> → <body> → <main> → <article> → <p> → <strong>

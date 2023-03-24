# porfolio
Porfolio feito com HTML/CSS
comente todo código html em portuguê: <!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portifolio</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header></header>
    <main class="apresentacao">
        <section class="apresentacao__conteudo">
            <h1 class="apresentacao__conteudo__titulo">Eleve seu negócio digital a outro nível<strong 
            class="titulo-destaque"> com um Front-end de qualidade!
            </strong></h1>
            <p class="apresentacao__conteudo__texto">Olá! Sou Waldir Neto, desenvolvedor
            Front-end com especialidade em, HTML e
            CSS. WORDPRESS, Ajudo pequenos negócios e designers a
            colocarem em prática boas ideias. Vamos
            conversar?</p>
            <div class="apresentacao__links">
                <a class="apresentacao__links__link" href="https://www.linkedin.com/in/waldir-garcia-5972b8179">Linkeid</a>
                <a class="apresentacao__links__link" href="https://github.com/waldirgarcia/">GitHub</a>
           </div>   
        </section>
        <img src="imagem.png" alt="Foto da Waldir Neto programando">
    </main>
    <footer></footer>
</body>

</html>

O código HTML acima é um exemplo de estruturação básica de uma página web. Veja abaixo uma explicação do que cada linha significa:

<!DOCTYPE html> - Define o tipo de documento como HTML5.
<html lang="pt-br"> - Define a linguagem da página como português brasileiro.
<head> - Inicia o cabeçalho da página.
<meta charset="UTF-8"> - Define a codificação de caracteres como UTF-8.

<meta http-equiv="X-UA-Compatible" content="IE=edge"> - Define que a página deve ser exibida na versão mais recente do Internet Explorer.

<meta name="viewport" content="width=device-width, initial-scale=1.0"> - Define a escala inicial para dispositivos móveis.

<title>Portifolio</title> - Define o título da página como "Portifolio".
<link rel="stylesheet" href="style.css"> - Importa um arquivo CSS externo para estilizar a página.
</head> - Finaliza o cabeçalho da página.
<body> - Inicia o corpo da página.
<header></header> - Define uma seção de cabeçalho da página.
<main class="apresentacao"> - Define uma seção principal da página, com a classe "apresentacao".
<section class="apresentacao__conteudo"> - Define uma seção dentro da seção principal, com a classe "apresentacao__conteudo".
<h1 class="apresentacao__conteudo__titulo">Eleve seu negócio digital a outro nível<strong 
class="titulo-destaque"> com um Front-end de qualidade!
</strong></h1> - Define um título dentro da seção, com a classe "apresentacao__conteudo__titulo" e um destaque em negrito.
<p class="apresentacao__conteudo__texto">Olá! Sou Waldir Neto, desenvolvedor
Front-end com especialidade em, HTML e
CSS. WORDPRESS, Ajudo pequenos negócios e designers a
colocarem em prática boas ideias. Vamos
conversar?</p> - Define um parágrafo dentro da seção, com a classe "apresentacao__conteudo__texto".
<div class="apresentacao__links"> - Define uma divisão dentro da seção, com a classe "apresentacao__links".
<a class="apresentacao__links__link" href="https://www.linkedin.com/in/waldir-garcia-5972b8179">Linkeid</a> - Define um link dentro da divisão, com a classe "apresentacao__links__link" e um link para o perfil do LinkedIn do autor.

<a class="apresentacao__links__link" href="https://github.com/waldirgarcia/">GitHub</a> - Define um link dentro da divisão, com a classe "apresentacao__links__link" e um link para o perfil do GitHub do autor.

</div> - Finaliza a divisão dentro da seção.
</section> - Finaliza a seção dentro da seção principal.
<img src="imagem.png" alt="Foto da Waldir Neto programando"> - Define uma imagem dentro da seção principal, com um caminho para um arquivo de imagem e uma descrição alternativa.

</main> - Finaliza a seção principal.
<footer></footer> - Define uma seção de rodapé da página.
</body> - Finaliza o corpo da página.
</html> - Finaliza o documento HTML.




CSS


A primeira linha faz o import de uma fonte externa do Google Fonts para ser utilizada no código.
O seletor universal * remove a margem e o preenchimento de todos os elementos HTML.
O seletor body define as propriedades de estilo do corpo da página HTML, como a cor de fundo e a cor do texto. A altura do corpo é definida como 100% da altura da viewport.
O seletor .titulo-destaque define a cor do texto para um tom de azul mais claro.
O seletor .apresentacao define as propriedades de estilo do contêiner principal do conteúdo da página HTML. É definido um espaçamento em torno do contêiner e um layout flexível com espaçamento uniforme entre os itens filhos.
O seletor .apresentacao__conteudo define as propriedades de estilo do contêiner do conteúdo principal da página HTML, como a largura, o layout flexível com espaçamento uniforme entre os itens filhos e o espaçamento entre esses itens.
O seletor .apresentacao__conteudo__titulo define a fonte, o tamanho da fonte e outras propriedades de estilo do título principal do conteúdo da página HTML.
O seletor .apresentacao__conteudo__texto define a fonte, o tamanho da fonte e outras propriedades de estilo do texto principal do conteúdo da página HTML.
O seletor .apresentacao__links define as propriedades de estilo do contêiner que agrupa os links de redes sociais da página HTML. O layout é definido como flexível com espaçamento uniforme entre os itens filhos.
O seletor .apresentacao__links__link define as propriedades de estilo dos links das redes sociais da página HTML, como a cor de fundo, o tamanho da fonte, o peso da fonte e o espaçamento ao redor do texto. Também é removido o sublinhado dos links e definida a cor do texto como preta.

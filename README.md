
# Desafios HTML e CSS: Ambientes de desenvolvimento, estrutura de arquivos e tags

## Oracle Next Education e Alura Latam

### Exercícios propostos durante o Módulo: Documentação e HTML

1) Construindo a estrutura básica do HTML
Você acabou de iniciar um estágio em uma empresa de desenvolvimento web e sua primeira tarefa é criar um documento HTML básico para um novo projeto. O objetivo é construir a estrutura fundamental de um arquivo HTML, incluindo as tags essenciais: ```<!DOCTYPE html>```, ```<html>```, ```<head>```, e ```<body>```. Além disso, dentro da tag <head>, adicione uma tag ```<title>``` com um título de sua escolha para a página. Lembre-se de seguir as práticas de indentação corretas para manter o código organizado.

```ruby
<!DOCTYPE html>
<html>
    <head>
        <title>Desenvolvimento Web</title>
    </head>
    <body>

    </body>
</html>
```

2) Adicionando conteúdo ao HTML
Agora que a estrutura básica do seu documento HTML está pronta, seu supervisor pediu para adicionar um cabeçalho e um parágrafo ao corpo do documento. Use as tags ```<h1>``` para o cabeçalho e ```<p>``` para o parágrafo. Escolha um tema para o cabeçalho e escreva um breve parágrafo relacionado a esse tema.

```ruby
<!DOCTYPE html>
<html>
    <head>
        <title>Desenvolvimento Web</title>
    </head>
    <body>
        <h1>Páginas da Web</h1>
        <p>Para criar páginas da web, devemos começar fazendo a estrutura básica do código HTML.<p>
    </body>
</html>
```

3) Trabalhando com meta tags e título
Você precisa otimizar a seção ```<head>``` da página HTML existente. Adicione uma meta tag para definir a codificação de caracteres como UTF-8 e altere o título da página para algo mais descritivo e apropriado para o conteúdo do site.

```ruby
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>Aprendendo HTML</title>
    </head>
    <body>
        <h1>Páginas da Web</h1>
        <p>Para criar páginas da web, devemos começar fazendo a estrutura básica do código HTML.<p>
    </body>
</html>
```

4) Organizando conteúdo com tags HTML
Você está desenvolvendo a página inicial de um site para um projeto pessoal. Você precisa criar um título principal e um subtítulo, seguidos por um breve parágrafo explicativo. Utilize HTML para estruturar esses elementos. Crie um arquivo HTML e adicione um título principal com a tag ```<h1>```, um subtítulo com a tag ```<h2>```, e um parágrafo com a tag ```<p>```. Use textos de sua escolha para cada um destes. Lembre-se de seguir a hierarquia correta das tags e verificar o resultado no navegador.

```ruby
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>Meu Projeto</title>
    </head>
    <body>
        <h1>Meu Projeto Pessoal</h1>
        <h2>Introdução do Projeto</h2>
        <p>O projeto foi desenvolvido...<p>
    </body>
</html>
```

5) Adicionando imagens com acessibilidade
Neste desafio, você vai adicionar uma imagem ao seu projeto de site pessoal. Escolha uma imagem de sua preferência (pode ser um logo ou uma foto relacionada ao tema do site). Utilize a tag ```<img>``` para inserir a imagem no corpo do documento HTML, e não se esqueça de incluir o atributo alt para descrever a imagem, melhorando a acessibilidade do site. Verifique o resultado no navegador.

```ruby
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>Meu Projeto</title>
    </head>
    <body>
        <h1>Meu Projeto Pessoal</h1>
        <h2>Introdução do Projeto</h2>
        <img src="imagem.png" alt="Imagem do Projeto">
        <p>O projeto foi desenvolvido...<p>
    </body>
</html>
```

6) Listando Itens em HTML
Agora, adicione uma lista de itens ao seu site. Esta lista pode ser de características do projeto, etapas de desenvolvimento, ou qualquer outra informação relevante. Utilize a tag ```<ul>``` para uma lista não ordenada ou ```<ol>``` para uma lista ordenada, e ```<li>```para cada item da lista. Verifique o layout no navegador após a inserção.

```ruby
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>Meu Projeto</title>
    </head>
    <body>
        <h1>Meu Projeto Pessoal</h1>
        <h2>Introdução do Projeto</h2>
        <img src="imagem.png" alt="Imagem do Projeto">
        <p>O projeto foi desenvolvido...<p>
        <ul>
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
        </ul>
    </body>
</html>
```

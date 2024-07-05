
# Desafios HTML e CSS: Ambientes de desenvolvimento, estrutura de arquivos e tags

## Oracle Next Education e Alura Latam

### Exercícios propostos durante o Módulo: Layout e tags semânticas

1) Construindo a estrutura HTML do portfólio
Você acaba de receber um layout de uma página de portfólio da sua designer. O desafio é transformar esse design em uma página web funcional. Utilizando HTML, crie a estrutura básica da página. Lembre-se de incluir os elementos principais: um título principal, um subtítulo, dois botões (Instagram e Github), e um espaço para a imagem da desenvolvedora. Sinta-se livre para personalizar o texto e a imagem para adaptá-los ao seu portfólio pessoal.
    ```ruby
    <!DOCTYPE html>
    <head>
        <title>Portfolio do Flavio Santana<title>
    </head>
    <body>
        <h1>Portfolio do Flavio Santana</strong></h1>
        <p>Olá! Sou Flávio Santana, desenvolvedor Front-end</p>
        <button>LinkedIn</button>
        <abutton>GitHub<button>
        <img src="imagem.png" alt="Foto no estilo selfie do Flávio Santana">
    </body>
    </html>
    ```

2) Estruturando a página com tags semânticas
Agora que você entende a importância das tags semânticas no HTML, é hora de aplicar esse conhecimento. Utilize as tags header, main, e footer para estruturar sua página de portfólio. No header, insira um menu ou um logotipo. No main, adicione os elementos do portfólio como título, parágrafo, botões e imagem. Por fim, no footer, coloque informações como contato ou direitos autorais. Lembre-se de que cada elemento deve ser colocado de forma lógica e estruturada para criar um site acessível e bem organizado.
    ```ruby
    <!DOCTYPE html>
    <html lang="pt-br">
    <head>
        <title>Portfolio do Flavio Santana<title>
    </head>
    <body>
        <header>
            <img src="logo.png">
        </header>
        <main>
            <h1>Portfolio do Flavio Santana</strong></h1>
            <p>Olá! Sou Flávio Santana, desenvolvedor Front-end</p>
            <button>LinkedIn</button>
            <abutton>GitHub<button>
            <img src="imagem.png" alt="Foto no estilo selfie do Flávio Santana">
        </main>
        <footer>
            Site desenvolvido por Flavio Santana
        </footer>
    </body>
    </html>
    ```

3) Entendendo e aplicando as tags meta
Explore o uso das tags meta no cabeçalho do seu HTML. Altere a tag lang para "pt-br", ajuste o charset para "UTF-8", adicione a tag meta para compatibilidade com o Edge e outra para configuração do viewport. Por fim, mude o título da sua página para algo relacionado ao seu projeto, por exemplo, "Portfólio de [Seu Nome]". Entenda como cada uma dessas mudanças afeta a funcionalidade e a acessibilidade do seu site.
    ```ruby
    <!DOCTYPE html>
    <html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Portfólio de Flavio Santana</title>
    </head>
    <body>
        <!-- Estrutura da página -->
    </body>
    </html>
    ```

4) Inserindo e formatando elementos no HTML
Agora que você já tem uma base sólida sobre a estrutura HTML, vamos adicionar e formatar elementos na sua página de portfólio. Siga o layout do Figma e comece adicionando um título (```<h1>```) com um destaque (```<strong>```) em uma parte dele. Em seguida, insira um parágrafo (```<p>```) com uma breve introdução sobre você ou sua empresa. Finalmente, adicione links (```<a>```) para suas redes sociais ou portfólios online, como Instagram e GitHub. Certifique-se de que cada elemento esteja corretamente formatado e colocado conforme o design do Figma.
    ```ruby
    <!DOCTYPE html>
    <html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Portfolio</title>
    </head>
    <body>
        <header></header>
        <main>
            <h1>Eleve seu negócio digital a outro nível <strong>com um Front-end de qualidade!</strong></h1>
            <p>Olá! Sou Flávio Santana, desenvolvedor Front-end com especialidade em React, HTML e CSS. Ajudo pequenos negócios e designers a colocarem em prática boas ideias. Vamos conversar?</p>
            <a href="https://linkedin.com/in/flavioafsantana">LinkedIn</a>
            <a href="https://github.com/flavioafsantana">GitHub</a>
            <img src="imagem.png" alt="Foto no estilo selfie do Flávio Santana">
        </main>
        <footer></footer>
    </body>
    </html>
    ```

5) Incorporando imagens com tags HTML
Chegou a hora de dar um toque visual à sua página! Escolha uma imagem que represente você ou seu trabalho e adicione-a à sua página de portfólio usando a tag <img>. Lembre-se de incluir a propriedade src com o caminho para a imagem e alt com uma descrição adequada da imagem. Isso não apenas melhora a acessibilidade do seu site, mas também ajuda os motores de busca a entenderem o conteúdo da imagem.
    ```ruby
    <img src="imagem.png" alt="Pessoa desenvolvendo">
    ```

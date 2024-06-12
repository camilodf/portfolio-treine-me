![image](https://github.com/camilodf/portfolio-treine-me/assets/38727814/b59a32ff-8aa8-44ee-9a44-9b5545b482d7)

Treine.me
Bem-vindo ao repositório do Treine.me! Este projeto é um exemplo de portfólio de aprendizado, focado em desenvolver habilidades em HTML e CSS.

Sobre o Projeto
O Treine.me é um site fictício voltado para a promoção de treinos personalizados. O projeto visa proporcionar uma experiência visual agradável, utilizando boas práticas de desenvolvimento web, design responsivo e uma estrutura de código limpa e organizada.

Tecnologias Utilizadas
HTML5: Linguagem de marcação utilizada para estruturar o conteúdo do site.
CSS3: Linguagem de estilo utilizada para a apresentação visual do conteúdo.
Google Fonts: Fonte externa para melhor tipografia.
Design Responsivo: O layout do site se adapta a diferentes tamanhos de tela.

Estrutura do Projeto
A estrutura do projeto é simples e organizada para facilitar a compreensão e manutenção do código.

vbnet
Copiar código
treine.me/
├── images/
│   ├── balls.svg
│   ├── jump.png
│   ├── logo.svg
│   └── whatsapp.svg
├── style.css
└── index.html
Arquivos
HTML (index.html)
html
Copiar código
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Treine me</title>

    <link href="https://fonts.googleapis.com/css2?family=Mulish:ital,wght@0,200..1000;1,200..1000&family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="page">
        
        <nav>
            <a id="logo" href="#">
                <img src="/images/logo.svg" alt="Treine.me">
            </a>
            <ul>
               <li><a href="#">Home</a></li>
               <li><a href="#">Sobre</a></li>
               <li><a href="#">Treinar</a></li>
            </ul> 
        </nav>
        

        <main>
            <section class="text">
                <h1>Treinos <span>exclusivos</span> para você!</h1>

                <p>
                    Nós criamos treinos <strong>exclusivos e únicos para você</strong>. <br/>
                    Invista no seu corpo e tenha <strong>muito mais performance</strong> e qualidade de vida.
                </p>

                <button>
                    <img src="/images/whatsapp.svg" alt="icone do whatsapp">
                    Comece já
                </button>
            </section>

            <img src="/images/jump.png" alt="desenho de uma mulher pulando corda">
        </main>

        <footer>
            Fale conosco no instagram
            <a href="https://instagram.com/treineme" target="_blank">@treine.me</a>
        </footer>
    </div>

        <img id="balls" 
             src="images/balls.svg" 
             alt="Bolinhas no canto inferior direito"
        >

</body>
</html>
CSS (style.css)
css
Copiar código
body{
    margin: 0;
    font-family: 'Open Sans', sans-serif;

    background: linear-gradient(180deg, rgba(227, 255, 248, 0) 82.08%, rgba(227, 255, 248, 0.38), 100%);
}

.page{
    width: 1000px;
    margin: 65px auto 0;
}

nav{
    display: flex;
    justify-content: space-between;
    margin-bottom: 55px;
    align-items: center;
}

ul{
    display: flex;
    gap: 48px;
    list-style: none;
    margin: 0;
    padding: 0;
}

/*pseudo Class*/

ul li a {
    color: #1F1534;
    text-decoration: none;
    opacity: 0.5;
}

ul li a:hover {
    font-weight: bold;
}

h1, ul{
    font-family: 'Mulish', sans-serif;
}

main{
    display: flex;
    align-items: center;
    justify-content: space-between;
}

h1{
    font-size: 49px;
    line-height: 56px;
    color: #000;

    font-weight: normal;

    width: 490px;
}

h1 span{
    color: #89C5CC;
    font-weight: bold;
}

section p{
    font-size: 14px;
    line-height: 28px;
    color: #7D7987;

    margin: 40px 0;
}

button{
    color: white;
    text-transform: uppercase;
    font-family: 'Open Sans', sans-serif;

    background: #69B99D;
    border: none;
    padding: 14px 32px 15px;

    display: flex;
    align-items: center;
    justify-content: center;
    gap: 10px;

    border-radius: 4px;

    cursor: pointer;
}

button:hover{
    background: #4ec59c;
}

footer{
    text-align: center;
    font-size: 14px;
    line-height: 28px;

    margin-top: 80px;
}

footer a{
    font-weight:  bold;
    text-decoration: none;
    color: #000;
}

#balls{
    position: fixed;
    bottom: 0;
    right: 0;
}
Como Utilizar
Clone o repositório:
bash
Copiar código
git clone https://github.com/seu-usuario/treine-me.git
Navegue até o diretório do projeto:
bash
Copiar código
cd treine-me
Abra o arquivo index.html no seu navegador.
Contribuição
Se você deseja contribuir com o projeto, sinta-se à vontade para abrir um Pull Request. Sugestões e melhorias são sempre bem-vindas!

Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.

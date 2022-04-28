Modulo 1:

Livros para aprender HTML5 e CSS3:

Material de apoio do Curso em Video - PDF do curso
Referencia MDN
Referencia W3C Standards
WHATWG Living Standard
W3Schools
HTML5 Entendendo e Executando
CSS Guia definitivo
Flexbox in CSS
Grid layout in CSS
HTML5 e CSS3
HTML&CSS projete e construa websites
HTML e CSS Use a Cabeça
Crie Seu Proprio Site
HTML5
CSS3
Fundamentos de HTML5 e CSS3
Css Grid Layout
Curso de design grafico
A psicologia das cores
design
pensar com tipos
Flexbox explained
Css grid explained
Smashing Html5
Smashing Css

Capitulo 2:

Dominio: é um endereço para o seu site que deve ter um nome unico, costuma ser pago e tem varios TLDs

Hospedagem: é o espaço para armazenar arquivos, costuma ser paga, deve ser escolhida com base em tamanho dos arquivos, tipos de linguagem, etc

URL: é um endereço que aponta para algum lugar

Capitulo 3:

Como funciona o HTML e o CSS
Não se programa em HTML e em CSS, se diz que se desenvolve em HTML e em CSS

O conteudo de um site é o HTML, o design da página é o CSS e as intercações vem do JavaScript

Capitulo 4:

Algumas tags em HTML:
<h1></h1> -> Titulo em HTML
<p></p> -> Paragrafo em HTML
<img src="foto.png" alt="Exemplo de foto"> -> Carregando uma imagem em HTML

Exemplos de estilo no CSS:
h1{
    font-family: Arial; -> Mudando a fonte da tag h1
    font-size: 20pt; -> Mudando o tamanho da fonte da tag h1
    color: blue; -> Mudando a cor da tag h1
}

Estrutura basica do HTML
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width,initial-scale=1.0"> -> O site vai ser iniciado de forma padrao (sem zoom nem nada)
        <title>Document</title>
    </head> -> Area de configurações
    <body>
        <h1>Olá, Mundo!</h1>
    </body> -> Area de corpo do site
</html>

Se digitar "html" no documento aparece a estrutura basica do HTMl, para nao precisar ficar escrevendo toda hora

Capitulo 5:

Tag <hr> cria uma linha horizontal no site
Tag <br> ele quebra uma linha
Para utilizar <> -> < = &lt; > = &gt;

É errado usar varios <br> em sequencia para quebrar varias linhas, o certo é usar o css pra controlar o tamanho do espacamento

Comentario em HTML <!-- Aqui vai o comentario -->

Para emojis é preciso pegar o código do emojipedia depois do U+ (qualquer duvida ver exercicio 002) e passar assim &#x1F914; onde depois do x vem o codigo do emoji

Capitulo 6:

Não se pode usar toda e qualquer imagem livremente

No google imagens vc pode pesquisar e entrar nas ferramentas e mudar o tipo de imagens para a segunda opção
Unsplash e pexels são alguns exemplos de sites com imagens sem direitos autorais 

GIMP -> photoshop gratuito 

O jpeg costuma ser o formato mais utilizado por não ser um formato pesado
O png é uma otima opçao tambem
Mas depende do que vc precisa tem um formato de arquivo que se encaixa melhor

O tamanho ideal para uma imagem na internet é de até 1500x1000 e a resoluçao é 72

No CSS é possivel mudar o tamanho da imagem tambem, mas nao muda o tamanho do arquivo. Sendo assim é preciso editar a imagem pra deixar um arquivo que pese pouco e então fazer as ediçoes necessarias com o CSS

Usando a tag img:
<img src="logo-html.png" alt="Logo HTML">
não é preciso digitar o src, se colocar o cursor dentro das aspas e utilicar o comando ctrl + espaco aparece as imagens na pasta

Para imagens da web é so passar o endereco da imagem da web no src

Favicon é o icone que fica na frente das abas e é possivel mudar esse icone

Site para pegar icones: iconarchive (baixar como ico)

favicon.cc é um site para desenhar icones

favicon.io transforma varias coisas em icone

e para ter o favicon é so adicionar no head:
<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">

Capitulo 7:
Podemos ter varios h1, h2, h3, h4, h5 ou h6, tudo depende da hierarquia desse titulo na pagina

para gerar um testo x no seu paragrafo é so escrever lorem dentro do <p></p> e dar enter

Certas tags não devem ser mais utilizadas no HTML5, como <center></center>. Agora é necessario usar o css para esse tipo de alterção




 

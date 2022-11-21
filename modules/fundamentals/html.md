<div align='justify'>



# HTML - _HyperText Markup Language_

## Criação do HTML
O HTML foi criado pelo físico, cientista da computação e professor do MIT _Tim Berners-Lee_ , o mesmo criador do _World Wide Web_ (www).
Estimulados pelo êxito da conexão entre um cliente e um servidor na internet, o intuito da linguagem era compartilhar documentos científicos entre os acadêmicos.
A base do HTML é a _SMGL_, liguagem de marcação da qual o HTML herda os seus principais componentes.

## O HTML é uma linguagem de programação?
A resposta é **não!** O HTML é uma linguagem de marcação, portanto não é possível que seja aplicada uma lógica para criar funcionalidades dinâmicas, sendo necessário usar uma linguagem de programação como, por exemplo, o _Javascript_.

## Então para que serve o HTML?
O HTML serve para _**estruturar**_ uma página web, ou melhor falando, montar o **_corpo_** da página e indicar o que cada parte tem de conteúdo, que pode ser um _texto_, uma _imagem_ a até mesmo um _link_, usando uma série de **_tags_**.
As **_tags_** vão auxiliar a estruturar e hierarquizar a construção de uma **_página web_**. 

## Principais tags do HTML
Existem mais de 140 tags HTML, listarei abaixo as mais utilizadas:

| Tag  | Descrição   |
| ------- | -------- |
| `<head>`   | Local onde serão declaradas informações como _títulos_ e _metadados_    |
| `<title>`   | Define o título   |
| `<body>`  | Local onde serão declarados todos os elementos que irão compor o corpo da página   |
| `<h1>,<h2>,<h3>,<h4>,<h5><h6>`  | Definem um título e subtítulos, sendo o h1 o título mais importante e o h6 de menos importância    |
| `<p>`   | Tag para definir um parágrafo   |
| `<a>`   | Define um hiperlink, que é usado para vincular uma página a outra usando o atributo **_href_**   |
| `<header>`   | Define um cabeçalho    |
| `<section>`   | Define uma seção    |
| `<article>`   | Define um artigo    |
| `<div>`   | Define uma divisão    |
| `<footer>`   | Define um rodapé    |
| `<nav>`   | Define uma área de navegação (como menus)   |
| `<table>`   | Define uma tabela    |
| `<ol>`   | Define uma lista ordenada   |
| `<ul>`   | Define uma lista não ordenada    |
| `<li>`   | Define o item de uma lista    |
| `<form>`   | Define um formulário   |
| `<imput>`   | Define os campos de um formulário    |
| `<textarea>`   | Defina uma área onde um usuário irá digitar um texto   |
| `<button>`   | Define um botão    |
| `<img>`   | Permite inserir uma imagem no documento    |

## Atributos de uma tag

Os atributos servem para adicionar uma _funcionalidade_ a _tag_. Abaixo listarei alguns atributois genéricos que podem ser utilizados na maioria das tags

| Atributo  | Descrição   |
| ------- | -------- |
|  `class=”…“ ` | Atribui uma _classe_ ao elemento. Uma classe pode ser utilizada para **um** ou **mais** elementos   |
| `id=”…“`  | Atribui um id ao elemento. Diferente da classe, o _id_ deve ser atribuído a um _único_ elemento  |
| `style=”…”` | Permite incluir elementos _CSS_ dentro da _tag_   |
| `lang=”…”`  | Define o idioma principal do elemento    |
| `title=”…”`  | Define o título do elemento   |
| `alt=”…”`  | Define um texto alternativo, muito utilizado em imagens|
| `hidden`   | Oculta o elemento |
| `align=”…” `   | Define o padrão de alinhamento _right, center, left e justify_  |
| `width=”…”`   | Define a largura do elemento    |
| `height=”…” `   |  Define a altura do elemento      |


## Tags Semânticas

Os elementos semânticos do HTML servem pra descrever de forma clara o seu signficado de forma a ser legível tanto por humanos quanto por máquinas. 
Além de resultar em um código mais consistente, as tags semânticas ajudam também na **acessibilidade**. Os algoritmos de indexação em sites de busca e as tecnologias assistivas (como leitores de tela para usuários com deficiência visual) irão compreender melhor o contexto e conteúdo do sua página, entregando uma melhor experiência para os usuários.
Abaixo estarão listadas as pricipais  tags semânticas:

| Tag  | Descrição   |
| ------- | -------- |
| `<article>`   | Usado para declarar um conteúdo que não precisa de outro para fazer sentido em um documento HTML, por exemplo, um artigo em um blog    |
| `<aside>`   | Utilizado quando precisamos criar um conteúdo de apoio/adicional ao conteúdo principal.   |
| `<details>`  | É usado como uma ferramenta de onde o usuário irá obter informações adicionais |
| `<figcaption>`  | Representa uma legenda ou uma legenda associada com uma figura ou ilustração    |
| `<figure>`   |  É uma marcação de uso específico para a inserção de uma figura.    |
| `<footer>`   | Representa um rodapé de um documento, como a área presente no final de uma página web.   |
| `<header>`   | É utilizado para representar o cabeçalho de um documento ou seção declarado no HTML.    |
| `<main>`   |  Especifica o conteúdo principal e, consequentemente, de maior relevância dentro da página.   |
| `<mark>`   | Representa um trecho de destaque em um texto    |
| `<nav>`   |  Utilizado quando precisamos representar um agrupamento de links de navegação, que, por sua vez, são criados com os elementos `<ul>`, `<li>` e `<a>`   |
| `<section>`   |  representa uma seção dentro de um documento e geralmente contém um título, o qual é definido por meio de um dos elementos entre `<h1`> e `<h6>`    |
| `<summary>`   | É utilizado como um sumário  |
| `<time>`   | Utilizado para representar datas    |


## Tags de **_Link_** e **_Imagem_**

Um link faz a ligação entre documentos, estando eles na mesma página ou em domínios diferentes.
Para criar um link, usaremos as tags `<a></a>` e o atributo `href=""`.

Ex:    `<p>Acesse o site da Digital College <a href="https://digitalcollege.com.br">clicando aqui!</a></p>`

Esse é o resultado:

 <p>Acesse o site da Digital College <a href="https://digitalcollege.com.br">clicando aqui!</a></p>


Para adicionar uma imagem ao documento, usaremos a tag `<img>` com o atributo `src=""`. Dentro desse atriubuto deve ser digitado o local onde a imagem se encontra. Também podemos usar o atributo `alt` para definir um título ou texto para a imagem.

Ex:  `<img src="https://static.wikia.nocookie.net/naruto/images/9/93/O_Time_7.png/revision/latest?cb=20131209191745&path-prefix=pt-br" alt="Imagem time7">`

Resultado:


<img src="https://static.wikia.nocookie.net/naruto/images/9/93/O_Time_7.png/revision/latest?cb=20131209191745&path-prefix=pt-br" alt="Imagem time7">






## Estrutura básica de um documento HTML



![Image](https://user-images.githubusercontent.com/112489109/192039157-7b61cd13-b58f-41f4-8f41-fd9d58a98aba.png)


|  **Tag** | **Descrição**  |
| ------- | -------- |
| `<!DOCTYPE html>`  | Informa ao navegador a versão do HTML utilizada no arquivo    |
| `<html lang=" ">`   | Define o idioma principal da sua página    |
| `<head>`   | Contém  _metadados_  sobre o documento. Não são exibidos na página   |
| `<meta>`   | As tags _meta_ definem as informações de _metadados_ |
| `<meta charset>`   | Define a codificação que será usada na página   |
| `<title>`   | Adiciona um _título_ ao documento  |
| `<body>`   | Conteúdo da página. Os dados informados aqui ficarão visíveis para o usuário final  |



## Vídeo



https://user-images.githubusercontent.com/112489109/192167258-607e3cb7-6cdf-4e8b-a9bc-58df1bc5d77b.mp4


</div>
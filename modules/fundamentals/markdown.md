# **Markdown**
O markdown é uma linguagem de marcação criada em 2004 pelo UI designer John Gruber, em colaboração com o programador [Aaron Swartz](http://www.aaronsw.com/) — criador do [Reddit](https://www.reddit.com/).

Ela foi criada para ser uma forma fácil de escrever documentos estruturados, com base em convenções para formatações de e-mail, por exemplo, e permite que o texto seja convertido para HTML ou outros formatos.

O markdown foi desenvolvido, segundo Gruber, para ser o mais legível possível e para ter um design  que, ao ser publicado da forma como foi escrito, pareça não ter sido marcado com tags de formatação.

> *The overriding design goal for Markdown’s formatting syntax is to make it as readable as possible. The idea is that a Markdown-formatted document should be publishable as-is, as plain text, without looking like it’s been marked up with tags or formatting instructions.* - [*John Gruber em Daring Fireball*](https://daringfireball.net/projects/markdown/).

## **Variações**
A sintaxe original de Gruber não traz todas as possibilidades de implementação que existem hoje para a linguagem markdown. Isso porque, com o passar do tempo, outras pessoas e organizações foram escrevendo as próprias variações da linguagem e inserindo recursos ausentes na versão inicial. 

Foi percebida também certa ambiguidade na sintaxe. Para corrigir isso, surgiu a [CommonMark](https://commonmark.org/), que propõe "uma especificação de sintaxe padrão e inequívoca para o Markdown".

O GitHub também lançou, em 2017, a especificação formal do [GitHub Flavored Markdown (GFM)](https://github.github.com/gfm/), que tem como base o CommonMark. O GFM combina a sintaxe do markdown com recursos de escrita exclusivos. Com ele, os usuários da plataforma podem, por exemplo, interagir com outras pessoas em pull requests e issues utilizando recursos como @mentions.

Atualmente, diversos sites utilizados no dia a dia têm suporte para a linguagem markdown, como o [Trello](https://trello.com/) e o [Notion](https://www.notion.so/).

## **Sintaxe**

A seguir, serão mostrados exemplos de algumas funcionalidades importantes para a formatação de um arquivo em `.mkd`.

### 1. Cabeçalho
```
# h1
## h2
### h3
#### h4
##### h5
###### h6

```

> # h1
> ## h2
> ### h3
> #### h4
> ##### h5
> ###### h6

### 2. Destaques
```
Para deixar uma palavra ou um trecho em itálico, coloque *entre asteríscos* ou _entre símbolos underline_.

Para negrito, deve vir **entre dois asteríscos** ou __com dois símbolos underline de cada lado__.

É possível combinar **_itálico com negrito_**.

Também dá para ~~riscar~~ uma palavra ou ~~um trecho~~ com dois tils.
```

Para deixar uma palavra ou um trecho em itálico, coloque *entre asteríscos* ou _entre símbolos underline_.

Para negrito, deve vir **entre dois asteríscos** ou __com dois símbolos underline de cada lado__.

É possível combinar **_itálico com negrito_**.

Também dá para ~~riscar~~ uma palavra ou ~~um trecho~~ com dois tils.

### 3. Quebra de linha

```
Para escrever mais de um parágrafo, não adianta
dar apenas um enter. É preciso dar enter

duas vezes para conseguir a quebra de linha.
```

Para escrever mais de um parágrafo, não adianta
dar apenas um enter. É preciso dar enter

duas vezes para conseguir a quebra de linha.

### 4. Citação
```
Em markdown, para fazer uma citação, se utiliza o símbolo ">" antes da
frase, como no exemplo a seguir:

> "Ser ou não ser, eis a questão."
```

Em markdown, para fazer uma citação, se utiliza o símbolo ">" antes da frase, como no exemplo a seguir:

> "Ser ou não ser, eis a questão."

### 5. Listas

```
1. Uma lista pode ser ordenada
2. Aqui temos o segundo item dela
    2.1 Que também pode ter uma sub-lista ordenada 
1. Mesmo que o número da lista não siga a ordem real, no resultado final a ordem vai ser reconhecida. Veja o preview
    * A sub-lista também pode ser não-ordenada

    Olha só! Podemos ter um parágrafo identado dentro de um item de listas. Pode ser uma frase pequena, mas também pode ser um textinho maior, depende do que você precisa escrever.

* As listas não ordenadas podem ser criadas utilizando um asterísco no lugar do número
- Ou um sinal negativo
+ Ou ainda um positivo

```

1. Uma lista pode ser ordenada
2. Aqui temos o segundo item dela
    2.1 Que também pode ter uma sub-lista ordenada 
1. Mesmo que o número da lista não siga a ordem real, no resultado final a ordem vai ser reconhecida. Veja o preview
    * A sub-lista também pode ser não-ordenada

    Olha só! Podemos ter um parágrafo identado dentro de um item de listas. Pode ser uma frase pequena, mas também pode ser um textinho maior, depende do que você precisa escrever.

* As listas não ordenadas podem ser criadas utilizando um asterísco no lugar do número
- Ou um sinal negativo
+ Ou ainda um positivo

### 6. Link

```
Para inserir um [link de um site](https://linkdosite.com) se coloca entre 
colchetes o nome do site ou o trecho do texto em que o link irá aparecer e
entre parenteses o link em si.
```

Para inserir um [link de um site](https://linkdosite.com) se coloca entre colchetes o nome do site ou o trecho do texto em que o link irá aparecer e entre parenteses o link em si.

### 7. Imagem

```
Para inserir uma imagem, se utiliza a seguinte sintaxe: 

![texto alternativo para melhorar a acessibilidade](endereço da imagem
na internet ou no repositório)

*Dica! Ao fazer o upload de uma imagem criando no respectivo ícone, o editor
HackMD, utilizado para construir este documento, cria automaticamente um
endereço para a imagem.*

Como no exemplo a seguir:

![Foto de um gato branco de olhos azuis encostado em uma janela de
vidro](https://i.imgur.com/HFhJIIW.jpg)

```

Para inserir uma imagem, se utiliza a seguinte sintaxe: 

![texto alternativo para melhorar a acessibilidade](endereço da imagem na internet ou no repositório)

*Dica! Ao fazer o upload de uma imagem criando no respectivo ícone, o editor HackMD, utilizado para construir este documento, cria automaticamente um endereço para a imagem.*

Como no exemplo a seguir:

![Foto do Dante, meu gato branco de olhos azuis, sem raça definida. Ele está encostado em uma janela de vidro](https://i.imgur.com/HFhJIIW.jpg)

### 8. Tabelas

```
Para inserir tabelas, deve-se utilizar os seguints elementos:

- Barra vertical (|)
- Sinal de menos (-)
- Dois pontos (:) - opcional

Entre o cabeçalho e a primeira linha da tabela, deve ter ao menos três sinais
de menos (-) e, caso se deseje modificar a justificação do texto da coluna,
dois pontos (:) ou no início e no final, ou apenas como último caractere.

|      Coluna 1      |      Coluna 2      |      Coluna 3      |
| ------------------ | :----------------: | -----------------: |
| Texto coluna 1     | Texto coluna 2     | Texto coluna 3     |

Para funcionar, a tabela não precisa estar toda alinhada, veja:

| Coluna 1 | Coluna 2 | Coluna 3 |
| -------- | :--------: | --------: |
| Texto coluna 1     | Texto coluna 2     | Texto coluna 3     |

```

Para inserir tabelas, deve-se utilizar os seguints elementos:

- Barra vertical (|)
- Sinal de menos (-)
- Dois pontos (:) - opcional

Entre o cabeçalho e a primeira linha da tabela, deve ter ao menos três sinais
de menos (-) e, caso se deseje modificar a justificação do texto da coluna,
dois pontos (:) ou no início e no final, ou apenas como último caractere.

|      Coluna 1      |      Coluna 2      |      Coluna 3      |
| ------------------ | :----------------: | -----------------: |
| Texto coluna 1     | Texto coluna 2     | Texto coluna 3     |

Olha só como a segunda tabela lá de cima também funciona:

| Coluna 1 | Coluna 2 | Coluna 3 |
| -------- | :--------: | --------: |
| Texto coluna 1     | Texto coluna 2     | Texto coluna 3     |

### 9. Blocos de código e destaques

```
Você já percebeu que sempre que queremos mostrar como funciona a sintaxe,
sem que ela seja lida e executada pelo editor, nós usamos esse retângulo
cinza, certo? Bem, ele é um bloco de código. Nos casos anteriores, não
especificamos uma linguagem, mas nele nós podemos demonstrar,
por exemplo, como funciona um trecho de código em uma linguagem específica.

Para isso, temos que utilizar três acentos graves (```) para iniciar o bloco
e outros três para fechar. Para especificar a linguagem, colocamos o
nome dela logo após abrir o bloco de código. Assim:

    ```python
    
    ```
Depois do nome da linguagem, é só escrever o código que ele será reconhecido.

```

Vamos iniciar a seguir um bloco que reconheça a linguagem python:

```python
t = "texto"
print(t)
```

```
Já quando você utiliza o acento grave apenas uma vez (``) no início e no final de uma `palavra`  ou de `uma expressão`, você vai dar um destaque para ela.
```

Já quando você utiliza o acento grave apenas uma vez (``) no início e no final de uma `palavra`  ou de `uma expressão`, você vai dar um destaque para ela.

## **Dicas**
### **1. Tutorial: aprenda markdown em 60 segundos**

Tutorial da Commonmark que ensina conceitos sobre da linguagem markdown com exemplos. Com ele, é possível aprender sobre parágrafos, cabeçalho, listas, links e imagens, por exemplo. [Clique aqui para conferir o tutorial](https://commonmark.org/help/tutorial/).

### **2. Editores de Markdown**

Existem diversas opções de editores de markdown disponíveis na internet e a melhor delas vai ser a que atender à sua necessidade em determinado momento.

Há, por exemplo, editores online que podem ser utilizados sem a precisar de criar uma conta; outros em que se pode fazer edições colaborativas — como no *Google Docs* — e programas que necessitam de instalação no computador.

Confira algumas opções e escolha a que melhor se adequa ao seu projeto.

[![Print da página do editor online de markdown dillinger.io](https://i.imgur.com/NpwlpTL.png)](https://dillinger.io/)

1. [**Dillinger.io**](https://dillinger.io/)
Essa é uma das opções de ferramenta que permitem a edição online de texto em formato markdown. Com ela, é possível conectar-se à conta do Github, do Medium, do Google Drive, entre outras, para importar e exportar arquivos. Após finalizar a edição do texto, é possível exportá-lo em formatos HTML, HTML "com estilo", markdown ou PDF.

[![Página do programa de edição de markdown caret.io](https://i.imgur.com/WvfDaOP.png)](https://caret.io/)

2. [**Caret.io**](https://caret.io/)
Com interface minimalista, o [Caret.io](https://caret.io/) está disponível para Mac, Windows e Linux. Ele tem diversos recursos, como autocompletar, múltiplos cursores para edições simultâneas e ajuda com tabelas, listas, html, etc.

[![Print de página da ferramenta hackmd.io](https://i.imgur.com/Jq7AgxR.png)](https://hackmd.io/)

3. [**Hackmd.io**]([hackmd.io](https://hackmd.io/))
É um editor colaborativo em tempo real e gratuito. Para utilizar, basta criar uma conta com o login do Twitter, do  Facebook, do  Google+, do GitHub ou do Dropbox. Como ocorre em arquivos do Google Drive (como o *Google Docs* ou o *Google Sheets*), é possível que mais de uma pessoa faça alterações no arquivo ao mesmo tempo. Ótimo para trabalhos em equipe, não é mesmo?

### **3. Praticidade ao criar tabelas**
Às vezes, preencher cada campo de uma tabela diretamente no markdown pode ser confuso. Se esse for o seu caso, essa ferramenta pode ajudar a facilitar esse trabalho. 

[![Print da página da ferramenta de geração e edição de tabelas em formato markdown](https://i.imgur.com/39xJNG5.png)](https://tableconvert.com/markdown-generator)

Com a [Markdown Table Editor and Generator](https://tableconvert.com/markdown-generator), basta preencher os campos do editor de tabela que, em seguida, será gerada uma tabela em formato markdown. A ferramenta permite escolher o alinhamento do texto e determinar qual linha ou coluna deve ficar em negrito.

## **Fontes**
* [Daring Fireball, By John Gruber](https://daringfireball.net/projects/markdown/)
* [GitHub Flavored Markdown Spec](https://github.github.com/gfm/#introduction)
* [Introdução ao Markdown - Instituto de Física / Universidade Federal do Rio Grande do Sul](https://www.if.ufrgs.br/fis01069/sintaxemarkdown.html#cabe%C3%A7alhos)
* [Wikipedia - Markdown](https://pt.wikipedia.org/wiki/Markdown)
# Introdução 

## Host 
![Computador copiando informações do host](https://media0.giphy.com/media/9igGG6KxpY0eY0Sr5u/giphy.gif?cid=ecf05e47iqjttkz0cm3y0eozvxohdp11woa6wqtg0lf1v6ly&rid=giphy.gif&ct=g)

Um conceito importante para entender todos os campos da barra de enderenço é que todos os sites estão hospedados em um servidor que chamamos de *web host*. Esse servidor pode ser simplesmente um notebook conectado a internet como também um aglomerado gigante de equipamentos em um empresa. Esses servidores armazenam arquivos em formatos como html, css, javascript, banco de dados entre outros e através de um endereço que você acessa pelo seu browser conseguimos chegar nesses arquivos e ver a página ser exibida. 

## Location 
Uma API interessante para analisar todos esses atributos é o location. Com o devtools aberto podemos descobrir várias informações da página, como o nome do host, por exemplo. Como ilustra a figura abaixo: 
![screenshotDoLocation](https://raw.githubusercontent.com/Deborahhm/Digital-College/main/barraDeEnderecos/images/Screenshot%20from%202022-09-25%2019-39-40.png)

Entre os atributos do location, teremos: 
- Location.ancestorOrigins
	Uma lista da DOM da página 
- Location.href
	Retorna uma string com toda a url completa 
- Location.protocol
	Retorna o protocolo da página 
- Location.host
	Retorna o nome do servidor host 
- Location.hostname
	Retorna o domínio do site 
- Location.port
	Retorna a porta do site
- Location.pathname
	Retorna o caminho/pasta onde o arquivo se encontra 
# Barra de endereços 

A barra de endereço especifica o local na internet onde o arquivo/página web está localizado e essa é constituída de vários elementos como veremos a seguir na imagem. 

![Barra de Ferramentas atributos](https://raw.githubusercontent.com/Deborahhm/Digital-College/main/barraDeEnderecos/images/URL.drawio.png)
	
## Protocolo 

https:// e http:// Aparecem na parte inicial do endereço. O protocolo http *Hypertext Transfer Protocol* Foi desenvolvido para permitir a comunicação com um servidor web e utilizava a príncipio apenas o método *GET* para pegar as informações. Isso fez com que quando surgiu a necessidade de não só pegar informações do servidor como também de dar informações para o servidor *POST* o método http fosse considerado não seguro, já que o dados são transferido por texto. Já o método https:// faz uso de criptografia, isso é a codificação da mensagem, para encaminhar os dados para o servidor. Para verificar o protocolo podemos utilizar location.protocol

## Subdomínio

Desde os primórdios da internet os sites utilizavam www. na frente dos seus dominios. A sigla significa *world wide web*. muitos nomes de servidores começavam com *www* por serem servidores de web. Assim com os servidores de FTP utilizavam *ftp* , e servidores de notícia usenet utilizavam *nntp*. Os nomes dos servidores apareciam em DNS antes do nome de domínio como *www.exemplo.com*. Porém o www não é obrigatório e muitos sites nem o usam como o stackoverflow e o github. Atualmente a utilidade do www é questionada mas ainda há usuários que defendem seu uso.

## Domínio 
Por padrão o protocolo de endereços na internet é o IP, *internet protocol*, mas é bem mais fácil para os usuários lembrar de nome, como google.com do que de um número como 142.251.134.110(google). Por isso foi criado o DNS *Domain Name System* que contém o registro de todos os nomes de domínio na internet. Então quando você tenta entrar em um site você indica o nome dele e o servidor retorna o ip para que seu navegador consiga se conectar no site e assim acessar os arquivos 
![DNSserver](https://pessoatech.com.br/wp-content/uploads/2020/02/DNS-Server.png)
Para verificar o dominio podemos utilizar location.host

## Porta
A porta não é comum em páginas mais pode especificar um ponto lógico para fazer conexão com o servidor. Por padronização o protocolo http usa a porta 80 e https a porta 443. Para ver a porta que a página utiliza podemos utilizar o location.port

## Path 

No host os arquivos também são organizados em pastas. O path diz exatamente o caminho das pastas do arquivo. Para ver o caminho do arquivo podemos utilizar o location.path

## Query 

A string "?" marca o início da query na url. Para verificar a query podemos utilizar location.search. Após a query. Por exemplo:
![GITHUBLANGUAGES](https://github-readme-stats.vercel.app/api/top-langs/?username=Deborahhm&bg_color=30,76B4C5,12353F&title_color=fff&text_color=fff)
Essa é uma imagem que reune as linguagens mais utilizadas no github pelo meu usuário. Como a mesma api constrói a imagem e a imagem é personalizavel de acordo com o perfil e preferência do usuário os valores são passados atráves da URL. E o endereço da imagem é 
`https://github-readme-stats.vercel.app/api/top-langs/?username=Deborahhm&bg_color=30,76B4C5,12353F&title_color=fff&text_color=fff`

Vemos algumas informações depois da interrogação como por exemplo 
- username = Deborahhm 
	Nome de usuário github para poder resgatar as informações do usuário.
- bg_color = bg_color=30,76B4C5,12353F. 
	Como a imagem é um gradiente, essas são as 3 cores do plano de fundo 
- title_color = fff. 
	A cor do título da imagem. Nesse caso a cor é branca 
- text_color. 
	A cor do texto da imagem. Novamente branco. 
<a href="https://drive.google.com/file/d/1ab552qfAf3TSs9VobjoSoR1b6N3OG16o/view?usp=sharing">Link Do vídeo aqui</a>
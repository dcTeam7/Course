# Memória Cache e Cookies


## Cache

> **A memória cache é um modo bastante prático de dar mais velocidade a execução das tarefas, pois armazena dados de modo temporário para um acesso direto do processador (CPU).**

_A memória cache consegue armazenar as informações de modo mais superficial, não sendo necessário que o processador realize uma busca profunda a cada comando simples durante uma tarefa. Ela executa funções e níveis bastante importantes em um dispositivo._


![Image](https://user-images.githubusercontent.com/112489075/192279821-1debd49d-a2bd-47de-a90e-18582d247cec.jpg)


## O que é a memória cache? 

A memória cache é um tipo de memória de acesso rápido, que facilita o processo de acesso a todos os dados do dispositivo. A velocidade que um comando é executado ou que uma atividade é concluída depende da rapidez que o processador consegue captar, dentre todos arquivos, as informações mais necessárias no momento.

Então, para facilitar essa busca, existe a memória cache, que consegue armazenar as informações de modo mais superficial, não sendo necessário que o processador realize uma busca profunda a cada comando simples durante uma tarefa.
Para facilitar o entendimento preciso discorrer entre memória **RAM** e memória **Cache**, elas estão intrínsecas mas com funções diferentes. 


![imagem](https://user-images.githubusercontent.com/112489075/192280652-ae7c6108-59c5-4d45-a717-4da0376fd52a.gif)

## Diferença entre memória RAM e memória CACHE


![Image](https://user-images.githubusercontent.com/112489075/192282906-c38f9345-0d82-426b-a9fb-89dace19be92.png)



A memória **RAM** é a memória temporária de um dispositivo, que armazena dados por um período necessário para a realização de uma tarefa, antes de salvar o arquivo na memória permanente.

E a memória **CACHE** também é temporária, possuindo funções similares à memória RAM só que em áreas de acesso mais rápido. Mas para se ter uma melhor compreensão, é preciso exemplificar o processo.

É possível compreender esse processo imaginando todas as informações escritas em um caderno simples de papel. Para se obter essas informações no caderno deve-se extrair uma árvore, que está em uma floresta.

A floresta é onde ficam as informações mais profundas, ou seja, a memória permanente do dispositivo. Já uma árvore é um método mais rápido de acesso, pois pode ser de uma espécie em específica, isto é, a memória RAM.

Já o caderno possui as próprias informações em si, sendo preciso apenas folhear para encontrar os dados desejados.

Nesse caso, sempre que o processador fosse procurar uma simples informação, ele teria que procurar em toda a floresta, por isso, reduzir essa procura para uma árvore em específico torna tudo mais rápido, que é a memória **RAM**.

E a memória cache é um método ainda mais instantâneo de encontrar essas informações. Assim, o processador não precisa vasculhar toda a floresta, nem mesmo uma árvore, pois tudo pode ser visualizado rapidamente no caderno. Com isso, há grandes diferenças também em relação à capacidade de armazenamento de cada uma dessas memórias.

## Quais os níveis da memória cache?

>**A memória cache busca dar velocidade de acesso aos dados, mas mesmo dentro dessa memória, existem ainda certos níveis, que podem variar na função e também na velocidade, são elas: memória cache L1, memória cache L2 e memória cache L3.**

![Image](https://user-images.githubusercontent.com/112489075/192291174-2af2e265-e845-4555-a4d4-3769b7beb2d0.png)

### 1. memória cache L1
O cache L1 ou cache nível 1 é uma espécie de memória rápida e, como visto, bastante curta, que se constitui diretamente na CPU. Das três divisões, essa é a principal, pois permite o acesso mais rápido de todas, e é onde ficam as informações de uso mais frequente e com maior importância, e se integra ao próprio dispositivo.###

### 2. memória cache L2
O cache L2, conhecido como cache de nível 2 guarda os últimos dados que foram acessados. Sua função inicial é a de tornar o acesso aos dados mais rápido, pois consegue armazenar essas informações que foram utilizadas nos últimos momentos.

Ele não é tão rápido quanto a memória cache L1, que é a principal, mas ocupa um papel importante nos processos, sendo até mesmo com muito mais capacidade de armazenamento.

E como são interligados, as informações que são pedidas na memória cache L2 são transmitidas para a memória cache L1, podendo ou não ainda ficarem no L2.

### 3. memória cache L3
Há uma pequena hierarquia na ordem da velocidade, onde o L1 é o mais rápido, o L2 é mediano, e o L3 é o mais lento dos três. Mas mesmo assim, a memória cache L3 é bem mais rápida que a verdadeira memória do dispositivo. Sua integração é diretamente com a própria placa-mãe, sendo o encarregado de repassar os dados para a memória cache L2.

## Quais os princípios da memória cache?

>**As funções executadas pela memória cache são baseadas em dois princípios básicos, que tornam tudo mais dinâmico e rápido. São os princípios de *localidade espacial e o de localidade temporal*, que conseguem até mesmo prever os dados seguintes que seriam consultados na memória RAM.**

### 1. princípio da localidade espacial

O princípio da localidade espacial é justamente o que consegue adiantar os futuros dados consultados na memória RAM, e é bastante simples. Quando um dispositivo inicia uma aplicação, o processador vai primeiramente na memória secundária, que é a permanente. Após essa primeira consulta, todos os dados referentes à aplicação são transmitidos para a memória RAM, e isso por si só já é baseado no princípio da localidade espacial.

Quando o processador realiza uma procura na memória RAM por um dado, a memória cache copia os dados seguintes, assim  o processador não precisa ir mais na principal, pois já possui tudo o que precisa perto de si.


### 2. princípio da localidade temporal

O princípio da localidade temporal é relacionado ao próprio dado buscado, pois ela possui grandes chances de ser usado mais vezes. Então quando o processador realiza uma busca na memória RAM por um dado em específico, esse dado é copiado para a memória cache, pois possui grandes chances de um uso recorrente.

Assim, os princípios de localidade espacial e temporal são totalmente relacionados, pois são relativos a todo o bloco de dados que está sendo usado. Nesse caso, a localidade temporal indica a necessidade da cópia do dado que foi buscado, e a localidade espacial indica a provável necessidade da cópia dos dados seguintes, relativos ao primeiro dado.

## Vale a pena limpar a memória cache?


Apesar de ser temporária, há muitas utilizações da memória cache, e ela é associada também a aplicativos, navegadores, etc. Nesses casos, essa memória é relacionada a pequenas informações que são guardadas e que ajudam no carregamento dessas aplicações em acessos futuros. Geralmente os aparelhos celulares possuem um aplicativo de varredura, e vez ou outra ele pede uma limpeza. vejam no vídeo abaixo que gravei da tela do meu celular essa demonstração de limpeza cache.

https://user-images.githubusercontent.com/112489075/192288589-e1b16528-8235-4f1a-a613-e204f48b8016.mp4

Então o **Whatsapp**, o **Instagram**, o **Facebook**, e os navegadores usam um tipo de memória cache que facilita a sua abertura sempre que são iniciados. Apesar de ser temporária, a memória cache de um navegador pode durar um pouco mais de tempo, e pode ser observado sempre que se entra em um site com muita frequência.

Nesses casos, eles são abertos com mais facilidade, pois já há dados específicos armazenados na memória cache, de outras vezes que ele foi utilizado.

Principalmente em smartphones, que possuem uma capacidade de armazenamento bem menor que os computadores, a disputa por espaço é relativamente grande, pois são muitos arquivos e aplicativos disputando.

E a memória cache pode sim realmente ocupar uma pequena parte desse espaço, uma vez que pode armazenar os dados de cada aplicação. Muitas pessoas se perguntam dessa forma, se é possível e se vale a pena limpar a memória cache, e as respostas para essas perguntas são bastante simples.

Quanto à possibilidade de limpar a memória cache, a resposta é sim. Para isso, basta ir nas configurações do celular, ir em aplicativos, selecionar o app, e clicar em limpar cache.

Com isso, na próxima vez que o app for iniciado, ele levará um pouco mais de tempo para carregar. E sobre valer a pena ou não, isso vai depender de muitos fatores. Primeiramente, os dados da memória cache sempre serão armazenados, ou seja, sempre que um aplicativo for utilizado, serão guardadas as informações principais do carregamento.

Então, apesar da limpeza liberar um pouco de espaço, nos acessos futuros, ele será pouco a pouco preenchido novamente. Com isso, dependendo do quanto essa memória esteja interferindo na capacidade do dispositivo, pode até valer a pena realizar sua limpeza, mas eles serão recuperados, consumindo um pouco mais de dados e energia do aparelho.

Dessa forma, caso a limpeza seja realizada, é interessante que o próximo acesso seja realizado sem usar os dados móveis, para que não haja um consumo desnecessário.

## Diferença entre limpar CACHE e limpar DADOS

Quem já tentou limpar a memória cache do dispositivo já se deparou também com a opção de limpar os dados do aplicativo. Mas o que realmente isso significa? Como visto, a memória cache serve para armazenar alguns dados relativos ao carregamento de uma app ou navegador.

Então o primeiro acesso a um site ou app é bem mais demorado que os outros acessos, pois ainda não há nada relacionado a ele na memória do dispositivo.

Porém, em consultas futuras, eles carregam de modo bem mais rápido, pois já há algumas informações salvas. Os dados, por outro lado, são relativos a outras informações mais importantes, que ficam armazenadas nessas aplicações. São dados como o login e a senha de um aplicativo.

Quando salvas, não há mais a necessidade de inserir a senha de um aplicativo todas as vezes que ele é iniciado, isso porque seus dados já estão salvos.

Limpar os dados significa, desse modo, abrir mão dessas informações, então em um futuro acesso, será preciso realizar um novo login na aplicação.

Dessa forma, limpar o cache é apagar algumas informações de carregamento, já apagar os dados é como desinstalar e reinstalar um app novamente, pois ele será iniciado sem nenhuma informação salva.


# O que são cookies?



![Image](https://user-images.githubusercontent.com/112489075/192295222-863759d6-9fd7-45b1-b810-e802d28d1e71.jpg)



Os cookies são arquivos que contêm pequenos fragmentos de dados — como um nome de usuário e uma senha — que são trocados entre o computador de um usuário e um servidor Web para identificar usuários específicos e melhorar sua experiência de navegação.

Por exemplo, os cookies permitem que os sites reconheçam os usuários e lembrem de suas informações e preferências de login individuais, como notícias esportivas em vez de política.

Os sites de compras usam cookies para rastrear itens que os usuários visualizaram anteriormente, permitindo sugerir outros produtos que possam ser de interesse do usuário e manter itens no carrinho de compras enquanto eles continuam comprando.

Os cookies são criados quando os usuários visitam um site novo, e o servidor Web envia um breve fluxo de informações para os navegadores deles. Esse cookie só é enviado quando o servidor deseja que o navegador da Web armazene o cookie. Nesse caso, ele lembrará de string name=value e o enviará de volta ao servidor com cada pedido posterior.

Se, no futuro, o usuário voltar a esse site, o navegador da Web retornará esses dados ao servidor da Web sob a forma de um cookie.

O nome "cookie" vem de "cookies mágicos", inventado pelo programador de navegador da Web Lou Montulli. Os termos referem-se a pacotes de informações que são enviados e recebidos sem alterações. A analogia com o biscoito assado crocante é uma coincidência, embora apropriada.

## Há vários tipos de cookies



![Image](https://user-images.githubusercontent.com/112489075/192295944-f129abdb-8339-43da-b449-f81c15d8248e.png)



Com algumas variações, há dois tipos de cookies no mundo virtual: de sessão e persistente. Os cookies de sessão são usados apenas ao navegar em um site. Eles são armazenados na memória RAM e nunca são gravados no disco rígido.

Quando a sessão termina, os cookies da sessão são excluídos automaticamente. Eles também ajudam no funcionamento do botão "Voltar" ou dos plug-ins de anonimato de terceiros. Esses plug-ins são projetados para que navegadores específicos funcionem e ajudam a manter a privacidade do usuário.

Os cookies persistentes se alojam em um computador indefinidamente, embora muitos incluam uma data de expiração e sejam removidos automaticamente nessa data.

## Os cookies persistentes são usadospara dois propósitos principais:

>**Autenticação: esses cookies controlam se o usuário está conectado e qual conta ele está usando. Eles também simplificam as informações de login para que os usuários não tenham de lembrar das senhas do site.**

>**Rastreamento: esses cookies acompanham as várias visitas ao mesmo site ao longo do tempo. Alguns lojistas on-line, por exemplo, usam cookies para controlar as visitas de usuários específicos, incluindo as páginas e produtos vistos. As informações que eles obtêm permitem sugerir outros itens que possam interessar aos visitantes. Gradualmente, é criado um perfil com base no histórico de navegação do usuário nesse site.**

## Cuidado com cookies de terceiros


![Image](https://user-images.githubusercontent.com/112489075/192296833-74c65863-fd9d-4dc7-808e-15228d72a324.png)


Os cookies de terceiros são mais problemáticos. Eles são gerados por sites que são diferentes das páginas da Web em que os usuários estão navegando no momento, geralmente porque estão vinculados a anúncios contidos nessas páginas.

*__A visita a um site com 10 anúncios pode gerar 10 cookies, mesmo que o usuário nunca clique nesses anúncios.__*

Os cookies de terceiros permitem que os anunciantes ou as empresas de análise acompanhem o histórico de navegação de um indivíduo em toda a Web, nos sites que contêm seus anúncios. Consequentemente, o anunciante pode determinar que um usuário inicialmente procurou roupas de corrida em uma loja específica antes de conferir um determinado site de artigos esportivos e, em seguida, uma certa loja de roupas esportivas on-line.

Alguns cookies de terceiros podem ser zumbis. Os cookies zumbis ficam instalados permanentemente nos computadores dos usuários, mesmo quando optam por não instalar cookies. Eles também reaparecem depois de terem sido excluídos. Quando os cookies zumbis surgiram, eles foram criados a partir de dados armazenados no compartimento de armazenamento do Adobe Flash. Às vezes, eles são chamados de cookies de flash e são extremamente difíceis de remover.

Assim como outros cookies de terceiros, os cookies zumbis podem ser usados por empresas de análise da Web para rastrear históricos de navegação de cada indivíduo. Os sites também podem usá-los para proibir usuários específicos.

## Os cookies em si não são prejudiciais


Como os dados nos cookies não mudam, os cookies em si não são prejudiciais. Eles não podem infectar computadores com vírus ou outros malwares, embora alguns ataques cibernéticos possam sequestrar cookies e, portanto, sessões de navegação. O perigo reside na capacidade deles de rastrear os históricos de navegação dos indivíduos. Esse tipo de comportamento "Big Brother" pode representar um problema de segurança.

## Permitir ou remover cookies



![Image](https://user-images.githubusercontent.com/112489075/192297306-70b47bf1-7bb1-4568-9e29-53f7792ad957.png)



>**Para simplificar a navegação, os usuários podem encontrar a seção de cookies,geralmente em Configurações > Privacidade, e clicar nas caixas para permitir cookies. Às vezes, a opção é: "Permitir dados locais".**

A remoção de cookies comuns é fácil, mas pode dificultar a navegação em certos sites. Sem os cookies, os usuários podem ter de inserir seus dados novamente a cada visita. Os vários navegadores armazenam cookies em locais diferentes, mas a seção Configurações > Privacidade — às vezes listada em Ferramentas > Opções da Internet ou Avançado — é o mais comum. Estão disponíveis opções para gerenciar ou remover cookies.

Antes de remover os cookies, avalie a facilidade de uso esperada de um site da Web que usa cookies. Na maioria dos casos, os cookies melhoram a experiência na Web, mas devem ser tratados com cuidado.

Segue o vídeo sobre o tema.

https://photos.app.goo.gl/yKqgbZ3kXcTYeeL99
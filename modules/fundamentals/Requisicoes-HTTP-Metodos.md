# O que é HTTP?
Afinal, o que é protocolo HTTP? A abreviatura de “Hypertext Transfer Protocol” descreve um protocolo sem estado com o qual os dados podem ser transmitidos em uma rede IP. A aplicação mais importante é a transferência de páginas da Internet e dados entre um servidor web e um navegador. No entanto, ele não está restrito a sites, sendo usado para aplicativos.<p>

Um exemplo dessa relação é quando utilizamos aplicativos de streaming, como a Netflix. O catálogo de filmes não está armazenado no nosso dispositivo, mas sim em um servidor, o papel que o site e o aplicativo fazem é buscar esses filmes e exibir para o usuário por meio dos métodos HTTP.

# Uma visão geral do HTTP<p>

<div>

<img src="https://media.discordapp.net/attachments/1019607462015414372/1023988692710338610/unknown.png?width=641&height=427" height="230" width="400" align="center">
<br>
<br>

</div>

<html>
<p>


 HTTP é um protocolo ( protocol ) que permite a manutenção de recursos, como documentos HTML. É uma base de qualquer troca de dados a cliente Web e um protocolo, o que significa que as requisições são iniciadas pelo destinatário, geralmente um navegador da Web. Um documento completo é reconstruído a partir de diferentes subdocumentos obtidos, como por exemplo texto, descrição do layout, imagens, vídeos, scripts e muito mais.
<br>

# História do HTTP
Esse protocolo foi criado por Tim Bernes-Lee, juntamente com sua equipe da World Wide Web (WWW). Ele surgiu da necessidade de padronizar e facilitar a transmissão de dados através de clientes e servidores. A primeira versão do protocolo foi implementada em 1990, e era utilizado apenas para transmitir somente texto ASCII e possuía somente o método GET. Em 1992, a demanda por transmitir outros tipos de arquivos além de texto surgiu e foram criados mais dois métodos: POST e HEAD, que possibilitaram também o transporte de outros formatos de arquivos.<p>


Atualmente, a grande maioria dos softwares utilizam-se uma API REST — É uma interface de programação de aplicações que, quase sempre, utiliza os métodos HTTP para realizar sua tarefa, que é funcionar como um mediador entre o cliente e o servidor, interpretando as requisições e exibindo as respostas necessárias — E com isso, os dados estarão alocados em um servidor independente, essa ação de manter os dados fora do equipamento do usuário possibilitará o acesso multiplataforma, isso é: acessar e modificar os mesmos dados através do seu celular e também pelo seu computador.

# Mas como isso tudo funciona?

Existem dois conceitos fundamentais que englobam e sustentam o funcionamento do protocolo: requisição e resposta:
<div>

<img src="https://oraculoti.com.br/wp-content/uploads/2019/06/oraculo-ti-servidor-web-requisicao-resposta.jpg"
height="230" width=" 400" align="center"><br>

##### <u> Requisição </u>
Na requisição, é onde será feito o envio e/ou a requisição de dados para o servidor. Por exemplo, enviar o login e a senha de um usuário e o servidor retornará através da Resposta se aquele usuário é válido ou não. Ou então, outro exemplo bastante recorrente é o streaming de arquivos.<br>

##### <u>Resposta</u>
A resposta do servidor servirá apenas para orientar a camada de cliente (frontend). Sempre que uma requisição é feita, a resposta é separada em duas partes, uma é composta pelo Http Status Code, que são códigos para definir o sucesso ou a falha de uma operação e a outra pelo corpo da resposta, que contém os arquivos e dados solicitados. Por exemplo, caso você esteja executando um GET para uma lista de usuários, o corpo da requisição retornará essa lista em formato JSON, ou quando é o caso de streaming de vídeos, como é a Netflix, o software cliente receberá como resposta o próprio arquivo do filme em um formato mp4 já pronto para ser interpretado pelo navegador ou pelo aplicativo. Porém, como irei explicar mais a frente, nem sempre esse corpo da requisição é necessário na resposta.
<br>
 
</div> 
<p>





# Métodos de requisição HTTP<br>
<br>

O protocolo HTTP define um conjunto de métodos de requisição responsáveis por indicar a ação a ser executada para um dado recurso. Embora esses métodos possam ser descritos como substantivos, eles também são comumente referenciados como HTTP Verbs (Verbos HTTP). Cada um deles implementa uma semântica diferente, mas alguns recursos são compartilhados por um grupo deles, como por exemplo, qualquer método de requisição pode ser do tipo safe, idempotent ou cacheable (en-US).<p>
<br>

<div>
<img src="https://miro.medium.com/max/1100/0*sJhNJCTKqt2DPwpI"
height="230" width=" 400" align="center"><p>
<p>
</div><br>

# Explicando cada método individualmente:

| Método  | Descrição   |
| ------- | -------- |
|  GET  | O método GET solicita a representação de um recurso específico. Requisições utilizando o método GET devem retornar apenas dados.    |
| HEAD   | O método HEAD solicita uma resposta de forma idêntica ao método GET, porém sem conter o corpo da resposta.   |
| POST  | O método POST é utilizado para submeter uma entidade a um recurso específico, frequentemente causando uma mudança no estado do recurso ou efeitos colaterais no servidor.  |
| PUT  | O método PUT substitui todas as atuais representações do recurso de destino pela carga de dados da requisição.    |
| DELETE   | O método DELETE remove um recurso específico.   |
| CONNECT  | O método CONNECT estabelece um túnel para o servidor identificado pelo recurso de destino. |
| OPTIONS   | O método OPTIONS é usado para descrever as opções de comunicação com o recurso de destino.    |
| TRACE   | O método TRACE executa um teste de chamada loop-back junto com o caminho para o recurso de destino.    |
| PATCH   | O método PATCH é utilizado para aplicar modificações parciais em um recurso.    |<p>


##### <u>Get</u>
Esse método é o mais utilizado, tem a função de solicitar ou requisitar algum recurso ao servidor. É geralmente usado para o retorno de informações sobre uma entidade especificamente ou uma lista delas, mas quando trata-se sobre arquivos muito extensos como listas de dados, é preciso que fique atento sobre a performance da API, e usa-se o conceito de Paginação, que é preferir mostrar a informação repartida em páginas, do que mostrar ela completa de uma vez só, ampliando assim a velocidade de tempo de resposta da API.

##### <u> Post</u>
Método usado para enviar informações ao servidor, é utilizado de forma mais popular em cadastros de dados retirados de um formulário, e também quando enviamos um arquivo para o servidor: seja isso uma foto de perfil, um post no Instagram, tudo isso é usado o método POST.

##### <u>Put</u>
O PUT é responsável por editar arquivos e informações já existentes. Esse método usa-se juntamente com um parâmetro na URL da requisição, que ajudará a identificar através de uma chave única (id) qual elemento ele está referenciando.

##### <u>Delete</u>
Esse método é bem autoexplicativo, deleta arquivos ou informações presentes no banco de dados. Igual o PUT, é recomendável que utilize-o usando um parâmetro na URL da requisição, para que evite problemas de deletar dois arquivos/informações ao mesmo tempo.

##### <u>HEAD</u>
Esse método é muito similar com o GET, a diferença é que esse retorna apenas o cabeçalho da resposta, enquanto o GET retorna tanto o cabeçalho quanto o corpo da resposta.

##### <u>Options</u>
É responsável por retornar as informações referentes ao servidor. Esse método é muitíssimo importante para ferramentas de deploy como o Heroku, pois ele pega todas as informações necessárias para o deploy de forma automática por meio desse método, o que facilita a vida do programador.

##### <u>Trace</u>
Funciona bem mais como uma ferramenta de debug para as API ‘s. Ele reenvia a última requisição para o servidor e verifica se houve alguma interferência de servidores de terceiros.

##### <u>Connect</u>
Dentre os métodos, esse é o mais específico e impopular, é responsável por conectar a API com algum servidor proxy. É mais utilizado para tentar a conexão com sites que possuem segurança e que não permitem conexão direta, dessa forma, é preciso que se conecte a um servidor proxy para depois conseguir acessar seu destino.

# Vídeo: <a href="https://photos.google.com/share/AF1QipM9F_EuNl5GTtcnv_DUsQlFSJMfQ7LYe2rKwq_Md9-nUFAQ133KjI2f_ppuZ35hAg/photo/AF1QipMopz6m8vnI_aRiQJUOO_yajTbsv79TdOcEBvFc?key=MjRGUWNrVWhlcWhvd3ZyYzh2ekNTekZNNXhucWVB" target="blank">Clique Aqui<a/>


</html>


# **O que é HTTP Error?**

Error HTTP são os códigos HTTP que se referem a erros de cliente e servidor, respectivamente, e impedem o carregamento de um site.
Quando você visita um site, o seu navegador faz uma solicitação ao servidor, e o servidor responde o navegador com um código, os códigos HTTP. São esses códigos que informam o que o servidor e navegador estão conversando entre si.
E com as informações do tópico anterior, fica fácil deduzir que os códigos HTTP Error são sempre começados pelos números 4 ou 5, que são respectivamente falhas do cliente (navegador) ou do servidor. Certo? Então vamos para o próximo passo.

# **Quais os principais códigos de erro HTTP?**

Conhecer os principais códigos de erro HTTP vai te ajudar a identificar problemas de navegação no seu site e minimizar os erros, além de entender a comunicação entre o seu navegador e o servidor do site que está tentando acessar. 
Os principais códigos de erros HTTP que você deve ter em mente são os erros 403, 404 (4xx -Erros do cliente), 500 e 503 (5xx Erros do servidor). Então veja agora o que significa os erros de HTTP mais comuns.

**Categoria 4xx, erro do cliente: Esses códigos indicam um erro do cliente, geralmente significando que o cliente solicitou um recurso que não existe ou não há permissão. Por fim, vale lembrar que esta categoria contém o código de status mais reconhecível: “404 Not Found”;**

## **Error 403**

O “Error 403 Forbidden” ocorre quando a página da web (ou outro recurso) que você está tentando abrir no navegador da web é um recurso que você não tem permissão para acessar. É chamado de Erro 403 porque é o código de status HTTP que o servidor da web usa para descrever esse tipo de erro. Normalmente, você obtém esse erro por causa de dois motivos.
O primeiro é que os proprietários do servidor web configuraram corretamente as permissões de acesso e que você realmente não tem permissão para acessar o recurso. O segundo motivo é que os proprietários do servidor da web configuraram permissões incorretamente e você está tendo acesso negado quando na verdade não deveria.
Assim como acontece com os erros 404 e 502, os designers de sites podem personalizar a aparência de um “Error 403”. Portanto, você poderá ver páginas 403 de aparência diferente em diferentes sites. Além disso, os sites também podem usar nomes ligeiramente diferentes para esse erro. Por exemplo, você pode ver coisas como:

•	403 Forbidden;
•	HTTP 403;
•	Forbidden;
•	Erro HTTP 403 – Forbidden;
•	Error HTTP 403.14 – Forbidden;
•	Erro 403;
•	Forbidden: você não tem permissão para acessar [diretório] neste servidor;
•	Erro 403 – Forbidden.

Na grande maioria das vezes, não há muito que você possa fazer para consertar as coisas do seu lado. Dessa forma, ou você realmente não tem permissão para acessar o recurso ou há um erro no lado do servidor. Às vezes, é um erro temporário; às vezes não é.

![Image](https://user-images.githubusercontent.com/112489062/192128280-7b53fc2d-43fd-4588-8a0a-fc61bd2860ed.png)


## **Error 404**

O famoso “Error 404” ocorre quando você tenta visitar uma página da web que não existe. Às vezes, o problema está no próprio site e não há muito que você possa fazer a respeito. Mas às vezes, o problema é algo que você pode resolver – talvez você tenha digitado o endereço errado ou talvez o cache do navegador esteja causando problemas. 

## **O que é um “Error 404”?**

você obtém um “Error 404” quando a página da web que está tentando acessar não existe. Dessa forma, ele recebe esse nome pois é o código de status HTTP que o servidor da web usa para descrever esse tipo de erro. os sites também podem usar nomes ligeiramente diferentes para esse erro. Por exemplo, você pode ver coisas como:

•	404;
•	404 Recurso não encontrado;
•	Error 404;
•	HTTP 404;
•	404 não encontrado;
•	Error 404 não encontrado;
•	404 Página Não Encontrada;
•	404 – Arquivo ou diretório não encontrado.
Todos eles significam a mesma coisa.

### **Quais os motivos desses erros estarem aparecendo?**

Existem vários motivos pelos quais você pode receber um código HTTP 404:
•	Um “gatilho típico” para uma mensagem de “Error 404” é quando a página foi excluída do site;
•	A página está com outra URL e o redirecionamento foi feito incorretamente;
•	Você inseriu um endereço de URL incorreto;
•	Embora isso aconteça muito raramente, às vezes o servidor apresenta mau funcionamento;
•	O nome de domínio inserido não existe mais.

Links quebrados costumam ficar presentes por longos períodos depois que a página foi excluída ou movida. A razão para isso é que os sites vinculados a esta página não são informados de que o site não existe mais ou que pode ser encontrado em um novo URL. É comum que os sites não verifiquem seus links internos regularmente, fazendo com que os usuários tentem acessar um link inativo. Portanto, é por isso que os webmasters precisam realizar manutenção regular do site.  

### **O que fazer quando dá “Error 404”?**

Existem vários procedimentos que podem ser feitos:
– Recarregar a página;
– Verificar o endereço;
– Limpar o cache do navegador;
– Mudar o servidor DNS;
– Verificar se o site possui algum problema temporário.

![Image](https://user-images.githubusercontent.com/112489062/192128344-e6bea93a-2fbc-4392-94c9-f41e0e0d3c5a.png)

**Categoria 5xx, erro de servidor: Esses códigos indicam que o servidor encontrou um erro ou está em manutenção temporária ou tempo de inatividade.**

## **Error 500**

Este erro não é tão comum de acontecer, mas uma hora ou outra ele aparece! Erro 500 significa que algum script ou solicitação não foi compreendida – o que nem sempre indica um problema com o servidor. Os motivos podem ser arquivos .htaccess corrompidos, permissões de arquivo incorreto, tempo limite de script, versão do PHP incompatível ou atualizações do WordPress. No entanto, pode haver muitas outras razões, e será necessário pesquisar mais a fundo para saberá real causa. 

![Image](https://user-images.githubusercontent.com/112489062/192128493-1ea1601b-d560-41cb-9929-308e72d5eb15.png)

## **Erro 503**
Se seu site apresentar o erro "503 Service Unavailable", seguido de "The server is temporarily unable to service your request due to maintenance downtime or capacity problems", isso indica que sua requisição de acesso ao site bateu em algum limite do plano de hospedagem. Todo plano de hospedagem tem um limite pré-estabelecido de:

•	memória
•	processamento (CPU)
•	número de processos
•	acesso ao disco (entrada/saída, ou I/O)
•	número de acessos ao site
•	transferência de/para o banco de dados

Se um desses limites for atingido, o site pode apresentar o erro 503 Service Unavailable. Para resolver isso, você tem duas opções: fazer o upgrade do seu plano de hospedagem ou otimizar seu site para utilizar os recursos disponíveis a ele de forma mais eficiente. 

![Image](https://user-images.githubusercontent.com/112489062/192128573-330e8b2e-ab65-4084-867d-1b402bb47b88.png)



Link do Vídeo.

https://drive.google.com/file/d/1-00duXYqRDpMnVX1__lyxzG6IHZAOjdZ/view?usp=sharing










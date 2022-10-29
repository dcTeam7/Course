# Conceito de Computação em Nuvem (Cloud Computing)

 <img src="https://github.com/fadetobash/fadetobash/blob/main/images/Nuvem.gif?raw=true">

<p align="justify"><em> 
“A nuvem não é uma entidade física, mas sim uma vasta rede de servidores remotos em todo o mundo que estão conectados e destinados a operar como um único ecossistema. Em vez de acessar arquivos e dados de um computador pessoal ou local, você os acessa on-line de qualquer dispositivo com acesso à Internet - as informações estarão disponíveis em qualquer lugar e a qualquer momento que você precisar” - Microsoft Azure
</em></p>

  
<p align="justify"> 
Seguindo esse conceito obtido na documentação de uma das maiores plataformas provedoras de serviços em nuvem, podemos resumir que se trata de uma tecnologia de computação de dados que fornece pela internet recursos que dentre os principais, estão; computação (Compute, VMs), armazenamento e banco de dados (Storage and Databases), comunicação (Networking) e capacidade de análise de dados (Analytics).
</p>

  

<p align="justify">
Provedores de nuvem como AWS, Azure, Google Cloud, auxiliam a maioria dos serviços modernos baseados em web. Netflix, AirBnb, Spotify, Icloud, Twitch e tantos outros, se beneficiam da nuvem de alguma forma.
</p>
  

### Um exemplo contextual:

<img src="https://github.com/fadetobash/fadetobash/blob/main/images/RedBullCrash.gif?raw=true" width="40%" />

**Formula 1**

<p align="justify"> 
Como a maioria das transmissões de eventos esportivos, a F1 fornece informações, por exemplo, na tela de nossos televisores, as condições climáticas, pit stops, estatísticas dos pilotos e seus times, ultrapassagem, temperatura de pneus e etc. Como isso é alcançado é bem interessante. Eles armazenam mais de 65 anos de dados históricos de corrida e estatísticas críticas de desempenho em um serviço de nuvem na plataforma AWS - Amazon Web Services, chamado S3 (Serviço de armazenamento de alta disponibilidade de dados, segurança e performance), cientistas de dados da F1 realizam consultas de dados através de um processo de deep learning auxiliados por outro serviço de nuvem, o AWS Sage Maker (Serviço que facilita a criação, treinamento e implantação de modelos de machine learning), e assim geram os dados que chegam às nossas telinhas. 
</p>

Veja em [Porque a F1 escolhe a AWS](https://aws.amazon.com/pt/f1/)

# Os 3 modelos de implantação da nuvem 

<img src="https://github.com/fadetobash/fadetobash/blob/main/images/hybrid-multi-cloud-global-representation-scaled.webp?raw=true">


 **Nuvem Pública (_Public Cloud_)**

<p align="justify"> 
São ambientes de nuvem criados a partir de uma infraestrutura de TI que não é de propriedade do usuário final. Alguns dos maiores provedores de nuvem pública são a Amazon Web Services (AWS), Microsoft Azure, Google Cloud, IBM Cloud.
</p>


**Características**

<p align="justify">
   
-   Arquitetura multi-tenant (Quando uma única instância ou instalação é capaz de atender a vários clientes. Exemplo: Uma empresa usando um serviço/aplicação de outra empresa, numa relação B2B, business to business).  
-   Modelo de preço ‘pagamento conforme o uso’ (Pay as you go).
-   Não é necessário manutenção
    
-   Escalabilidade
</p>


**Prós**

<p align="justify">

- Como a nuvem pública compartilha recursos computacionais, os benefícios de se usar uma nuvem pública vão desde redução de custos, eficiência de tempo e agilidade. Um grupo que utiliza este tipo de nuvem, não se preocupa em custos de instalação, operação e manutenção de servidores e outros equipamentos.
</p>


**Contras**

 <p align="justify">

- Entretanto, pelo fato da configuração, manutenção e segurança não serem da responsabilidade de quem contrata esse tipo de serviço, seus dados podem ficar vulneráveis a riscos de segurança.
</p>


**Exemplos de nuvem pública:**

-   Microsoft Azure
    
-   IBM Cloud
    
-   VMWare
    
#

**Nuvem Privada (_Private Cloud_)**
  

<p align="justify"> 
São ambientes de nuvem dedicadas exclusivamente a um único usuário final ou grupo, nesse tipo de nuvem a infraestrutura de TI é desenvolvida localmente, com acesso isolado e recursos não compartilhados. Porém, não necessariamente, estas precisam ser originadas de uma infraestrutura local. As organizações podem construir nuvens privadas em data centers alugados de propriedade de fornecedores fora do grupo. Desta forma, temos uma divisão de nuvem privada em subtipos: Nuvem privada gerenciada (On-premise cloud solutions) e Nuvem dedicad (Externally hosted cloud solutions)
</p>

  

**Características**

<p align="justify"> 
    
- Arquitetura single-tenant (Arquitetura de locatário único, diferente da multi-tenant)

- Cliente dedicado
    
-   Alta confiabilidade
    
-   Eficiência
    
-   Alta segurança
    
-   Escalabilidade e autoatendimento
</p>
  

**Prós**
<p align="justify">

- O benefício predominante, é o alto nível de segurança e controle. De todos os tipos de computação em nuvem, apenas uma nuvem privada permite que você personalize os servidores em nuvem de acordo com suas próprias preferências. Também é mais confiável e, portanto, mais adequado para informações confidenciais seguras e sistema central. Desta forma, é um dos tipos de nuvem mais utilizados em organizações governamentais e empresas financeiras.
</p>
  

**Contras**

<p align="justify">

- O hardware deve ser adquirido para inicialização e manutenção do ambiente, além dos custos operacionais de serviços de TI (CaPeX e OpEx), despesas capitais e operacionais. Não é uma opção acessível para todas as empresas, especialmente as menores, devido aos altos custos operacionais para manutenção contínua. Sendo nesse caso, um tipo de nuvem mais utilizado em organizações governamentais
</p>    

  

**Exemplos de nuvem privadas**
<p align="justify">

-   Microsoft

-   Hewllet-Packard

-   Citrix
    
-   Ubuntu
    
-   Dell
    
-   Cisco
</p>

#

**Nuvem Híbrida (_Hybrid Cloud_)**

<p align="justify">
Nuvens híbridas, como o nome indica, é o uso das duas principais nuvens, pública e privada em paralelo e interseccionadas de acordo com o propósito. Com nuvens híbridas, você pode alternar entre nuvens públicas e privadas e escolher onde colocar dados e aplicativos com base em suas necessidades. Essa flexibilidade permite que você se beneficie dos melhores recursos dos dois tipos de acordo com seus requisitos de negócios.
</p>

  
  

**Características**

<p align="justify">

-   Alta escalabilidade e elasticidade
    
-   Parcialmente compartilhada e dedicada
    
-   Fácil transição
    
-   Protegidas e seguras
</p>


**Prós**
<p align="justify">

- Devido à alta escalabilidade e elasticidade, as nuvens híbridas são um dos melhores tipos de opções de computação em nuvem disponíveis. Com a computação em nuvem híbrida, você obtém os benefícios da nuvem pública e privada e muito mais, como a capacidade de criar aplicativos novos e inovadores com demandas incertas.

**Caso de uso**: _Negócios com cargas de trabalho altamente variáveis. Por exemplo, se houver um pico na demanda e a carga de trabalho do seu sistema de entrada de pedidos aumentar durante as vendas da Black Friday, a nuvem híbrida pode ser a melhor opção para você. Você pode executar o aplicativo em sua nuvem privada e usar recursos de computação adicionais de uma nuvem pública._
</p>

**Contras**
<p align="justify">

- Como a maioria dos outros exemplos de computação em nuvem, a nuvem híbrida também tem seu próprio conjunto de desvantagens. Uma nuvem híbrida requer um alto nível de compatibilidade e conectividade de rede para fazer a nuvem privada interagir com a nuvem pública. Portanto, requer conhecimentos de gerenciamento de TI mais complexos. Ele também pode enfrentar problemas de desempenho ao lidar com grandes volumes de dados.
</p> 



**Exemplo de nuvens híbridas**

<p align="justify">

-   Microsoft Azure
    
-   IBM
    
-   Amazon AWS
    
-   Dell EMC
    
-   Cisco
    
-   VMWare
    
-   Hewlett-Packard
</p>


# Conclusão
<p align="justify">
Em um mundo onde a tecnologia cresce exponencialmente, como na robótica, inteligência artificial, internet das coisas, big data, a nuvem entra nesse <em>hall</em> de tecnologias provendo recursos poderosos e que juntos nos propiciam vários benefícios do seu uso, além de agregar, sobretudo, valor econômico para as organizações, trazendo uma nova forma de lidar com infraestrutura, diminuindo o risco do componente humano de falhas e o potencial risco de hardware físico. A TI tradicional se vê num momento onde é inerente a busca pelo conhecimento e aprimoramento de sua infraestrutura, a fim de prover soluções inovadoras, seguras e modernas para diferentes tipos de negócios. Estamos vivendo em uma era de renascimento tecnológico para a infraestrutura de TI como a conhecemos. E como profissionais e/ou meros usuários da nuvem, já estamos nos beneficiando do que já vem sendo e ainda será um grande ecossistema tecnológico universal.
</p>

#

### Bibliografia

  
What is the cloud?

[https://azure.microsoft.com/en-us/resources/cloud-computing-dictionary/what-is-the-cloud/](https://azure.microsoft.com/en-us/resources/cloud-computing-dictionary/what-is-the-cloud/)

  
A Holistic Introduction to the Cloud

[https://levelup.gitconnected.com/cloud-curious-a-holistic-introduction-to-the-cloud-5af4d317f822](https://levelup.gitconnected.com/cloud-curious-a-holistic-introduction-to-the-cloud-5af4d317f822)

  
4 Types of Cloud Computing

[https://www.goodcore.co.uk/blog/types-of-cloud-computing/](https://www.goodcore.co.uk/blog/types-of-cloud-computing/)
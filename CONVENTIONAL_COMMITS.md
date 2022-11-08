

# Exemplos

## Imperativo ao invés de pretérito (modo passado)

Sei que pode parecer estranho ao primeiro momento escrever a mensagem no imperativo, pois a mudança implementada foi uma ação passada, mas escrevendo commits utilizando o imperativo nós estamos dizendo à nossa equipe o que ele fará se aplicado. No artigo de Chris Beams ele diz um pouco mais sobre a escolha do imperativo e traz uma grande notação à qual, todo subject (texto do commit) deve se enquadrar, como no seguinte caso:

> "If applied, this commit will [message]"

Em português: “Se aplicado, esse commit irá [mensagem]”. Se pensarmos no exemplo representado acima, o resultado seria:

> "If applied, this commit will change the markup", o que faz muito mais sentido do que: "If applied, this commit will changed the markup"

##

## Compondo uma mensagem de commit

Visto a importância do contexto nas mudanças em cada projeto, caso quisermos deixar bem documentadas e apresentáveis, podemos tomar dois exemplos de pessoas que trabalharam em projetos onde a disciplina de commit é essencial.

Peter Hutterer, o principal mantenedor da libinput (Se você usou o mouse no Linux para acessar esse artigo pode agradecer a esse homem) conta em um artigo em seu blog:

Uma boa mensagem de commit deve responder as essas três questões sobre determinada mudança:
Por que essa mudança é necessária? A mesma pode corrigir um bug, adicionar uma feature, melhorar a performance ou a segurança.
Como a mesma resolve o problema? Para mudanças pequenas e óbvias essa parte pode ser omitida, mas a mesma consiste em uma descrição de alto nível de qual foi a abordagem usada para tratar o determinado problema.
Quais os efeitos essas mudanças tem? Além das óbvias, isso pode incluir benchmarks, efeitos colaterais, etc.

E para um exemplo mais estático, Linus Torvalds (Criador do Git e Linux) na sua pagina de contribuição para seu outro projeto Subsurface, comentou um modelo de uma boa mensagem de commit:

sugestion

Cabeçalho: Explique esse commit em uma linha (Use a linguagem imperativa)

O corpo da mensagem de commit são algumas linhas de texto, explicando
em mais detalhes e possivelmente apresentando mais contexto sobre o
problema sendo tratado.

O corpo da mensagem de commit pode ser diversos paragráfos e
por favor façam corretamente a quebra de linha e mantenham as
colunas menos que 74 caracteres. Assim, o comando "git log"
irá mostrar a mensagem de forma agradavel mesma que esteja identada.

Faça questão de explicar a sua solução e por que voce está fazendo
o que está fazendo, ao invés de apenas descrever o que está fazendo de forma superficial.
Pense que revisores e o seu eu-futuro irão ler essas mudanças, mas podem não entender
por que determinada solução foi implementada.

Reported-by: quem-reportou
Signed-off-by: Seu Nome [email@host.com](mailto:email@host.com)

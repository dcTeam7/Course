

# Exemplos

## Imperativo ao invés de pretérito (modo passado)

Sei que pode parecer estranho ao primeiro momento escrever a mensagem no imperativo, pois a mudança implementada foi uma ação passada, mas escrevendo commits utilizando o imperativo nós estamos dizendo à nossa equipe o que ele fará se aplicado. No artigo de Chris Beams ele diz um pouco mais sobre a escolha do imperativo e traz uma grande notação à qual, todo subject (texto do commit) deve se enquadrar, como no seguinte caso:

> "If applied, this commit will [message]"

Em português: “Se aplicado, esse commit irá [mensagem]”. Se pensarmos no exemplo representado acima, o resultado seria:

> "If applied, this commit will change the markup", o que faz muito mais sentido do que: "If applied, this commit will changed the markup"

##

## Padrões de Commits: por que utilizar? 

De modo geral, o versionamento consiste em estratégias para gerenciar as diferentes versões de um código, de um sistema ou de um modelo. Então, os commits são formas de administrar as mudanças que são feitas e de garantir mais segurança na transição de uma versão para outra.
Sendo assim, para poder otimizar o tempo de desenvolvimento de um projeto e entender em que ponto está esse desenvolvimento, os commits se fazem extremamente necessários. Por conta disso, eles precisam ser levados a sério e nomeados da melhor e mais clara maneira possível.

Assim, utilizar Padrões de Commits, também chamados de Conventional Commits ou Commits Semânticos, é uma excelente forma de melhorar os seus commits.
Utilizar os padrões de commits no dia a dia é, sem sombra de dúvidas, necessário. Principalmente em grandes projetos, em que existem inúmeras features que, com o passar do tempo, pode acabar ficando caótico navegar na linha do tempo dos commits.

Assim, utilizar o conjunto de regras apresentadas neste artigo permitirá que tanto desenvolvedores quanto todos os demais stakeholders consigam entender em que estado do desenvolvimento a aplicação se encontra, quais features já foram implementadas e em que escopo elas afetarão.

Dessa forma, quando for fazer um novo commit, lembre-se de aplicar essas regras.

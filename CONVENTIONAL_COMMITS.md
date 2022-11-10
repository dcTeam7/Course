

# Exemplos

## Imperativo ao invés de pretérito (modo passado)

Sei que pode parecer estranho ao primeiro momento escrever a mensagem no imperativo, pois a mudança implementada foi uma ação passada, mas escrevendo commits utilizando o imperativo nós estamos dizendo à nossa equipe o que ele fará se aplicado. No artigo de Chris Beams ele diz um pouco mais sobre a escolha do imperativo e traz uma grande notação à qual, todo subject (texto do commit) deve se enquadrar, como no seguinte caso:

> "If applied, this commit will [message]"

Em português: “Se aplicado, esse commit irá [mensagem]”. Se pensarmos no exemplo representado acima, o resultado seria:

> "If applied, this commit will change the markup", o que faz muito mais sentido do que: "If applied, this commit will changed the markup"

##

## O que é um commit?
É o registro de uma modificação em um banco de dados que neste estudo é o GitHub. O Commit é uma escrita na história do software, você como programador está escrevendo em uma parte da história daquele produto, aquilo está registrado, então você como escritor não faça uma má escrita. Assim como não deve-se escrever um mal código, não deve-se escrever um mal commit. 

## A especificação do Conventional Commits :

é uma convenção simples para utilizar nas mensagens de commit. Ela define um conjunto de regras para criar um histórico de commit explícito, o que facilita a criação de ferramentas automatizadas baseadas na especificação. Esta convenção se encaixa com o [SemVer](https://semver.org/), descrevendo os recursos, correções e modificações que quebram a compatibilidade nas mensagens de commit. Essa padronização veio para solucionar um problema que muita gente encontra ao fazer uma revisão de um PR (pull request), ou quando se entra em uma empresa ou squad novo e tenta entender o que foi feito no fluxo de trabalho do Git. Conventional Commits é uma forma de padronização de commits dentro de um projeto de desenvolvimento de software, utilizando regras simples e claras, que contribui para reduzir o tempo gasto em compreender como e por que algo foi feito em uma alteração ou correção posterior.



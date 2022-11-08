

# Exemplos

## Imperativo ao invés de pretérito (modo passado)

Sei que pode parecer estranho ao primeiro momento escrever a mensagem no imperativo, pois a mudança implementada foi uma ação passada, mas escrevendo commits utilizando o imperativo nós estamos dizendo à nossa equipe o que ele fará se aplicado. No artigo de Chris Beams ele diz um pouco mais sobre a escolha do imperativo e traz uma grande notação à qual, todo subject (texto do commit) deve se enquadrar, como no seguinte caso:

> "If applied, this commit will [message]"

Em português: “Se aplicado, esse commit irá [mensagem]”. Se pensarmos no exemplo representado acima, o resultado seria:

> "If applied, this commit will change the markup", o que faz muito mais sentido do que: "If applied, this commit will changed the markup"

##

## Qual conteúdo deve conter um Commit Inicial?

Mesmo o commit inicial sendo o primeiro em um projeto, ainda é um commit como outro qualquer. Logo, deve conter algum conteúdo.

Mas qual arquivo devo incluir neste commit? Isso depende se o projeto está começando do zero ou se já tem algum código escrito ou um conjunto de arquivos de código que serão usados como ponto de partida.

Para projetos que começam do zero, tipicamente não existe nenhum arquivo com código ainda, nesse caso o commit inicial vai conter um único arquivo chamado README.md, que será simplesmente um arquivo descrevendo o propósito do projeto.

Para projetos que já tem algum arquivo ou código, o commit inicial normalmente inclui todos esses arquivos de uma vez. Esse commit funciona como uma versão inicial do projeto no Git. Os desenvolvedores vão trabalhar a partir disso para adicionar novas funções e funcionalidades ao projeto.

Dito isso, um commit inicial deve ser feito como se o projeto já estivesse em andamento.

ex.:
Add README.md

Initialize Project

Add README.md
Add .gitignore

##


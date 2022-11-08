

# Exemplos

## Imperativo ao invés de pretérito (modo passado)

Sei que pode parecer estranho ao primeiro momento escrever a mensagem no imperativo, pois a mudança implementada foi uma ação passada, mas escrevendo commits utilizando o imperativo nós estamos dizendo à nossa equipe o que ele fará se aplicado. No artigo de Chris Beams ele diz um pouco mais sobre a escolha do imperativo e traz uma grande notação à qual, todo subject (texto do commit) deve se enquadrar, como no seguinte caso:

> "If applied, this commit will [message]"

Em português: “Se aplicado, esse commit irá [mensagem]”. Se pensarmos no exemplo representado acima, o resultado seria:

> "If applied, this commit will change the markup", o que faz muito mais sentido do que: "If applied, this commit will changed the markup"

##

## Atomic commits

Um `atomic commit` é um `commit` que tem como objetivo corrigir, **implementar ou refazer algo que está pronto e com seus arquivos dentro de um mesmo contexto.** Usando essa abordagem você garante que seu histórico do git seja mais organizado tornando possível navegar pelo histórico com menos dificuldade e facilitando achar os commits que você deseja.

Em resumo, a cada correção ou implantação individual se deve executar um processo de `commit.`


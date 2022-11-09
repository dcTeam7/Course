

# Exemplos

## Imperativo ao invés de pretérito (modo passado)

Sei que pode parecer estranho ao primeiro momento escrever a mensagem no imperativo, pois a mudança implementada foi uma ação passada, mas escrevendo commits utilizando o imperativo nós estamos dizendo à nossa equipe o que ele fará se aplicado. No artigo de Chris Beams ele diz um pouco mais sobre a escolha do imperativo e traz uma grande notação à qual, todo subject (texto do commit) deve se enquadrar, como no seguinte caso:

> "If applied, this commit will [message]"

Em português: “Se aplicado, esse commit irá [mensagem]”. Se pensarmos no exemplo representado acima, o resultado seria:

> "If applied, this commit will change the markup", o que faz muito mais sentido do que: "If applied, this commit will changed the markup"

##

Como o Conventional Commits trata os commits de reversão?

Reverter código pode ser complicado: você está revertendo vários commits? se você reverter um recurso, a próxima versão deve ser um patch?

O Conventional Commits não o força a definir um comportamento de reversão. Em vez disso, deixamos isso para que os autores de ferramentas usem a flexibilidade de tipos e rodapés para desenvolver sua própria lógica para lidar com reversões.

Uma recomendação é usar o tipo revert e um rodapé que referencia os SHAs de commit que estão sendo revertidos:

revert: nunca mais falaremos do incidente do miojo

Refs: 676104e, a215868
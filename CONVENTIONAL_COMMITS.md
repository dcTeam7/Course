

# Exemplos

## Imperativo ao invés de pretérito (modo passado)

Sei que pode parecer estranho ao primeiro momento escrever a mensagem no imperativo, pois a mudança implementada foi uma ação passada, mas escrevendo commits utilizando o imperativo nós estamos dizendo à nossa equipe o que ele fará se aplicado. No artigo de Chris Beams ele diz um pouco mais sobre a escolha do imperativo e traz uma grande notação à qual, todo subject (texto do commit) deve se enquadrar, como no seguinte caso:

> "If applied, this commit will [message]"

Em português: “Se aplicado, esse commit irá [mensagem]”. Se pensarmos no exemplo representado acima, o resultado seria:

> "If applied, this commit will change the markup", o que faz muito mais sentido do que: "If applied, this commit will changed the markup"

#
## Utilizar emoji nos commits

Os emojis podem ajudar muito a dar um pouco de personalidade nos commits e até a melhorar a leitura, já que conseguimos saber qual o tipo do commit em apenas bater o olho.
Por exemplo :
> 🐛: esse commit irá consertar o bug referente à issue #33

> 🖌️: esse commit irá melhorar o design do card do usuário da issue #33

Para um guia de emojis que podem ser usados em commits segue o link do gitmoji
https://gitmoji.dev/
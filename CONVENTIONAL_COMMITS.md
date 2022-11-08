

# Exemplos

## Imperativo ao invés de pretérito (modo passado)

Sei que pode parecer estranho ao primeiro momento escrever a mensagem no imperativo, pois a mudança implementada foi uma ação passada, mas escrevendo commits utilizando o imperativo nós estamos dizendo à nossa equipe o que ele fará se aplicado. No artigo de Chris Beams ele diz um pouco mais sobre a escolha do imperativo e traz uma grande notação à qual, todo subject (texto do commit) deve se enquadrar, como no seguinte caso:

> "If applied, this commit will [message]"

Em português: “Se aplicado, esse commit irá [mensagem]”. Se pensarmos no exemplo representado acima, o resultado seria:

> "If applied, this commit will change the markup", o que faz muito mais sentido do que: "If applied, this commit will changed the markup"

##


## O que eu faço se acidentalmente usar o tipo errado de commit?


### - Quando você usou um tipo da especificação, mas não do tipo correto, por exemplo ***`fix`*** em vez de ***`feat`***
Antes do merge ou release com o erro, recomendamos o uso de `git rebase -i` para editar o histórico do commit. Após o release, a limpeza será diferente de acordo com as ferramentas e processos que você utiliza.

### -  Quando você usou um tipo que não é da especificação, por exemplo ***`feet`*** em vez de ***`feat`***
Na pior das hipóteses, não é o fim do mundo se um commit não atender à especificação do Conventional Commits[[2]][Conventional Commits]. Significa apenas que o commit será ignorado por ferramentas baseadas nessa especificação.

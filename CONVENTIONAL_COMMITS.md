

# Exemplos

## Imperativo ao invés de pretérito (modo passado)

Sei que pode parecer estranho ao primeiro momento escrever a mensagem no imperativo, pois a mudança implementada foi uma ação passada, mas escrevendo commits utilizando o imperativo nós estamos dizendo à nossa equipe o que ele fará se aplicado. No artigo de Chris Beams ele diz um pouco mais sobre a escolha do imperativo e traz uma grande notação à qual, todo subject (texto do commit) deve se enquadrar, como no seguinte caso:

> "If applied, this commit will [message]"

Em português: “Se aplicado, esse commit irá [mensagem]”. Se pensarmos no exemplo representado acima, o resultado seria:

> "If applied, this commit will change the markup", o que faz muito mais sentido do que: "If applied, this commit will changed the markup"

##

## Utilização dos Types + Identificação sobre Issues

Acredito que a padronização de commits seja essencial para organização de um trabalho em equipe ou ate mesmo individual, uma tarefa dada a uma equipe. Após sua divisão entre os membros, haverá com certeza vários commits, até por que a cada avanço na tarefa precisamos comittar, para que não se torne uma tarefa digamos chata de se fazer, com descrição longa do que foi feito durante o processo que antecede o commit. Acredito que os valores primordiais seriam o uso do "type", "descrição", "id issue". Mesmo com essa informações acima, venho dar uma sugestão, algo que não sei se existe mas os types deveriam seguir algo parecido com o Label referente as cores para uma possível prioridade. Exemplo: 
> type fix: trata-se de uma possível correção de bugs no caso assumiria um cor em vermelho.




# Exemplos

## Imperativo ao invés de pretérito (modo passado)

Sei que pode parecer estranho ao primeiro momento escrever a mensagem no imperativo, pois a mudança implementada foi uma ação passada, mas escrevendo commits utilizando o imperativo nós estamos dizendo à nossa equipe o que ele fará se aplicado. No artigo de Chris Beams ele diz um pouco mais sobre a escolha do imperativo e traz uma grande notação à qual, todo subject (texto do commit) deve se enquadrar, como no seguinte caso:

> "If applied, this commit will [message]"

Em português: “Se aplicado, esse commit irá [mensagem]”. Se pensarmos no exemplo representado acima, o resultado seria:

> "If applied, this commit will change the markup", o que faz muito mais sentido do que: "If applied, this commit will changed the markup"

##


## Aqui temos um ótimo modelo de boas mensagens de commit, escrito originalmente por Tim Pope

Resumo com Capitalização e Breve (no Máximo, 50 Caracteres)

Texto explicativo mais detalhado, se necessário. Deixe-o com, cerca de 72 caracteres. Em alguns contextos, a primeira linha é tratada como o assunto de um e-mail e o resto do text como o corpo. A linha em branco separando o resumo do corpo é fundamental (a menos que você não escreva uma descrição detalhada); ferramentas como o rebase podem se confundir se você executar ambas em conjunto.

Escreva sua mensagem de commit no imperativo: "Consertar o bug" em vez de "Bug consertado" ou "Conserta o bug". Esta convenção corresponde às mensagens de commit geradas por comandos como o git merge e o git revert.

Outros parágrafos vêm após linhas em branco.

Colocar a descrição em itens está ok

Tipicamente, um hífen ou um asterisco é usado como bullet point (marcação de itens), seguido de um único espaço, envolvido por linhas em branco, mas as convenções variam

Use indentação

Se você usar um rastreador de Issues, adicione uma referência a eles ao final, dessa maneira:

Resolve a issue nº 123

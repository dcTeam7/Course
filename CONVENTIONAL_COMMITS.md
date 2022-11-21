

# Exemplos

## Imperativo ao invés de pretérito (modo passado)

Sei que pode parecer estranho ao primeiro momento escrever a mensagem no imperativo, pois a mudança implementada foi uma ação passada, mas escrevendo commits utilizando o imperativo nós estamos dizendo à nossa equipe o que ele fará se aplicado. No artigo de Chris Beams ele diz um pouco mais sobre a escolha do imperativo e traz uma grande notação à qual, todo subject (texto do commit) deve se enquadrar, como no seguinte caso:

> "If applied, this commit will [message]"

Em português: “Se aplicado, esse commit irá [mensagem]”. Se pensarmos no exemplo representado acima, o resultado seria:

> "If applied, this commit will change the markup", o que faz muito mais sentido do que: "If applied, this commit will changed the markup"

## <br><br>



## Atomic commits


Um `atomic commit` é um `commit` que tem como objetivo corrigir, **implementar ou refazer algo que está pronto e com seus arquivos dentro de um mesmo contexto.** Usando essa abordagem você garante que seu histórico do git seja mais organizado tornando possível navegar pelo histórico com menos dificuldade e facilitando achar os commits que você deseja.

Em resumo, a cada correção ou implantação individual se deve executar um processo de `commit.`

Em um projeto grande, é normal que muitas vezes façamos uma sequencia grande de mudanças, e nem sempre essas alterações
possuem algo em comum. Quando agrupamos todas essas alterações em um único `commit`, pode parecer mais prático, mas essa ação 
pode trazer certos desafios no futuro, como buscar um bug na sua fonte ou reverter alterações potencialmente danosas sem comprometer as alterações que estão corretas.

Os `commits atômicos` permitem que essas alterações sejam mais facilmente gerenciaveis, já que eles são responsáveis por
documentar uma única e completa unidade de trabalho.

Os commits atômicos não precisam limitar-se a um único arquivo ou a algumas linhas de códigos, mesmo isso não sendo um problema,
contanto que as alterações estejam facilmente descritas em uma única mensagem sugestiva e relacionada unicamente ao trabalho feito.

Como dito inicialmente, se um commit for revertido e nessa reversão outras partes do trabalho que não estão citadas na base da
mensagem forem alteradas, ou se na sua remoção do histórico remover também alterações legítimas, esse não pode ser considerado um `commit atômico.`

### Dicas de como escrever commits limpos e atômicos

• Use um tempo verbal e permaneça nele<br>
• Mencione o que foi alterado **( função, componente, área do código )**<br>
• Mencione o bug, se houver, que seu commit resolve **(De preferência
mencionando também o commit com bug)**<br>
• Referenciar o problema na sua mensagem de confirmação, criando um
link para um problema e facilitando o rastreamento das PR's **(Ex. Message #12345)**<br><br>

Aqui vai um <a href="https://www.youtube.com/watch?v=NpTF7HsuG5U">tutorial</a> de como fazer `commits atômicos` pelo **Vscode**

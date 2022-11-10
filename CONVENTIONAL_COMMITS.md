

# Exemplos

## Imperativo ao invés de pretérito (modo passado)

Sei que pode parecer estranho ao primeiro momento escrever a mensagem no imperativo, pois a mudança implementada foi uma ação passada, mas escrevendo commits utilizando o imperativo nós estamos dizendo à nossa equipe o que ele fará se aplicado. No artigo de Chris Beams ele diz um pouco mais sobre a escolha do imperativo e traz uma grande notação à qual, todo subject (texto do commit) deve se enquadrar, como no seguinte caso:

> "If applied, this commit will [message]"

Em português: “Se aplicado, esse commit irá [mensagem]”. Se pensarmos no exemplo representado acima, o resultado seria:

> "If applied, this commit will change the markup", o que faz muito mais sentido do que: "If applied, this commit will changed the markup"

#

Pensar no todo. Acredito que as boas praticas e padronização dos Commits refletem diretamente no desempenho do trabalho. A Agilidade e o entendimento entre as diferentes partes do projeto só é possível com organização e metodologia. Só assim, alguém no Brasil pode trabalhar com alguém na China no mesmo projeto. Não podemos tambem esquecer que somos HOJE parte de um projeto que poderá ser continuado ou melhorado no futuro por outros profissionais. Qual o legado que queremos deixar? A da organização, padronização e praticidade? Seremos lembrados pela maneira que atuamos HOJE!

Fica o lembrete:

Compromissos Convencionais 1.0.0
Resumo
A especificação de Commits Convencionais é uma convenção leve em cima das mensagens de confirmação. Ele fornece um conjunto fácil de regras para criar um histórico de confirmação explícito; o que torna mais fácil escrever ferramentas automatizadas em cima. Essa convenção se encaixa com [SemVer](http://semver.org/) , descrevendo os recursos, correções e alterações importantes feitas nas mensagens de confirmação.

A mensagem de confirmação deve ser estruturada da seguinte forma:

<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
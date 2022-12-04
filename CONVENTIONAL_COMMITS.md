

# Exemplos

## Imperativo ao invés de pretérito (modo passado)

Sei que pode parecer estranho ao primeiro momento escrever a mensagem no imperativo, pois a mudança implementada foi uma ação passada, mas escrevendo commits utilizando o imperativo nós estamos dizendo à nossa equipe o que ele fará se aplicado. No artigo de Chris Beams ele diz um pouco mais sobre a escolha do imperativo e traz uma grande notação à qual, todo subject (texto do commit) deve se enquadrar, como no seguinte caso:

> "If applied, this commit will [message]"

Em português: “Se aplicado, esse commit irá [mensagem]”. Se pensarmos no exemplo representado acima, o resultado seria:

> "If applied, this commit will change the markup", o que faz muito mais sentido do que: "If applied, this commit will changed the markup"

##

## Utilização de prefixos: Types

<p align="justify">
Seguindo as especificações do <a href="https://www.conventionalcommits.org/en/v1.0.0/#specification">conventional commits</a>, é importante a prática de utilizar prefixos (types) de identificação em commits. Em destaque, ao se criar issues, assim,  favorecendo a compreensão das partes envolvidas, do que está sendo contribuído, seja em correções, novas funcionalidades e etc. Além da importância na automação de changelogs. </p>

<a href="http://karma-runner.github.io/0.10/dev/git-commit-msg.html">Abaixo segue alguns prefixos(types) padrões</a>

<p align="justify">
Valores (types) utilizados:

Type | Valor
-------- | --------
**feat** | (new feature / nova funcionalidade/característica)    
**fix** | (bug fix / correção de bugs)
**docs** | (changes to documentation / mudanças na documentação)
**style** | (formatting, missing semi colons, etc; no code change / formatação, sem mudanças no código)
**refactor** | (refactoring production code / refatoração de código)
**test** | (adding missing tests, refactoring tests; no production code change / testes, sem mudanças no código em produção)
**chore** | (updating grunt tasks etc; no production code change)


**Exemplos do formato da mensagem de commit:**

***`<type>: <subject>`***

* `feat: new button function...`
* `fix: broken links errors`
* `style: change menu icons`
</p>



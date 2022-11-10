

# Exemplos

## Imperativo ao invés de pretérito (modo passado)

Sei que pode parecer estranho ao primeiro momento escrever a mensagem no imperativo, pois a mudança implementada foi uma ação passada, mas escrevendo commits utilizando o imperativo nós estamos dizendo à nossa equipe o que ele fará se aplicado. No artigo de Chris Beams ele diz um pouco mais sobre a escolha do imperativo e traz uma grande notação à qual, todo subject (texto do commit) deve se enquadrar, como no seguinte caso:

> "If applied, this commit will [message]"

Em português: “Se aplicado, esse commit irá [mensagem]”. Se pensarmos no exemplo representado acima, o resultado seria:

> "If applied, this commit will change the markup", o que faz muito mais sentido do que: "If applied, this commit will changed the markup"

## O que são e como indicar as breaking changes?

Entre os tipos de commits que devem estar bem explicados estão as `BREAKING CHANGES`, ou quebra de compatibilidade. Elas ocorrem quando uma alteração feita leva à quebra na execução do código, que não funciona mais ao consultar a API do projeto seguindo uma padronização anterior.

Conforme a padronização de commits semânticos, elas devem ser comunicadas das seguintes formas:

```
type(scope): subject 

<body>
<footer>
```

- No rodapé (footer) do commit: 
O rodapé é um espaço opcional, mas é lá que uma `BREAKING CHANGE: ` deve aparecer. E ao colocá-la deve-se escrever o termo dessa forma, em caixa alta, seguido de dois pontos e espaçamento. Após a expressão, deve-se explicar o porquê de ter feito a mudança.

- Após o type/scope do commit:
Nesses casos, a BREAKING CHANGE é sinalizada apenas com um sinal de exclamação `!` imediatamente antes dos dois pontos `:`. Conforme a convenção:

```
"Se o símbolo ! for usado, BREAKING CHANGE:
PODE ser omitido da seção de rodapé
e a descrição da mensagem de commit
DEVE ser usada para descrever a BREAKING CHANGE."
```

- A sinalização de `BREAKING CHANGE` pode ser utilizada em qualquer type/scope de commit, seja ele fix, feat, chore etc.

### Relação com o SemVer — Versionamento Semântico
De forma resumida, o Versionamento Semântico (SemVer) diz respeito à padronização formal de como se documenta as versões de um software de acordo com a etapa e o objetivo de cada atualização. O formato padrão é "X.Y.Z", conforme explica o trecho a seguir do documento [Versionamento Semântico 2.0.0](https://semver.org/lang/pt-BR/):

```
Um número de versão normal DEVE ter o formato de X.Y.Z, onde X, Y, e Z são inteiros não negativos,
e NÃO DEVE conter zeros à esquerda. X é a versão Maior, Y é a versão Menor, e Z é a versão de Correção.
Cada elemento DEVE aumentar numericamente. Por exemplo: 1.9.0 -> 1.10.0 -> 1.11.0.
```

Esses números de versão recebem os nomes de `MAJOR.MINOR.PATCH`, nesta ordem.
Sobre eles, o documento aponta o seguinte:

```
Dado um número de versão MAJOR.MINOR.PATCH, incremente a:

1. versão Maior(MAJOR): quando fizer mudanças incompatíveis na API,
2. versão Menor(MINOR): quando adicionar funcionalidades mantendo compatibilidade, e
3. versão de Correção(PATCH): quando corrigir falhas mantendo compatibilidade.

Rótulos adicionais para pré-lançamento(pre-release) e metadados de construção(build)
estão disponíveis como extensão ao formato MAJOR.MINOR.PATCH.
```

Ou seja: "Commits com `BREAKING CHANGE` nas mensagens, independentemente do tipo, devem ser enviados para releases `MAJOR`."

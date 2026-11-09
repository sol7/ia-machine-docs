# Robots

Robot é o trabalho que roda fora, num Runner do projeto. Esta página é o cadastro dele. O nó Robot, no fluxo, é quem chama esse robot na hora da execução. Sem Runner online, o passo não tem onde rodar. As duas telas são de administrador.

## Para que serve

Cadastra o robot que o nó Robot executa num Runner.

## Quem vê

Só administrador.

## Onde fica

`/settings/robots`.

## O que a tela mostra

O robot do projeto e o ponto em que o fluxo chama esse robot. Cadastrar aqui deixa o robot disponível. Colocar o nó Robot no fluxo é o que faz a tarefa chamá-lo. Uma coisa sem a outra não executa: robot sem nó não entra na tarefa, nó sem robot não tem o que chamar.

## Campos

O cadastro do robot. O detalhe de cada campo desse formulário, além do próprio cadastro, não está descrito nesta página.

## O que dá para fazer

Cadastrar o robot e chamá-lo no fluxo.

## Limite atual

Quem não é administrador não vê Robots.

{% content-ref url="/referencia/nos/robot" %}
[Robot](/referencia/nos/robot)
{% endcontent-ref %}

{% content-ref url="runners.md" %}
[Runners](runners.md)
{% endcontent-ref %}

## Dúvidas comuns

**O fluxo chegou no nó Robot e nada rodou.**
O nó executa um Robot da nuvem no Runner escolhido. Sem um Runner online nesse projeto, o passo não tem onde rodar. Confira também se o robot está cadastrado nesta tela.

**Não vejo o menu.**
Robots pede administrador. O mesmo vale para Runners.

**O robot é o colaborador digital?**
Não. O colaborador digital é o agente da operação, com ficha e tarefa. O robot é o que o nó Robot manda executar numa máquina ligada ao projeto.

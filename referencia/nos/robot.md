# Robot

O Robot manda executar um robot da nuvem no Runner escolhido. O cadastro do robot fica em Robots. A máquina fica em Runners. Sem Runner online neste projeto, o passo não tem onde rodar.

## Para que serve

Executa um Robot da nuvem no Runner escolhido.

## Quem vê

Quem desenha a tarefa no editor de fluxo.

## Onde fica

Na paleta do editor, em `/task/[id]/flow`. O botão do nó é **Abrir manual do nó**.

## O que a tela mostra

O bloco no canvas e a ligação com o nó anterior e o seguinte. O manual que abre no editor, quando existe, separa visão geral, configuração, como usar, exemplos e referência. Se ainda não houver texto, a tela diz: "Ainda não há manual para este nó." Esta página não completa essas partes no lugar da tela.

## Campos

Os campos de configuração ficam no manual do nó, dentro do editor. Não estão repetidos aqui.

## O que dá para fazer

Colocar o nó no caminho que sai do Início, ligar o passo anterior e o seguinte, e abrir o manual quando ele tiver texto.

## Limite atual

Sem o manual publicado na tela, não há passo a passo de configuração nesta página.

## Dúvidas comuns

**O nó está no fluxo e não executa.**
Confira três peças: o robot cadastrado por um administrador, um Runner online neste projeto, e a versão do fluxo publicada. Sem Runner online, o passo Robot não tem onde rodar.

{% content-ref url="/operations/robots" %}
[Robots](/operations/robots)
{% endcontent-ref %}

{% content-ref url="/operations/runners" %}
[Runners](/operations/runners)
{% endcontent-ref %}

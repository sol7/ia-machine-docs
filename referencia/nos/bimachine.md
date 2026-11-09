# BIMachine

O BIMachine traz dados de uma fonte externa para o fluxo continuar com eles. Não é a DataTable do projeto. A DataTable guarda dado estruturado entre tarefas e execuções da própria plataforma.

## Para que serve

Obtém dados de fontes externas.

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

**Isto é a mesma coisa que DataTables?**
Não. DataTables é a tabela do projeto, em `/datatables`. Este nó obtém dados de fontes externas.

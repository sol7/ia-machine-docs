# Entrada de texto

A Entrada de texto entrega um texto fixo aos próximos nós. O texto não muda sozinho de uma execução para outra. Ele muda quando alguém edita o nó e publica de novo. Não é a mensagem que você digita no chat.

## Para que serve

Um texto fixo para os próximos nós.

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

**Quero um texto diferente a cada execução.**
Este nó é texto fixo. Dado que muda vem de outro passo, como HTTP, planilha, arquivo ou o que a execução já trouxe até aqui.

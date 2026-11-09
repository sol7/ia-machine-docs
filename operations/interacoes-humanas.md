# Interações humanas

## Para que serve

Fila do que o fluxo parou para uma pessoa decidir ou responder.

## Quem vê

Quem acompanha a operação. O link público é a página de quem responde sem estar na fila.

## Onde fica

`/human-interactions` e o link público `/human-interactions/link/[token]`.

## O que a tela mostra

Abas: todas, pendentes, respondidas, aprovadas, reprovadas, prazo estourado, canceladas. Lista ou grade.

{% hint style="info" %}
Quando o fluxo chega numa revisão humana, a execução pausa e abre **Revisão humana aguardando você**. O texto explica: responda para o fluxo seguir pela saída **Respondido**, ou feche e responda depois nesta tela.
{% endhint %}

O pedido traz a solicitação e o contexto configurados no fluxo. **Abrir para responder** volta para a interação. O detalhe é a decisão em si.

| Desfecho | O que acontece |
| --- | --- |
| Aprovada | A revisão foi aprovada |
| Reprovada | A revisão foi reprovada |
| Respondida | A revisão foi respondida e o fluxo segue pela saída Respondido |
| Prazo vencido | O prazo acabou e o fluxo segue pela saída Timeout |
| Cancelada | A revisão foi cancelada |

Se houver outra revisão em seguida, a tela avisa qual acabou e qual é a próxima.

## Campos

Filtros: busca, só as minhas, incluir teste, período, colaborador, responsável. Ordenação: recentes, mais antigas, prazo.

## O que dá para fazer

Filtrar a fila, abrir a decisão e responder pelo link público.

## Limite atual

A configuração do passo, no desenho da tarefa, está na Revisão humana.

{% content-ref url="/referencia/nos/revisao-humana" %}
[Revisão humana](/referencia/nos/revisao-humana)
{% endcontent-ref %}

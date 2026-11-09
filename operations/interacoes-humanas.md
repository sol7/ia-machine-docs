# Interações humanas

Quando um fluxo chega numa revisão humana, ele para e espera uma pessoa. Esta página é a fila dessa espera. Não é o histórico de conversas do Assistant. A pessoa responsável responde aqui, ou por um link público, sem precisar achar a execução no meio da Torre.

## Para que serve

Fila do que o fluxo parou para uma pessoa decidir ou responder.

## Quem vê

Quem acompanha a operação. O link público é a página de quem responde sem estar na fila. Quem recebe o link não precisa abrir o menu.

## Onde fica

`/human-interactions` e o link público `/human-interactions/link/[token]`.

## O que a tela mostra

Abas: todas, pendentes, respondidas, aprovadas, reprovadas, prazo estourado, canceladas. Lista ou grade.

A aba recorta o estado. Pendentes é o que ainda espera alguém. As outras separam o que já teve desfecho. Lista ou grade mudam a apresentação, não o conteúdo.

{% hint style="info" %}
Quando o fluxo chega numa revisão humana, a execução pausa e abre **Revisão humana aguardando você**. O texto explica: responda para o fluxo seguir pela saída **Respondido**, ou feche e responda depois nesta tela.
{% endhint %}

Fechar a pausa não cancela o pedido. Ele continua na fila até alguém responder, o prazo estourar ou o pedido ser cancelado.

O pedido traz a solicitação e o contexto configurados no fluxo. **Abrir para responder** volta para a interação. O detalhe é a decisão em si. Não é um comentário solto: é o que faz o fluxo seguir.

| Desfecho | O que acontece |
| --- | --- |
| Aprovada | A revisão foi aprovada |
| Reprovada | A revisão foi reprovada |
| Respondida | A revisão foi respondida e o fluxo segue pela saída Respondido |
| Prazo vencido | O prazo acabou e o fluxo segue pela saída Timeout |
| Cancelada | A revisão foi cancelada |

Se houver outra revisão em seguida, a tela avisa qual acabou e qual é a próxima. Uma execução cancelada ou já encerrada não cria revisão humana.

## Campos

Filtros: busca, só as minhas, incluir teste, período, colaborador, responsável. Ordenação: recentes, mais antigas, prazo.

**Só as minhas** esconde o que está com outra pessoa. **Incluir teste** mostra também o que foi gerado em teste. Sem esse filtro, o teste fica de fora e a fila parece menor do que o fluxo produziu. O prazo na ordenação ajuda a achar o que vence antes.

## O que dá para fazer

Filtrar a fila, abrir a decisão e responder pelo link público.

## Limite atual

A configuração do passo, no desenho da tarefa, está na Revisão humana. Esta página não edita o fluxo. Ela responde o que o fluxo já parou.

{% content-ref url="/referencia/nos/revisao-humana" %}
[Revisão humana](/referencia/nos/revisao-humana)
{% endcontent-ref %}

## Dúvidas comuns

**Fechei o aviso e o fluxo não continuou.**
Fechar deixa o pedido na fila. O fluxo segue pela saída Respondido quando alguém responde. Se o prazo acabar antes, ele segue pela saída Timeout.

**A pessoa que decide não tem usuário no projeto.**
Envie o link público `/human-interactions/link/[token]`. Essa página é de quem responde sem estar na fila.

**Não acho o meu pedido.**
Ligue **Só as minhas** só se ele estiver com você. Confira a aba: pendente não aparece em respondidas. Inclua teste se o fluxo rodou como teste. A busca, o período, o colaborador e o responsável também recortam a lista.

**Cancelei a execução. Devia ter nascido uma revisão?**
Não. Uma execução cancelada ou já encerrada não cria revisão humana.

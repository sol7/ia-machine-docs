# Interações humanas

**Interações humanas** é a fila do que uma execução pediu para uma pessoa decidir ou responder.

Quando o fluxo chega numa revisão humana, a execução pausa e abre **Revisão humana aguardando você**. O texto explica: responda para o fluxo seguir pela saída **Respondido**, ou feche e responda depois nesta tela.

O pedido traz a solicitação e o contexto configurados no fluxo. **Abrir para responder** volta para a interação.

## Como uma revisão termina

| Desfecho | O que acontece |
| --- | --- |
| Aprovada | A revisão foi aprovada |
| Reprovada | A revisão foi reprovada |
| Respondida | A revisão foi respondida e o fluxo segue pela saída Respondido |
| Prazo vencido | O prazo acabou e o fluxo segue pela saída Timeout |
| Cancelada | A revisão foi cancelada |

Se houver outra revisão em seguida, a tela avisa qual acabou e qual é a próxima.

A configuração desse passo, no desenho da tarefa, está em [Fluxo da tarefa](../tarefas/fluxo.md).

# Execuções

**Execuções** mostra a **Atividade do dia**: as próximas execuções, as execuções recentes e o que está em andamento.

O resumo da tela pode dizer quantas tarefas estão agendadas para hoje, em quanto tempo vem a próxima, qual foi a última e se alguma está em execução. Quando não há nada marcado para o dia, a mensagem é "Nenhuma execução agendada para hoje".

## Status

| Status | O que significa |
| --- | --- |
| Sucesso | A execução terminou |
| Falhou | A execução terminou com falha |
| Executando | A execução está em andamento |
| Aguardando | A execução espera uma condição ou uma resposta |
| Cancelado | A execução foi cancelada |
| Interrompida pelo revisor | Um revisor interrompeu a execução |
| Ignorado | O passo não rodou |

## Cancelar

Quem tem permissão pode cancelar uma execução em andamento. Durante o pedido, o botão mostra **Cancelando...**. Ao terminar, a mensagem é **Execução cancelada**.

Se o cancelamento já estiver em andamento, se a execução não for encontrada ou se você não tiver permissão, a tela explica o motivo e nada além disso é cancelado.

Uma execução cancelada ou já encerrada não cria revisão humana. O que ficou aguardando uma pessoa continua em [Interações humanas](interacoes-humanas.md).

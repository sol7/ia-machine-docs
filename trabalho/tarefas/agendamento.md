# Agendamento da tarefa

A frequência é obrigatória na criação da tarefa. As opções da tela são:

| Frequência | O que mais a tela pede | Como roda |
| --- | --- | --- |
| Diária | Hora da execução | Todo dia nesse horário |
| Semanal | Dia da semana e hora | Naquele dia da semana, nesse horário. Também existe a forma em dias úteis |
| Mensal | Dia do mês e hora | Naquele dia do mês, nesse horário |
| Intervalo Diário | Intervalo em minutos, hora início e hora fim | A cada tantos minutos, dentro dessa faixa |
| Sob Demanda | Não pede horário | Só roda quando alguém dispara |

Os textos de confirmação da própria tela são do tipo "Executa diariamente às …", "Executa toda … às …", "Executa em dias úteis às …", "Executa todo dia … às …" e "Executa a cada … min das … às …".

Na lista de tarefas, o filtro de agendamento usa os mesmos nomes: Diária, Semanal, Mensal, Intervalo e Sob demanda.

## Quando a execução anterior ainda não terminou

O campo **Quando a execução anterior ainda não terminou** escolhe o que fazer com o próximo horário.

| Opção | O que a tela explica |
| --- | --- |
| Automático (recomendado) | Com revisão humana no fluxo, cada horário vira uma execução independente. Sem revisão humana, o horário é pulado enquanto houver uma execução rodando. |
| Rodar mesmo assim: cada execução é independente | Cada horário dispara uma execução nova, mesmo com outra aguardando resposta. As revisões se acumulam para o responsável. |
| Esperar a anterior e rodar só a mais recente | Guarda um disparo e roda assim que a execução atual terminar. Os outros horários do período são descartados. |
| Pular este horário | Enquanto houver uma execução rodando ou aguardando, o horário é descartado e não roda depois. |

{% hint style="info" %}
A tarefa ativa entra na fila desses horários. Desativar a tarefa tira os próximos disparos sem apagar o cadastro.
{% endhint %}

O resultado de cada disparo aparece em Execuções.

{% content-ref url="../acompanhar/execucoes.md" %}
[Execuções](../acompanhar/execucoes.md)
{% endcontent-ref %}

# Tarefas do Copilot

## Para que serve

Tarefas que o Copilot da pessoa dispara. O texto da tela é: "Execute tarefas de forma agendada ou sempre que precisar delas."

## Quem vê

A pessoa dona do Copilot. Some sem projeto.

{% hint style="warning" %}
Sem projeto selecionado, a tela pede: "Selecione um projeto para ver as tarefas agendadas."
{% endhint %}

## Onde fica

`/chat/scheduled`.

## O que a tela mostra

Esta lista é sua. A lista **Tarefas** da operação, ligada a um colaborador digital, é outra lista.

O cartão mostra a última execução e o status, ou **Ainda não executou**, e a próxima data. Uma tarefa pode estar pausada ou concluída. Um modelo alterado pelo administrador leva a marca **Personalizada pelo administrador**.

Se ainda não houver nenhuma, a tela mostra **Nenhuma tarefa agendada ainda** e **Modelos para começar**.

## Campos

O que fazer, quando roda e o que já rodou. O campo **Duração** define até quando a tarefa continua: Permanente, Até uma data, Por N vezes ou Até atingir um objetivo.

| Opção | O que a tela explica |
| --- | --- |
| Permanente | Roda até você pausar ou excluir. |
| Até uma data | Roda até o fim do dia escolhido, no horário de Brasília, e se encerra sozinha. A data não pode estar no passado. |
| Por N vezes | Encerra depois desse número de execuções do agendamento, entre 1 e 365. Executar agora não conta. |
| Até atingir um objetivo | A cada execução o Copilot confere se o objetivo aconteceu. Quando acontece, ele avisa e encerra a tarefa. |

## O que dá para fazer

**Nova tarefa** abre **Criar com o Copilot** ou **Configurar manualmente**. As ações do cartão são **Executar agora**, **Pausar**, **Ativar**, **Editar** e excluir. Dá para buscar por nome e ordenar por **Próxima execução**, **Nome** ou **Mais recentes**.

**Criar com o Copilot** abre o chat com o pedido: "Quero agendar uma tarefa recorrente com você. Me ajude a definir o que fazer, quando e como me avisar."

**Executar agora** inicia na hora e abre a conversa. Essa execução manual não conta para o limite de vezes da duração.

## Limite atual

{% hint style="warning" %}
Um modelo pode exigir e-mail ou WhatsApp conectado. Sem o canal, ele aparece como indisponível.
{% endhint %}

{% hint style="warning" %}
Uma tarefa manual, sem frequência, não tem duração. A tela pede uma frequência para limitar o ciclo.
{% endhint %}

{% content-ref url="/operations/tarefas" %}
[Tarefas](/operations/tarefas)
{% endcontent-ref %}

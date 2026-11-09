# Execuções

## Para que serve

Mostra o que está por vir, o que está rodando e o que terminou.

## Quem vê

Quem acompanha o projeto.

## Onde fica

`/executions`. Lista ou linha do tempo.

## O que a tela mostra

A tela também se apresenta como **Atividade do dia**: as próximas execuções, as execuções recentes e o que está em andamento. O resumo pode dizer quantas tarefas estão agendadas para hoje, em quanto tempo vem a próxima, qual foi a última e se alguma está em execução.

{% hint style="info" %}
Quando não há nada marcado para o dia, a mensagem é "Nenhuma execução agendada para hoje".
{% endhint %}

| Status | O que significa |
| --- | --- |
| Sucesso | A execução terminou |
| Falhou | A execução terminou com falha |
| Executando | A execução está em andamento |
| Aguardando | A execução espera uma condição ou uma resposta |
| Cancelado | A execução foi cancelada |
| Interrompida pelo revisor | Um revisor interrompeu a execução |
| Ignorado | O passo não rodou |

## Campos

Busca, projeto, colaborador, resultado (sucesso, falha, em execução, aguardando, cancelada, interrompida), origem (agenda, manual e as outras que a tela listar) e intervalo de datas.

## O que dá para fazer

Baixar, tentar de novo e encerrar. Quem tem permissão pode cancelar uma execução em andamento. Durante o pedido, o botão mostra **Cancelando...**.

{% hint style="info" %}
Ao terminar, a mensagem é **Execução cancelada**.
{% endhint %}

## Limite atual

{% hint style="warning" %}
Se o cancelamento já estiver em andamento, se a execução não for encontrada ou se você não tiver permissão, a tela explica o motivo e nada além disso é cancelado.
{% endhint %}

Uma execução cancelada ou já encerrada não cria revisão humana.

{% content-ref url="interacoes-humanas.md" %}
[Interações humanas](interacoes-humanas.md)
{% endcontent-ref %}

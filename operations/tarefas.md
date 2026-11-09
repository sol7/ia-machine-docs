# Tarefas

## Para que serve

Organiza, agenda e acompanha o trabalho dos colaboradores digitais.

## Quem vê

Quem tem o projeto aberto.

## Onde fica

`/tasks`. Criar pede o colaborador digital e abre o fluxo novo em `/task/new?agent=`.

## O que a tela mostra

Lista ou agenda. Cada tarefa aparece como **Ativa** ou **Inativa**, com **Próxima:** e **Última:**.

{% hint style="info" %}
Se nunca rodou, o texto é **Ainda não executou**. Se a última execução não carregar, a lista continua disponível e avisa que a última execução ficou indisponível.
{% endhint %}

{% hint style="success" %}
A criação confirmada mostra "Tarefa criada com sucesso." A edição mostra "Tarefa atualizada com sucesso."
{% endhint %}

## Campos

| Campo | Regra |
| --- | --- |
| Nome | Obrigatório, no mínimo 3 caracteres |
| Descrição | Obrigatória, no mínimo 3 caracteres |
| Frequência | Obrigatória |
| Objetivo | Obrigatório, no mínimo 3 caracteres |

Filtros da lista: status (todas, ativas, inativas), colaborador digital e agenda (diária, semanal, mensal, intervalo, sob demanda).

| Frequência | O que mais a tela pede | Como roda |
| --- | --- | --- |
| Diária | Hora da execução | Todo dia nesse horário |
| Semanal | Dia da semana e hora | Naquele dia da semana, nesse horário. Também existe a forma em dias úteis |
| Mensal | Dia do mês e hora | Naquele dia do mês, nesse horário |
| Intervalo Diário | Intervalo em minutos, hora início e hora fim | A cada tantos minutos, dentro dessa faixa |
| Sob Demanda | Não pede horário | Só roda quando alguém dispara |

O campo **Quando a execução anterior ainda não terminou** escolhe Automático (recomendado), Rodar mesmo assim, Esperar a anterior e rodar só a mais recente, ou Pular este horário.

## O que dá para fazer

Buscar, filtrar, **Ativar ou desativar tarefa**, criar e abrir o editor. A lixeira do projeto guarda a exclusão.

{% hint style="info" %}
A tarefa ativa entra na fila desses horários. Desativar a tarefa tira os próximos disparos sem apagar o cadastro.
{% endhint %}

## Limite atual

{% hint style="danger" %}
A exclusão pede confirmação. Um snapshot vai para a Lixeira do projeto. A restauração recria a definição com novos identificadores. Canais, memória, versões e agendas não voltam. A tarefa só pode ser restaurada se o colaborador digital ainda existir neste projeto.
{% endhint %}

As tarefas do Copilot da pessoa ficam em Tarefas do Copilot. Não é a mesma lista.

{% content-ref url="fluxo.md" %}
[Editor de fluxo](fluxo.md)
{% endcontent-ref %}

{% content-ref url="/assistant/tarefas" %}
[Tarefas do Copilot](/assistant/tarefas)
{% endcontent-ref %}

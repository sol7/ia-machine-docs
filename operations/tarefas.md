# Tarefas

Tarefa, nesta página, é o trabalho de um colaborador digital. Ela tem nome, descrição, objetivo e uma frequência. Ativa, ela entra na fila dos horários. Inativa, o cadastro fica e os próximos disparos saem. Não é a tarefa do seu Copilot pessoal: aquela fica no Assistant e não abre este fluxo.

## Para que serve

Organiza, agenda e acompanha o trabalho dos colaboradores digitais.

## Quem vê

Quem tem o projeto aberto.

## Onde fica

`/tasks`. Criar pede o colaborador digital e abre o fluxo novo em `/task/new?agent=`. Sem escolher o colaborador, não há para quem criar a tarefa.

## O que a tela mostra

Lista ou agenda. A lista serve para achar e filtrar. A agenda serve para ver o horário. Cada tarefa aparece como **Ativa** ou **Inativa**, com **Próxima:** e **Última:**.

{% hint style="info" %}
Se nunca rodou, o texto é **Ainda não executou**. Se a última execução não carregar, a lista continua disponível e avisa que a última execução ficou indisponível.
{% endhint %}

A lista não some quando a última execução falha ao carregar. Você continua podendo abrir a tarefa. O aviso só diz que aquele dado ficou indisponível.

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

Nome e descrição identificam a tarefa na lista. O objetivo diz o resultado esperado. A frequência diz quando ela entra na fila. Os quatro são obrigatórios. A frequência ainda pede o detalhe do horário, conforme a tabela.

Filtros da lista: status (todas, ativas, inativas), colaborador digital e agenda (diária, semanal, mensal, intervalo, sob demanda).

| Frequência | O que mais a tela pede | Como roda |
| --- | --- | --- |
| Diária | Hora da execução | Todo dia nesse horário |
| Semanal | Dia da semana e hora | Naquele dia da semana, nesse horário. Também existe a forma em dias úteis |
| Mensal | Dia do mês e hora | Naquele dia do mês, nesse horário |
| Intervalo Diário | Intervalo em minutos, hora início e hora fim | A cada tantos minutos, dentro dessa faixa |
| Sob Demanda | Não pede horário | Só roda quando alguém dispara |

O campo **Quando a execução anterior ainda não terminou** escolhe o que fazer se o horário chegou e a anterior segue aberta:

* **Automático (recomendado).** A opção que a tela marca como recomendada.
* **Rodar mesmo assim.** Dispara outra mesmo com a anterior aberta.
* **Esperar a anterior e rodar só a mais recente.** Não empilha. Fica com a mais recente.
* **Pular este horário.** Este disparo não roda.

## O que dá para fazer

Buscar, filtrar, **Ativar ou desativar tarefa**, criar e abrir o editor. A lixeira do projeto guarda a exclusão.

{% hint style="info" %}
A tarefa ativa entra na fila desses horários. Desativar a tarefa tira os próximos disparos sem apagar o cadastro.
{% endhint %}

Desativar é reversível. Excluir pede confirmação e vai para a lixeira. São ações diferentes. Uma tarefa sob demanda não entra sozinha no horário: alguém dispara.

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

## Dúvidas comuns

**Criei e a próxima execução não aparece.**
Confira se a tarefa está ativa. Inativa não entra na fila. Sob demanda não tem horário: **Próxima:** não se comporta como a de uma tarefa diária. Se nunca rodou, o texto é **Ainda não executou**.

**A última execução não carrega.**
A lista continua disponível e avisa que a última execução ficou indisponível. Abra Execuções para o histórico do projeto.

**Restaurei da lixeira e o agendamento sumiu.**
A restauração recria a definição com novos identificadores. Canais, memória, versões e agendas não voltam. Se o colaborador digital não existir mais neste projeto, a tarefa nem restaura.

**Não consigo excluir o colaborador desta tarefa.**
Com tarefa ativa ligada a ele, a exclusão do colaborador pede para desativar todas as tarefas vinculadas e tentar de novo.

**Esta tela também guarda a tarefa que eu agendei para mim?**
Não. A sua fica em Tarefas do Copilot, em `/chat/scheduled`. Ela some se não houver projeto selecionado, e a mensagem de lá pede para selecionar um projeto.

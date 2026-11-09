# DataTables

## Para que serve

Tabela ligada a uma tarefa. Guarda dados estruturados para as tarefas e as execuções do projeto usarem.

{% hint style="info" %}
O texto da tela é: "Armazene e compartilhe dados estruturados entre tarefas e execuções."
{% endhint %}

## Quem vê

Quem administra os dados do projeto.

## Onde fica

`/datatables`. No editor de fluxo, o controle DataTables lista as tabelas usadas por aquele fluxo.

## O que a tela mostra

O resumo mostra quantas tabelas e quantas linhas existem. Cada linha mostra o nome, a quantidade de linhas, a visibilidade, o ciclo de vida, a expiração e a última atualização. Uma tabela persistente não expira. Uma tabela com prazo mostra a janela em horas.

## Campos

Busca por **Buscar DataTables...**. Visibilidade: pública ou privada. Permanência: persistente ou janela. **Nova DataTable** pede o nome, a visibilidade e o ciclo de vida. A descrição é opcional.

{% hint style="warning" %}
Uma DataTable privada pede uma tarefa do projeto. Sem tarefa no projeto, a tela diz para criar uma tarefa antes.
{% endhint %}

## O que dá para fazer

Buscar, criar, editar e excluir. Depois dá para ver, editar o nome, a visibilidade, o ciclo de vida e a descrição, e renomear.

{% hint style="success" %}
O botão de confirmação cria a tabela e avisa "DataTable criada."
{% endhint %}

## Limite atual

Sem tarefa no projeto, não há como criar.

{% content-ref url="tarefas.md" %}
[Tarefas](tarefas.md)
{% endcontent-ref %}

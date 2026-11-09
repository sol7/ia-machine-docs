# DataTables

**DataTables** guarda dados estruturados para as tarefas e as execuções do projeto usarem.

{% hint style="info" %}
O texto da tela é: "Armazene e compartilhe dados estruturados entre tarefas e execuções."
{% endhint %}

O resumo mostra quantas tabelas e quantas linhas existem. Dá para buscar por **Buscar DataTables...** e filtrar por:

* visibilidade: Todas, Públicas ou Privadas
* persistência: Todas, Persistentes ou Com expiração

Cada linha mostra o nome, a quantidade de linhas, a visibilidade, o ciclo de vida, a expiração e a última atualização. Uma tabela persistente não expira. Uma tabela com prazo mostra a janela em horas.

## Nova DataTable

**Nova DataTable** pede o nome, a visibilidade e o ciclo de vida. A descrição é opcional.

{% hint style="warning" %}
Uma DataTable privada pede uma tarefa do projeto. Sem tarefa no projeto, a tela diz para criar uma tarefa antes.
{% endhint %}

{% content-ref url="/trabalho/tarefas/criar" %}
[Criar uma tarefa](/trabalho/tarefas/criar)
{% endcontent-ref %}

{% hint style="success" %}
O botão de confirmação cria a tabela e avisa "DataTable criada."
{% endhint %}

Depois dá para ver, editar o nome, a visibilidade, o ciclo de vida e a descrição, renomear ou excluir.

## No fluxo

O nó **Tabela de dados**, no grupo Designers, monta uma tabela visual. A DataTable da lista é o lugar onde os dados ficam guardados para outras tarefas e execuções lerem.

{% content-ref url="/trabalho/tarefas/fluxo" %}
[Fluxo da tarefa](/trabalho/tarefas/fluxo)
{% endcontent-ref %}

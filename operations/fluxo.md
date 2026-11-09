# Editor de fluxo

## Para que serve

Desenha os passos da tarefa. Cada bloco se chama nó. O nó **Início** é o ponto de partida. Os nós seguintes se ligam a partir dele.

## Quem vê

Quem edita a tarefa do projeto.

## Onde fica

`/task/[id]/flow`.

## O que a tela mostra

O canvas, a paleta e a ligação entre nós. Cada nó tem **Abrir manual do nó**. O manual, quando existe, separa visão geral, configuração, como usar, exemplos e referência.

{% hint style="info" %}
Se ainda não houver texto, a tela diz: "Ainda não há manual para este nó."
{% endhint %}

| Controle | O que a pessoa faz |
| --- | --- |
| Configurações da tarefa | Definições (nome, objetivo, metadados). Execução (agenda, webhook, e-mail). Contrato de entrada (parâmetros e validadores). Contrato de interação. Contrato de saída. |
| Publicar | Gera a versão que passa a valer |
| Histórico de versões | Compara e recupera publicação |
| Execuções | Roda e acompanha este fluxo |
| Painel de nós | Liga e desliga a paleta |
| Dados do fluxo | Recursos de dados do fluxo |
| DataTables | Tabelas usadas por este fluxo |
| Anotação | Nota no canvas, sem executar |

Nós ativos na paleta: Início, Se, Loop, Aguardar. Raciocínio, Revisão humana, Código, Extrair arquivo. BIMachine, HTTP, Google Sheets, Google Drive, IAMachine, Robot. Anotação. Entrada de texto. Enviar e-mail, WhatsApp, Insight, Artefato, Arquivo, Saída de texto, Saída lógica.

## Campos

Os controles da tabela acima. Nome, objetivo e frequência da tarefa continuam obrigatórios na criação.

## O que dá para fazer

Ligar nós, publicar, recuperar uma versão e abrir o manual do nó quando ele existir.

## Limite atual

Switch, Filtro, Memória, Telegram e os designers ficam só no índice da Referência, sem página de uso. O manual interno de cada nó ativo não foi encontrado neste repositório.

{% content-ref url="/referencia" %}
[Referência](/referencia)
{% endcontent-ref %}

{% content-ref url="datatables.md" %}
[DataTables](datatables.md)
{% endcontent-ref %}

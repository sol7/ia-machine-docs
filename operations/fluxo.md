# Editor de fluxo

O fluxo é o desenho da tarefa. Cada bloco se chama nó. A tarefa só faz o que os nós ligados a partir do **Início** descrevem. Publicar gera a versão que passa a valer. Enquanto você só edita, a versão publicada anterior é a que a operação usa.

## Para que serve

Desenha os passos da tarefa. Cada bloco se chama nó. O nó **Início** é o ponto de partida. Os nós seguintes se ligam a partir dele.

## Quem vê

Quem edita a tarefa do projeto.

## Onde fica

`/task/[id]/flow`. A tarefa nova, depois de escolher o colaborador, abre em `/task/new?agent=`.

## O que a tela mostra

O canvas, a paleta e a ligação entre nós. O canvas é a área do desenho. A paleta é a lista de nós que dá para colocar. A ligação diz a ordem. Um nó solto, sem caminho desde o Início, não faz parte do que a tarefa executa.

Cada nó tem **Abrir manual do nó**. O manual, quando existe, separa visão geral, configuração, como usar, exemplos e referência.

{% hint style="info" %}
Se ainda não houver texto, a tela diz: "Ainda não há manual para este nó."
{% endhint %}

Quando essa frase aparece, o nó pode estar na paleta e ainda não ter o passo a passo de configuração. A Referência desta wiki explica o papel de cada nó ativo. Ela não inventa o campo que o manual não publicou.

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

Definições repetem a identidade da tarefa: nome, objetivo e metadados. Execução junta o que dispara o fluxo: agenda, webhook e e-mail. O contrato de entrada diz o que a tarefa recebe, com parâmetros e validadores. O contrato de interação diz a troca com uma pessoa. O contrato de saída diz o que a tarefa devolve.

Publicar é o que faz a versão valer. O histórico compara e recupera uma publicação. Recuperar não é desfazer um rascunho: é voltar a uma versão já publicada. Anotação fica no canvas para quem lê o desenho e não executa.

Nós ativos na paleta: Início, Se, Loop, Aguardar. Raciocínio, Revisão humana, Código, Extrair arquivo. BIMachine, HTTP, Google Sheets, Google Drive, IAMachine, Robot. Anotação. Entrada de texto. Enviar e-mail, WhatsApp, Insight, Artefato, Arquivo, Saída de texto, Saída lógica.

## Campos

Os controles da tabela acima. Nome, objetivo e frequência da tarefa continuam obrigatórios na criação.

## O que dá para fazer

Ligar nós, publicar, recuperar uma versão e abrir o manual do nó quando ele existir. O painel de nós esconde ou mostra a paleta. Dados do fluxo e DataTables entram quando o passo precisa de dado guardado, não quando o passo é só uma nota.

## Limite atual

Switch, Filtro, Memória, Telegram e os designers ficam só no índice da Referência, sem página de uso. O passo a passo de configuração de cada nó ativo, com visão geral, configuração, como usar, exemplos e referência, ainda não está publicado nesta wiki. No editor, use **Abrir manual do nó**. Se não houver texto, a tela avisa.

{% content-ref url="/referencia" %}
[Referência](/referencia)
{% endcontent-ref %}

{% content-ref url="datatables.md" %}
[DataTables](datatables.md)
{% endcontent-ref %}

## Dúvidas comuns

**Desenhei e a operação não mudou.**
Falta publicar. Publicar gera a versão que passa a valer. O histórico serve para comparar e recuperar uma publicação anterior.

**O nó está na paleta e o manual diz que não há texto.**
A frase é: "Ainda não há manual para este nó." Dá para usar o nó no desenho. O passo a passo de campo não está nesse manual. Switch, Filtro, Memória, Telegram e os designers nem têm página de uso nesta wiki.

**A anotação mudou o resultado?**
Não. Anotação não executa. É uma nota no canvas.

**Onde eu ligo a tabela que a tarefa usa?**
No controle DataTables deste fluxo. A lista geral das tabelas do projeto fica em DataTables. Sem tarefa no projeto, a tela de criar tabela pede para criar uma tarefa antes, quando a tabela é privada.

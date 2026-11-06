# Fluxo da tarefa

O fluxo é o desenho dos passos da tarefa. Cada bloco se chama nó. O nó **Início** é o ponto de partida. Os nós seguintes se ligam a partir dele.

Cada nó tem **Abrir manual do nó**. O manual, quando existe, separa visão geral, configuração, como usar, exemplos e referência. Se ainda não houver texto, a tela diz: "Ainda não há manual para este nó."

## Nós do fluxo

**Entrada e lógica**

| Nó | O que a tela descreve |
| --- | --- |
| Início | Ponto de partida do fluxo |
| Entrada de Texto | Um texto fixo para os próximos nós |
| Se | Ramifica o fluxo com base em condições |
| Switch | Direciona o fluxo entre vários ramos |
| Filtro | Filtra os itens que passam pelo fluxo |
| Loop | Percorre uma lista, um objeto ou uma quantidade fixa |
| Aguardar | Pausa o fluxo por um tempo ou até um horário |
| Memória | Guarda e recupera contexto entre etapas |
| Código | Executa um JavaScript personalizado |

**Dados e integrações**

| Nó | O que a tela descreve |
| --- | --- |
| BIMachine | Obtém dados de fontes externas |
| HTTP | Obtém dados de fontes externas |
| Arquivo | Lê e grava arquivos |
| Extrair Arquivo | Extrai texto ou linhas de um arquivo, como PDF ou CSV |
| Google Sheets | Busca dados de planilhas públicas do Google Sheets |
| Google Drive | Detecta e baixa arquivos do Google Drive |
| IAMachine | Conecta à própria plataforma |
| Robot | Executa um Robot da nuvem no Runner escolhido |

**Inteligência e saída**

| Nó | O que a tela descreve |
| --- | --- |
| Raciocínio | Processa dados e devolve um resultado estruturado |
| Insight | Gera insights a partir dos dados |
| Saída de Texto | Mostra um texto durante os testes do fluxo |
| Saída Lógica | Encerra o fluxo com um desfecho de negócio |
| Enviar E-Mail | Envia uma notificação por e-mail |
| WhatsApp | Envia uma mensagem por WhatsApp |
| Telegram | Envia mensagens pelo Telegram |
| Artefato | Cria e publica um artefato com dados do fluxo |

**Designers**

Em branco, Dashboard, Relatório executivo, Resumo em texto, Apresentação em slides, Infográfico, Tabela de dados, Cartão de alerta, Storyboard e Livro.

**Anotação** não executa um passo. Serve para desenhar uma nota no fluxo.

## Artefato no fluxo

O nó **Artefato** abre o **Studio de Artefatos**, com cinco etapas: Definição, Dados e ações, Construção, Validação e Publicação. Na definição, a tela pede o nome, o objetivo do artefato e o design system. O padrão é o design system do projeto.

A lista do projeto fica em **Orquestração e Execução**.

{% content-ref url="../artefatos.md" %}
[Artefatos do projeto](../artefatos.md)
{% endcontent-ref %}

## Revisão humana

Quando o fluxo precisa parar para uma pessoa, a configuração se chama **Configurar revisão humana**. As etapas são:

1. Tipo e responsáveis
2. Solicitação e contexto
3. Resposta e regras

**Salvar e testar** espera o fluxo chegar na revisão. A resposta de teste faz o fluxo seguir pela saída **Respondido**.

Na execução de verdade, a pausa abre **Revisão humana aguardando você**. Dá para responder ali ou fechar e responder depois em **Interações humanas**. Os desfechos possíveis são: aprovada, reprovada, respondida, prazo vencido (o fluxo segue pela saída Timeout) ou cancelada.

O acompanhamento desses pedidos está em [Interações humanas](../acompanhar/interacoes-humanas.md).

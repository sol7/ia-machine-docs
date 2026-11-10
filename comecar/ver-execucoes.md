---
icon: list-check
---

# Ver o histórico de execuções

A página **Execuções** registra todas as vezes que seus colaboradores digitais rodaram tarefas. Cada linha mostra o resultado técnico, logs e saídas de uma execução.

## Passo a passo

{% stepper %}

{% step %}
### Abrir a página de Execuções

1. No menu lateral, expanda a seção **ORQUESTRAÇÃO E EXECUÇÃO**
2. Clique em **Execuções**

A página carrega mostrando a lista de execuções mais recentes.

<figure><img src=".gitbook/assets/06-execucoes-lista.png" alt="Lista de execuções"><figcaption>Histórico de todas as tarefas executadas</figcaption></figure>
{% endstep %}

{% step %}
### Interpretar a lista

Cada execução exibe:

* **Nome da tarefa**: o que foi executado
* **Versão**: qual versão da tarefa rodou
* **Colaborador**: quem executou (nome e avatar)
* **Status**: Concluído, Erro, Em execução, Aguardando, Cancelado, Interrompida pelo revisor
* **Canal**: origem da execução (Chat, API, agendamento)
* **Data e hora**: quando aconteceu
* **Ícones de ação**: visualizar detalhes, baixar logs
{% endstep %}

{% step %}
### Filtrar execuções

No topo da página, use os filtros para refinar a busca:

* **Abas de status**: Todos, Sucesso, Erro, Em execução, Aguardando, Cancelado, Interrompida pelo revisor
* **Colaborador**: filtre por nome de colaborador digital
* **Resultado técnico**: sucesso, falha, timeout, etc.
* **Origem**: Chat, API, agendamento
* **Período**: últimos 7 dias, 30 dias, ou intervalo personalizado
* **Busca**: pesquise por nome de tarefa ou execução

Os números em cada aba mostram quantas execuções há em cada status.
{% endstep %}

{% step %}
### Visualizar ou alternar layout

Acima da lista, há dois botões:

* **Lista**: exibe em linhas (padrão)
* **Linha do tempo**: mostra em ordem cronológica visual

Use "Linha do tempo" para ver padrões de execução ao longo do dia ou da semana.
{% endstep %}

{% step %}
### Navegar entre páginas

No rodapé da lista, use:

* **Itens por página**: escolha quantas execuções mostrar (10, 20, 50)
* **Setas**: avance ou volte entre páginas
* **Número da página**: veja em qual página está

A contagem "Exibindo 1-10 de X execuções" informa o total de registros.
{% endstep %}

{% endstepper %}

## Quando usar

* **Investigar falhas**: filtre por "Erro" para ver o que deu errado
* **Auditar execuções**: consulte quem rodou o quê e quando
* **Monitorar progresso**: acompanhe execuções "Em execução" ou "Aguardando"
* **Baixar logs**: clique no ícone de download para exportar detalhes técnicos

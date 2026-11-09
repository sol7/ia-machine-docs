# Torre de Controle

A Torre é o painel da operação no projeto aberto. Ela não cria o colaborador nem desenha a tarefa. Ela mostra o período, deixa filtrar por quem executa e reúne os blocos em que a empresa lê o que está acontecendo. Quando você precisa falar com um colaborador a partir daqui, a barra de lançamento abre o chat dele com o texto já digitado.

## Para que serve

Reúne a visão do que a operação está fazendo, inclusive as execuções do dia.

## Quem vê

Quem tem o projeto aberto.

## Onde fica

`/central`.

## O que a tela mostra

Período: Hoje, Semana, Mês. Filtro por colaborador digital. Indicador ao vivo com a hora da última atualização. A hora diz quando os números foram atualizados. Se o período é Hoje e o filtro é um colaborador, os blocos falam desse recorte, não da empresa inteira em qualquer data.

| Bloco | O que a tela reúne |
| --- | --- |
| Visão executiva | Impacto, equipe de colaboradores digitais, inteligência e decisões, ritmo de trabalho, diário da equipe e indicadores de operação. Cada ponto do diário da equipe é uma execução. |
| Visão tática | Conversa acoplada ao colaborador escolhido e as abas da visão tática. |
| Barra de lançamento | Texto e voz que abrem o chat principal daquele colaborador. |
| Insights | Tipo, colaborador, abrir detalhe e excluir. |

A visão executiva é o retrato do recorte. A visão tática desce ao colaborador escolhido e mostra a conversa dele. O insight é um item com tipo e colaborador: dá para abrir o detalhe ou excluir. Excluir tira o insight da Torre. Não apaga a execução que o originou.

## Campos

O período e o colaborador digital do filtro.

## O que dá para fazer

Trocar o período, filtrar por colaborador, abrir um insight e lançar o chat daquele colaborador. Para um painel em tela cheia, use o Modo TV. Ele não está no menu lateral.

<table data-view="cards"><thead><tr><th>A partir da Torre</th><th data-card-target data-type="content-ref">Abrir</th></tr></thead><tbody><tr><td><strong>Modo TV</strong><br>Tela cheia para painel. Não está no menu lateral.</td><td><a href="modo-tv.md">modo-tv</a></td></tr><tr><td><strong>Atividades</strong><br>O que a operação fez no período.</td><td><a href="atividades.md">atividades</a></td></tr><tr><td><strong>Execuções</strong><br>Lista ou linha do tempo do que rodou.</td><td><a href="execucoes.md">execucoes</a></td></tr><tr><td><strong>Interações humanas</strong><br>Fila do que o fluxo parou para uma pessoa decidir.</td><td><a href="interacoes-humanas.md">interacoes-humanas</a></td></tr></tbody></table>

## Limite atual

O detalhe interno de cada bloco da visão executiva, além dos nomes desta página, não está descrito aqui. O que está descrito é o recorte, o filtro, o indicador ao vivo e o que cada bloco reúne.

## Dúvidas comuns

**O diário da equipe é um texto escrito por alguém?**
Cada ponto do diário da equipe é uma execução. Para ver status, origem e o que ainda vai rodar, abra Execuções.

**Mandei um texto pela barra e ele já foi para o cliente?**
A barra abre o chat principal daquele colaborador com a mensagem digitada. O envio para fora continua dependendo do que o chat pedir. No Copilot pessoal, nada sai sem o ok de quem conversa.

**Quero deixar a Torre numa TV da sala.**
Abra o Modo TV, em `/central/tv`. Ele alterna cenas em tela cheia. Não há um item com esse nome no menu lateral.

**O número não bate com o que eu vi de manhã.**
Olhe a hora da última atualização no indicador ao vivo e o período selecionado. Hoje, Semana e Mês não mostram o mesmo recorte.

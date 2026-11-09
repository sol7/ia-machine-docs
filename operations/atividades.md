# Atividades

Atividades é a leitura do que a operação já fez. Serve para olhar para trás: o que terminou bem e o que falhou no dia. O que ainda está rodando, e o que ainda vai rodar hoje, não mora aqui. Isso fica em Execuções. A vista das duas telas alterna de propósito, para você não misturar histórico com fila.

## Para que serve

Mostra o que a operação fez no período.

## Quem vê

Quem acompanha o projeto.

## Onde fica

`/central/activities`. A vista alterna com Execuções.

## O que a tela mostra

O trabalho realizado pelos colaboradores digitais e pelo Copilot.

{% hint style="info" %}
A lista serve para ler o que já aconteceu. O estado de cada execução em andamento, e o que ainda vai rodar hoje, fica em Execuções.
{% endhint %}

| Status | O que significa |
| --- | --- |
| Sucesso | Terminou bem |
| Falha | Terminou com falha |

Não há, nesta lista, os status de espera da execução. Aguardando, executando e cancelado são leitura de Execuções. Aqui o trabalho já fechou em sucesso ou falha.

## Campos

Busca e dia. O dia recorta o que você quer reler. A busca acha o item dentro desse recorte.

## O que dá para fazer

Buscar, ver o dia, ver falhas com nova tentativa, exportar e atualizar.

Falhas com nova tentativa mostra o que não terminou bem e pode ser disparado de novo. Exportar tira uma cópia do que a lista está mostrando. Atualizar busca o que entrou desde que a tela abriu.

## Limite atual

A vista do que está rodando fica em Execuções.

{% content-ref url="execucoes.md" %}
[Execuções](execucoes.md)
{% endcontent-ref %}

## Dúvidas comuns

**A atividade de agora não aparece.**
Se ainda está em andamento, ela está em Execuções, não aqui. Atividades só lê o que já aconteceu.

**Qual a diferença para o diário da Torre?**
Cada ponto do diário da equipe, na Torre, é uma execução. Atividades é a lista do trabalho já realizado, com sucesso ou falha, busca, dia, exportação e nova tentativa.

**A nova tentativa conta como outra execução?**
Ela dispara de novo o que falhou. O rastro de o que está rodando passa a ser lido em Execuções.

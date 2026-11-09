# Colaboradores digitais

Colaborador digital é o agente da operação neste projeto. Ele tem nome, descrição e um estado ativo ou inativo. Não é o Meu Copilot de ninguém. A lista serve para achar, criar, abrir e, quando for o caso, excluir. A ficha guarda quem ele é. A rotina mostra o que ele tem para fazer. A tarefa é o trabalho que aponta para ele.

## Para que serve

Lista os agentes da operação do projeto, para visualizar e gerenciar.

## Quem vê

Quem tem projeto e não é Viewer. Sem projeto, ou com o papel Viewer, a entrada some. Não é uma falha da busca.

## Onde fica

`/agents`.

## O que a tela mostra

Cada colaborador tem nome, descrição e um estado ativo ou inativo. A busca se chama **Buscar colaboradores digitais...**. Ela procura no nome e na descrição. Inativo continua na lista: o cadastro existe e não está em uso. O Meu Copilot pessoal não entra aqui, mesmo que você tenha acabado de criá-lo.

{% hint style="success" %}
A criação concluída mostra "Colaborador digital criado com sucesso."
{% endhint %}

## Campos

A busca pelo nome e pela descrição.

## O que dá para fazer

Buscar, criar, abrir e excluir. A exclusão vai para a lixeira.

{% hint style="danger" %}
A exclusão pede confirmação. Um snapshot vai para a Lixeira do projeto. Canais, memória, versões e agendas não voltam.
{% endhint %}

{% hint style="warning" %}
Não dá para excluir enquanto houver tarefa ativa ligada a ele. A mensagem pede para desativar todas as tarefas vinculadas e tentar de novo.
{% endhint %}

O snapshot da lixeira recupera o cadastro, não a vida operacional dele. Canais, memória, versões e agendas ficam de fora da volta. Por isso, antes de excluir, desative as tarefas se a mensagem pedir, e saiba que reconectar e-mail, WhatsApp e agenda é um trabalho novo.

<table data-view="cards"><thead><tr><th>Onde continuar</th><th data-card-target data-type="content-ref">Abrir</th></tr></thead><tbody><tr><td><strong>Ficha do colaborador</strong><br>Quatro grupos. A pessoa preenche seção por seção.</td><td><a href="ficha.md">ficha</a></td></tr><tr><td><strong>Rotina do colaborador</strong><br>Cabeçalho, rotinas na linha do tempo, tarefas avulsas e calendário.</td><td><a href="rotina.md">rotina</a></td></tr><tr><td><strong>Tarefas</strong><br>Na lista de tarefas dá para filtrar pelo colaborador que executa o trabalho.</td><td><a href="tarefas.md">tarefas</a></td></tr></tbody></table>

## Limite atual

Some para Viewer e para quem não tem projeto. O Meu Copilot pessoal não aparece nesta lista. Criar a partir de um modelo continua em breve: o botão aparece como Aguardando lançamento.

## Dúvidas comuns

**Criei o Meu Copilot e ele não está nesta lista.**
O Meu Copilot é seu e privado. Esta lista é dos agentes da operação. Abra a ficha e use Começar do zero para criar um colaborador digital.

**A exclusão não conclui.**
Há tarefa ativa ligada a ele. Desative todas as tarefas vinculadas e tente de novo. Desativar a tarefa tira os próximos disparos sem apagar o cadastro da tarefa.

**Restauro da lixeira e o WhatsApp não volta.**
O retorno recria o cadastro. Canais, memória, versões e agendas não voltam. E-mail e WhatsApp precisam ser configurados de novo na ficha.

**Sou Viewer e a equipe some.**
Viewer não vê Colaboradores digitais. Peça outro papel se o seu trabalho for cadastrar ou abrir esses agentes.

# Auditoria

Auditoria é o registro do que foi feito no projeto: quem agiu, sobre o quê e de onde a ação partiu. Ela não desfaz a ação e não substitui Execuções. Execuções dizem se uma tarefa rodou. Auditoria diz qual ação ficou registrada. Sem projeto, a entrada some. Sem ser administrador, ela também some.

## Para que serve

Mostra quem fez o quê no projeto.

{% hint style="info" %}
Dentro de um projeto, o texto é: "Acompanhe as ações registradas no projeto."
{% endhint %}

## Quem vê

Só administrador, e só com projeto. Sem projeto, Auditoria some.

## Onde fica

`/audit`.

## O que a tela mostra

A lista das ações registradas. A **Origem** indica de onde a ação partiu. O alvo é o registro afetado. Quando esse registro já foi excluído, a linha continua e marca a exclusão, para o rastro não desaparecer junto com o cadastro.

{% hint style="warning" %}
Quando o registro já foi excluído, a lista marca como excluída.
{% endhint %}

## Campos

**Evento.** Todos os eventos, ou um tipo específico. **Projeto.** Todos os projetos, ou o projeto aberto. **Usuário.** **Alvo.** O registro afetado. O alvo pode ser uma tarefa, um colaborador digital, um projeto, um membro, uma sessão, um artefato, um perfil de geração ou um design system.

Use o evento para o tipo de ação, o usuário para a pessoa, e o alvo para o cadastro. Os três juntos respondem "quem fez o quê sobre qual registro".

## O que dá para fazer

Filtrar a lista.

## Limite atual

Quem não é administrador não vê Auditoria. A lista não restaura o que foi excluído. Restaurar colaborador ou tarefa é a lixeira do próprio cadastro, com as perdas já descritas naquelas páginas.

## Dúvidas comuns

**Excluí uma tarefa e quero ver se ficou registro.**
Filtre pelo alvo. O alvo pode ser uma tarefa. Se o registro já foi excluído, a lista marca como excluída. A marcação não recria a tarefa. A lixeira é que guarda o snapshot, e canais, memória, versões e agendas não voltam.

**A entrada não está no menu.**
Falta ser administrador ou falta o projeto. As duas condições são obrigatórias. Sem projeto, Auditoria some junto com Colaboradores digitais, Copilots e as tarefas do menu Assistant.

**Isto mostra se a execução de hoje falhou?**
O estado da execução está em Execuções: sucesso, falhou, executando, aguardando, cancelado, interrompida pelo revisor ou ignorado. Auditoria é o registro da ação, com origem, evento, usuário e alvo.

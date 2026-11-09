# Revisão humana

A Revisão humana para o fluxo quando uma pessoa precisa decidir ou responder. A execução fica aguardando. A fila dessa espera é Interações humanas. Sem este nó, o fluxo não abre essa fila. Sem alguém responder, o caminho de Respondido não segue.

## Para que serve

Para o fluxo quando uma pessoa precisa decidir ou responder. A fila de Interações humanas depende deste nó.

## Quem vê

Quem desenha a tarefa, e a pessoa responsável pela resposta. Quem está fora da fila pode responder pelo link público, se receber o endereço.

## Onde fica

Na paleta do editor de fluxo, em `/task/[id]/flow`. A fila fica em `/human-interactions`. O link de quem responde sem estar na fila é `/human-interactions/link/[token]`.

## O que a tela mostra

Tipos: aprovação, decisão, solicitação de informação, revisão, execução manual, baixa confiança, risco, esclarecimento.

O tipo diz a razão da pausa. Aprovação e decisão pedem um julgamento. Solicitação de informação pede um dado. Revisão pede leitura. Execução manual pede que a pessoa faça o passo. Baixa confiança, risco e esclarecimento marcam por que o fluxo não seguiu sozinho.

Na execução, a pausa abre **Revisão humana aguardando você**. O texto explica: responda para o fluxo seguir pela saída **Respondido**, ou feche e responda depois na fila. Fechar não cancela.

## Campos

Um responsável, o gestor do colaborador ou um usuário do projeto, e o prazo da resposta. O gestor da ficha só pode ser Expert ou Administrador do projeto.

O responsável é uma pessoa, não as duas ao mesmo tempo. Gestor do colaborador usa quem está na ficha. Usuário do projeto escolhe alguém do projeto. O prazo é o tempo dessa resposta. Se ele acaba, o fluxo segue pela saída Timeout e o desfecho na fila é Prazo vencido.

## O que dá para fazer

Configurar o passo e responder na fila, ou pelo link público. Os desfechos da fila são Aprovada, Reprovada, Respondida, Prazo vencido e Cancelada.

## Limite atual

O manual que abre no editor, quando existe, separa visão geral, configuração, como usar, exemplos e referência. Se ainda não houver texto, a tela diz: "Ainda não há manual para este nó." Os tipos e os dois campos acima são o que esta página já pode explicar. O restante do formulário não está completado aqui.

{% content-ref url="/operations/interacoes-humanas" %}
[Interações humanas](/operations/interacoes-humanas)
{% endcontent-ref %}

## Dúvidas comuns

**Fechei o aviso. O fluxo continuou?**
Não pela saída Respondido. O pedido fica na fila. Responder é o que segue por Respondido. O prazo, se acabar antes, segue por Timeout.

**Posso colocar duas pessoas como responsáveis?**
O campo é um responsável: o gestor do colaborador ou um usuário do projeto.

**A execução foi cancelada. Cadê a revisão?**
Uma execução cancelada ou já encerrada não cria revisão humana.

**O gestor que eu queria não aparece.**
Na ficha, o gestor da revisão humana só pode ser Expert ou Administrador do projeto.

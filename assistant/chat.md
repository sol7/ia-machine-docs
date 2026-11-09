# Meu Copilot no chat

O Chat é a tela em que o pedido vira conversa. Você escolhe com quem fala, escreve o que precisa e acompanha o que foi respondido. Nada é enviado para fora, por e-mail ou WhatsApp, sem o seu ok. A mesma tela também abre quando a Torre manda você continuar com um colaborador.

## Para que serve

O Chat é onde o Copilot trabalha com a pessoa. Dá para falar com o Meu Copilot ou com um colaborador digital, anexar arquivo, abrir voz ao vivo e continuar uma conversa.

## Quem vê

Só essa pessoa conversa com o Meu Copilot. A tela marca **Só você conversa com ele**. A conversa com um colaborador digital é outra conversa, com outro destinatário.

## Onde fica

`/chat` e `/agent/[id]/chat/[chatId]`. É a tela inicial depois do login. A barra da Torre de Controle também abre um chat já com a mensagem digitada, no chat principal daquele colaborador.

## O que a tela mostra

A tela inicial cumprimenta pelo horário e apresenta o texto "Seu agente no dia a dia: consulta dados, interpreta informações, produz conteúdos e executa tarefas no seu tom."

**Nova interação** abre uma conversa. O campo pede "Escreva sua solicitação ou aperte / para atalhos rápidos." A conversa precisa de um destinatário. O Copilot da pessoa aparece como **Meu Copilot**. Sem destinatário, não há para quem enviar o texto.

{% hint style="warning" %}
Se nenhum colaborador digital estiver escolhido, o envio fica bloqueado com a mensagem "Escolha um colaborador digital para poder enviar."
{% endhint %}

**Canais do seu Copilot** mostra E-mail e WhatsApp como **Conectado**, **Não conectado** ou **Recebimento incompleto**. Canal não conectado não impede o chat em texto. Ele impede o que depende daquele canal. Recebimento incompleto, no e-mail, significa que falta o servidor de entrada: o envio pode existir, mas a caixa do Copilot não recebe.

**Progresso de hoje** conta Respondidas, Decisões, Prazos feitos, Dispensadas e Pendentes. É o resumo do que passou por você hoje, não a lista de execuções da operação.

{% hint style="info" %}
Quando a fila zera, a tela mostra **Fila zerada**.
{% endhint %}

## Campos

O texto da solicitação e o destinatário. Dá para anexar arquivo. Atalhos de **Ideias para começar** entram pelo botão **Usar**.

## O que dá para fazer

Continuar uma conversa, anexar arquivo, abrir voz ao vivo e usar um atalho de **Ideias para começar**.

{% hint style="info" %}
Mostra um rascunho e espera você mandar antes de qualquer envio.
{% endhint %}

O rascunho é a proteção do envio. O Copilot pode preparar o texto. Quem dispara é você. O mesmo vale para o e-mail e para o WhatsApp: o canal conectado não manda mensagem sozinho.

<table data-view="cards"><thead><tr><th>Onde continuar</th><th data-card-target data-type="content-ref">Abrir</th></tr></thead><tbody><tr><td><strong>E-mail</strong><br>O e-mail do Copilot lê a sua caixa e envia em seu nome só quando você pede no chat.</td><td><a href="email.md">email</a></td></tr><tr><td><strong>WhatsApp</strong><br>O WhatsApp do Copilot envia mensagens pelo seu número quando você pede no chat.</td><td><a href="whatsapp.md">whatsapp</a></td></tr><tr><td><strong>Voz</strong><br>A voz do Copilot serve para respostas em áudio e para a Voz ao Vivo.</td><td><a href="voz.md">voz</a></td></tr><tr><td><strong>Tarefas do Copilot</strong><br>Tarefas que o Copilot da pessoa dispara.</td><td><a href="tarefas.md">tarefas</a></td></tr><tr><td><strong>Artefatos do chat</strong><br>Meus artefatos e Compartilhado comigo.</td><td><a href="artefatos.md">artefatos</a></td></tr></tbody></table>

## Limite atual

Nada sai sem o ok da pessoa. A voz ao vivo usa a voz configurada em Meu Copilot. Se esse passo foi pulado, o chat em texto segue sem ela.

## Dúvidas comuns

**Escrevi e o envio não sai.**
A conversa está sem destinatário. Escolha o Meu Copilot ou um colaborador digital. A mensagem "Escolha um colaborador digital para poder enviar." aparece nesse bloqueio.

**Falei com o Meu Copilot. O administrador consegue ler?**
Não. A tela marca que só você conversa com ele. A conversa com um colaborador digital da operação é outra.

**Pedi um e-mail no chat e nada foi enviado.**
O Copilot mostra um rascunho e espera você mandar. Conectar a caixa não autoriza envio sozinho. Se o canal está como Não conectado ou Recebimento incompleto, resolva o e-mail antes de esperar a caixa funcionar.

**A Torre me trouxe para cá com um texto pronto.**
A barra de lançamento da Torre abre este chat com a mensagem já digitada, no colaborador que você escolheu lá. Você ainda revisa antes de enviar.

**Onde fica a conversa de ontem?**
No menu, em Interações. Dá para buscar, filtrar pelo projeto da conversa e agrupar por período. Não é uma tela separada do chat.

# Runners

**Runners** lista as instalações do Runner vinculadas a este projeto. A tela fica em Infraestrutura e aparece para quem administra.

O texto da tela é: "Instalações do Runner vinculadas a este projeto."

{% hint style="warning" %}
Sem nenhum, a mensagem é: "Nenhum Runner vinculado ainda. Vincule pelo aplicativo desktop após o login."
{% endhint %}

Cada Runner mostra:

* **Dispositivo**
* **Versão.** Se houver versão nova, a lista marca **Atualização disponível**.
* **Status.** Online ou Offline. O menu avisa **Há Runner offline** quando algum está fora.
* **Último contato**

**Editar Runner** altera o nome. O nome é obrigatório e tem no máximo 120 caracteres. A confirmação é **Runner atualizado**.

{% hint style="danger" %}
Remover tira o vínculo do projeto. A confirmação é **Runner removido**.
{% endhint %}

O nó **Robot**, no fluxo de uma tarefa, executa um Robot da nuvem no Runner escolhido.

{% hint style="warning" %}
Sem um Runner online nesse projeto, esse passo não tem onde rodar.
{% endhint %}

{% content-ref url="/trabalho/tarefas/fluxo" %}
[Fluxo da tarefa](/trabalho/tarefas/fluxo)
{% endcontent-ref %}

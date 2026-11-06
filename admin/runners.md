# Runners

**Runners** lista as instalações do Runner vinculadas a este projeto. A tela fica em Infraestrutura e aparece para quem administra.

O texto da tela é: "Instalações do Runner vinculadas a este projeto." Sem nenhum, a mensagem é: "Nenhum Runner vinculado ainda. Vincule pelo aplicativo desktop após o login."

Cada Runner mostra:

* **Dispositivo**
* **Versão.** Se houver versão nova, a lista marca **Atualização disponível**.
* **Status.** Online ou Offline. O menu avisa **Há Runner offline** quando algum está fora.
* **Último contato**

**Editar Runner** altera o nome. O nome é obrigatório e tem no máximo 120 caracteres. A confirmação é **Runner atualizado**.

Remover tira o vínculo do projeto. A confirmação é **Runner removido**.

O nó **Robot**, no fluxo de uma tarefa, executa um Robot da nuvem no Runner escolhido. Sem um Runner online nesse projeto, esse passo não tem onde rodar.

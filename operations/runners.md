# Runners

## Para que serve

Lista a máquina que executa o robot neste projeto. O texto da tela é: "Instalações do Runner vinculadas a este projeto."

## Quem vê

Só administrador.

## Onde fica

`/settings/runners`.

## O que a tela mostra

Cada Runner mostra dispositivo, versão, status e último contato. Se houver versão nova, a lista marca **Atualização disponível**. O status é Online ou Offline.

{% hint style="warning" %}
O menu avisa **Há Runner offline** quando algum está fora. Sem nenhum, a mensagem é: "Nenhum Runner vinculado ainda. Vincule pelo aplicativo desktop após o login."
{% endhint %}

## Campos

Cadastro, status e atualização. **Editar Runner** altera o nome. O nome é obrigatório e tem no máximo 120 caracteres. A confirmação é **Runner atualizado**.

## O que dá para fazer

Cadastrar, atualizar e remover o vínculo.

## Limite atual

{% hint style="danger" %}
Remover tira o vínculo do projeto. A confirmação é **Runner removido**.
{% endhint %}

{% hint style="warning" %}
Sem um Runner online nesse projeto, o passo Robot não tem onde rodar.
{% endhint %}

Quem não é administrador não vê Runners.

{% content-ref url="robots.md" %}
[Robots](robots.md)
{% endcontent-ref %}

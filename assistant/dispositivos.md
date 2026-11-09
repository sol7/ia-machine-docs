# Dispositivos

Dispositivo é um aparelho ligado à sua conta, hoje o IAMachine One: um painel de parede, sempre ligado. O aparelho mostra um código. Você registra esse código aqui. A mesma página vale para o Assistant e para o Operations. Não cadastre duas vezes.

## Para que serve

Registra e gerencia os aparelhos ligados à conta. A descrição da tela é: "Registre e gerencie os aparelhos ligados à sua conta." Vale para Assistant e Operations.

## Quem vê

A pessoa dona da conta.

## Onde fica

`/devices`. A mesma página aparece nos dois ambientes.

## O que a tela mostra

Estados: nenhum dispositivo, lista, erro ao carregar. A lista vazia não é erro. Erro ao carregar é a tela que não conseguiu trazer os aparelhos. A lista é o cadastro que já existe.

{% hint style="info" %}
Sem aparelho, a tela mostra **Nenhum dispositivo registrado** e explica: ligue o aparelho, anote o código que aparece na tela dele e registre aqui.
{% endhint %}

| Estado | O que significa |
| --- | --- |
| Pareamento em curso | O registro ainda não terminou |
| Aguardando o aparelho | O código foi aceito e o aparelho ainda não confirmou |
| Pareado | O aparelho está ligado à conta |
| Revogado | O acesso foi encerrado |

Os detalhes mostram a última sincronização, o último contato, o identificador do aparelho e, quando o aparelho informa, a localização. **Ainda não deu sinal** aparece quando não houve contato. Pareado com "ainda não deu sinal" significa que o vínculo existe, mas o aparelho não falou com a conta desde então.

## Campos

1. **Registrar um dispositivo**.
2. Tipo. Hoje a opção é **IAMachine One**, descrita como "Painel de parede, sempre ligado."
3. **Código do dispositivo**. O aparelho mostra o código. A pessoa registra esse código aqui.
4. **Como você vai chamá-lo**. O exemplo da tela é "Recepção, Sala de reunião…". O nome é só o rótulo. Dá para alterá-lo depois sem parear de novo.

{% hint style="warning" %}
O código vale por cinco minutos. Se venceu, peça um novo no próprio aparelho.
{% endhint %}

O projeto do tablet é o escolhido no aparelho. No registro feito pelo navegador, é o projeto aberto aqui. Se a pessoa não tiver acesso ao projeto escolhido no tablet, a tela pede para alguém com acesso confirmar. Sem essa confirmação, o código certo não completa o vínculo.

## O que dá para fazer

Registrar, alterar o nome e revogar.

{% hint style="info" %}
O sucesso aparece como **Dispositivo registrado.** A confirmação do nome é **Nome atualizado.**
{% endhint %}

## Limite atual

{% hint style="danger" %}
**Revogar** encerra o acesso. O aparelho precisa ser registrado de novo. A confirmação pede para digitar o nome do dispositivo. A mensagem final é **Dispositivo revogado.**
{% endhint %}

## Dúvidas comuns

**O código não é aceito.**
Ele dura cinco minutos. Peça outro no aparelho e registre na hora. Confira também se você tem acesso ao projeto que o tablet está usando. Se não tiver, alguém com acesso precisa confirmar.

**Ficou em Aguardando o aparelho.**
O código já foi aceito nesta tela. Falta o aparelho confirmar. Não é a mesma coisa que Pareado, e não é revogação.

**Revoguei sem querer.**
O acesso encerrou. É preciso registrar de novo, com um código novo. Alterar o nome não desfaz a revogação.

**Preciso cadastrar o painel também na Torre?**
Não. A página de `/devices` é única e aparece nas duas abas.

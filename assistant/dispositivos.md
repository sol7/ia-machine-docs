# Dispositivos

## Para que serve

Registra e gerencia os aparelhos ligados à conta. A descrição da tela é: "Registre e gerencie os aparelhos ligados à sua conta." Vale para Assistant e Operations.

## Quem vê

A pessoa dona da conta.

## Onde fica

`/devices`. A mesma página aparece nos dois ambientes.

## O que a tela mostra

Estados: nenhum dispositivo, lista, erro ao carregar.

{% hint style="info" %}
Sem aparelho, a tela mostra **Nenhum dispositivo registrado** e explica: ligue o aparelho, anote o código que aparece na tela dele e registre aqui.
{% endhint %}

| Estado | O que significa |
| --- | --- |
| Pareamento em curso | O registro ainda não terminou |
| Aguardando o aparelho | O código foi aceito e o aparelho ainda não confirmou |
| Pareado | O aparelho está ligado à conta |
| Revogado | O acesso foi encerrado |

Os detalhes mostram a última sincronização, o último contato, o identificador do aparelho e, quando o aparelho informa, a localização. **Ainda não deu sinal** aparece quando não houve contato.

## Campos

1. **Registrar um dispositivo**.
2. Tipo. Hoje a opção é **IAMachine One**, descrita como "Painel de parede, sempre ligado."
3. **Código do dispositivo**. O aparelho mostra o código. A pessoa registra esse código aqui.
4. **Como você vai chamá-lo**. O exemplo da tela é "Recepção, Sala de reunião…".

{% hint style="warning" %}
O código vale por cinco minutos. Se venceu, peça um novo no próprio aparelho.
{% endhint %}

O projeto do tablet é o escolhido no aparelho. No registro feito pelo navegador, é o projeto aberto aqui. Se a pessoa não tiver acesso ao projeto escolhido no tablet, a tela pede para alguém com acesso confirmar.

## O que dá para fazer

Registrar, alterar o nome e revogar.

{% hint style="info" %}
O sucesso aparece como **Dispositivo registrado.** A confirmação do nome é **Nome atualizado.**
{% endhint %}

## Limite atual

{% hint style="danger" %}
**Revogar** encerra o acesso. O aparelho precisa ser registrado de novo. A confirmação pede para digitar o nome do dispositivo. A mensagem final é **Dispositivo revogado.**
{% endhint %}

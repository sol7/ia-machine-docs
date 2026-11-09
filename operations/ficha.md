# Ficha do colaborador

A ficha é o cadastro do colaborador digital. Ela responde quem ele é, para que existe, como fala, o que pode usar e como a empresa mede o trabalho. Você preenche seção por seção. O que aparece desligado fica visível e ainda não tem uso: não espere efeito ao mexer nesses campos.

## Para que serve

Cria ou edita o colaborador digital. O título da criação é **Criar novo colaborador digital**.

## Quem vê

Quem pode abrir Colaboradores digitais. Viewer e quem está sem projeto não chegam aqui.

## Onde fica

`/agents/create` e `/agent/[id]/edit`.

## O que a tela mostra

Dois caminhos na criação. **Criar Colaborador Digital Manual** está disponível. O botão é **Começar do zero**. Esse caminho abre o Canvas vazio para este projeto.

{% hint style="warning" %}
**Criar via Modelo.** Ainda **Em breve**. O botão aparece como **Aguardando lançamento**.
{% endhint %}

Não há passo a passo de modelo. O botão existe para mostrar que o caminho ainda não abre.

O Canvas tem quatro grupos. O botão final é **Criar colaborador digital** na criação e **Salvar alterações** na edição. Salvar grava as seções que estão em uso. Se e-mail ou WhatsApp estiverem em uso, a ficha não salva com essa seção pela metade.

{% hint style="success" %}
A confirmação de criação é "Colaborador digital criado com sucesso."
{% endhint %}

{% hint style="warning" %}
Se a seção de e-mail ou de WhatsApp estiver em uso, os campos obrigatórios daquela seção precisam estar completos antes de salvar.
{% endhint %}

## Campos

Documente só o que salva. O que aparece desligado fica na linha do limite, sem passo.

**Visão geral.** Identifica o colaborador. Avatar, nome, gênero da persona (masculino, feminino ou neutro), descrição / propósito, gestor responsável por decisões de revisão humana, setor / especialização, ambiente (desenvolvimento, homologação ou produção) e status ativo. O nome e a descrição pedem no mínimo 3 caracteres. A foto aceita PNG ou JPG. Os botões da foto são **Enviar**, **Alterar** e **Remover**. O status **Colaborador digital ativo** liga ou desliga o cadastro. Inativo permanece na lista e sai de uso.

O ambiente separa desenvolvimento, homologação e produção. Use produção quando o colaborador já atende a operação. Desenvolvimento e homologação servem para o cadastro que ainda não deve ser o da operação real.

O gestor da revisão humana só pode ser Expert ou Administrador do projeto. É essa pessoa que pode ser responsável quando o fluxo para numa revisão. Um usuário comum do projeto não entra nessa lista.

**Objetivo principal.** Diz a razão do colaborador existir: objetivo, problema que resolve e valor que gera. Sem isso, a ficha tem um nome e não tem um encargo.

**Personalidade e tom.** Diz como ele responde. Estilo cognitivo, estilo de comunicação, ritmo, emoção, voz e limite de tokens. A voz pode ser do catálogo ou uma clonagem da própria, com velocidade e idioma. O botão da clonagem é **Criar clone**. A gravação pedida é de cerca de 10 a 15 segundos. A voz clonada só fica vinculada depois que a pessoa salva o colaborador. Fechar sem salvar não grava a voz.

| Estilo cognitivo | O que a tela descreve |
| --- | --- |
| Analítico | Estrutura o raciocínio em etapas, cita dados e evita achismos. |
| Intuitivo | Confia em padrões e impressões rápidas. |
| Estratégico | Olha o quadro geral e escolhe caminhos. |
| Direto | Vai direto ao ponto. |
| Reflexivo | Pondera e evita conclusão precipitada. |
| Disruptivo | Questiona premissas e propõe outro caminho. |

Estilo de comunicação: Formal, Informal, Didático, Conciso, Inspirador ou Assertivo. Ritmo: Imediato, Equilibrado ou Cuidadoso. Emoção: Empático, Neutro, Engajado, Motivacional ou Sério. **Tamanho máx. da resposta (tokens)** fica entre 2 e 4096. O limite corta o tamanho da resposta. Não muda o estilo.

{% hint style="info" %}
Essa voz não é a voz do seu Copilot pessoal.
{% endhint %}

**Regras e diretrizes.** O que ele deve obedecer: diretrizes gerais, políticas e a ação de fallback quando não souber. O fallback é o comportamento quando ele não tem resposta, em vez de inventar uma.

**Fontes de conhecimento.** De onde ele lê: documentos e fontes externas. É o material deste colaborador, não a caixa do seu Copilot.

**Natureza.** Quem pode encontrar este colaborador. Público ou privado. Acesso: todos, equipes, usuários ou externo.

**Conectores.** Conectores e capacidades ligados a este colaborador. Apontam para o catálogo do projeto. Ligar aqui não autoriza o seu Meu Copilot, e autorizar o seu Copilot não liga a ferramenta a este colaborador.

**E-mail.** Conexão, recebimento e envio deste colaborador. É o canal dele, não o e-mail do seu perfil.

**WhatsApp.** Conexão, regras, usuários autorizados e teste de envio. O teste existe para conferir o envio antes de a operação depender dele.

**Métricas e indicadores.** KPIs e como a coleta acontece. Diz o que a empresa olha para saber se o colaborador está cumprindo o objetivo.

**Critérios de sucesso.** Resultados esperados, prazo e responsável. É a meta, separada do KPI.

**Notas.** Notas gerais, para o que não coube nas seções anteriores.

## O que dá para fazer

Começar do zero, preencher as seções que salvam e gravar. Na edição, o botão passa a ser Salvar alterações. Foto, voz e canais podem ser ajustados depois, desde que e-mail e WhatsApp em uso estejam completos no momento de salvar.

<table data-view="cards"><thead><tr><th>Voz</th><th data-card-target data-type="content-ref">Abrir</th></tr></thead><tbody><tr><td><strong>Voz do Meu Copilot</strong><br>A voz deste colaborador não é a voz do seu Copilot pessoal.</td><td><a href="/assistant/voz">voz</a></td></tr><tr><td><strong>Revisão humana</strong><br>O gestor desta ficha é quem pode ser responsável pela revisão.</td><td><a href="/referencia/nos/revisao-humana">revisao-humana</a></td></tr></tbody></table>

## Limite atual

Área e versão aparecem desligados. Casos de uso aparecem desligados. Conhecimentos internos e sistemas aparecem desligados. Público interno e público externo aparecem desligados. Aparece, ainda sem uso.

**Criar via Modelo** continua **Em breve**.

## Dúvidas comuns

**O campo está na tela e não consigo usar.**
Área, versão, casos de uso, conhecimentos internos, sistemas, público interno e público externo aparecem desligados. Não há passo de uso. O que vale é o que esta página descreve nas seções que salvam.

**Salvar falhou depois que liguei o e-mail.**
A seção está em uso e falta campo obrigatório dela. Complete conexão, recebimento e envio, ou deixe de usar a seção, antes de salvar. O mesmo vale para o WhatsApp.

**Clonei a voz e ela sumiu.**
A voz clonada só fica vinculada depois que você salva o colaborador. E ela não é a voz do seu Copilot pessoal. Trocar a voz do seu Copilot não altera esta ficha.

**Quem eu coloco como gestor?**
Só Expert ou Administrador do projeto. Essa pessoa é a responsável possível quando uma revisão humana pedir o gestor do colaborador.

**Começar do zero apaga um colaborador que já existe?**
Não. Esse botão é da criação. Editar um existente abre `/agent/[id]/edit` e termina em Salvar alterações. Excluir é outra ação, na lista, e vai para a lixeira.

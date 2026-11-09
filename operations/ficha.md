# Ficha do colaborador

## Para que serve

Cria ou edita o colaborador digital. O título da criação é **Criar novo colaborador digital**.

## Quem vê

Quem pode abrir Colaboradores digitais.

## Onde fica

`/agents/create` e `/agent/[id]/edit`.

## O que a tela mostra

Dois caminhos na criação. **Criar Colaborador Digital Manual** está disponível. O botão é **Começar do zero**.

{% hint style="warning" %}
**Criar via Modelo.** Ainda **Em breve**. O botão aparece como **Aguardando lançamento**.
{% endhint %}

O Canvas tem quatro grupos. O botão final é **Criar colaborador digital** na criação e **Salvar alterações** na edição.

{% hint style="success" %}
A confirmação de criação é "Colaborador digital criado com sucesso."
{% endhint %}

{% hint style="warning" %}
Se a seção de e-mail ou de WhatsApp estiver em uso, os campos obrigatórios daquela seção precisam estar completos antes de salvar.
{% endhint %}

## Campos

Documente só o que salva. O que aparece desligado fica na linha do limite, sem passo.

**Visão geral.** Avatar, nome, gênero da persona (masculino, feminino ou neutro), descrição / propósito, gestor responsável por decisões de revisão humana, setor / especialização, ambiente (desenvolvimento, homologação ou produção) e status ativo. O nome e a descrição pedem no mínimo 3 caracteres. A foto aceita PNG ou JPG. Os botões da foto são **Enviar**, **Alterar** e **Remover**. O status **Colaborador digital ativo** liga ou desliga o cadastro.

O gestor da revisão humana só pode ser Expert ou Administrador do projeto.

**Objetivo principal.** Objetivo, problema que resolve e valor que gera.

**Personalidade e tom.** Estilo cognitivo, estilo de comunicação, ritmo, emoção, voz e limite de tokens. A voz pode ser do catálogo ou uma clonagem da própria, com velocidade e idioma. O botão da clonagem é **Criar clone**. A gravação pedida é de cerca de 10 a 15 segundos. A voz clonada só fica vinculada depois que a pessoa salva o colaborador.

| Estilo cognitivo | O que a tela descreve |
| --- | --- |
| Analítico | Estrutura o raciocínio em etapas, cita dados e evita achismos. |
| Intuitivo | Confia em padrões e impressões rápidas. |
| Estratégico | Olha o quadro geral e escolhe caminhos. |
| Direto | Vai direto ao ponto. |
| Reflexivo | Pondera e evita conclusão precipitada. |
| Disruptivo | Questiona premissas e propõe outro caminho. |

Estilo de comunicação: Formal, Informal, Didático, Conciso, Inspirador ou Assertivo. Ritmo: Imediato, Equilibrado ou Cuidadoso. Emoção: Empático, Neutro, Engajado, Motivacional ou Sério. **Tamanho máx. da resposta (tokens)** fica entre 2 e 4096.

{% hint style="info" %}
Essa voz não é a voz do seu Copilot pessoal.
{% endhint %}

**Regras e diretrizes.** Diretrizes gerais, políticas e a ação de fallback quando não souber.

**Fontes de conhecimento.** Documentos e fontes externas.

**Natureza.** Público ou privado. Acesso: todos, equipes, usuários ou externo.

**Conectores.** Conectores e capacidades ligados a este colaborador.

**E-mail.** Conexão, recebimento e envio.

**WhatsApp.** Conexão, regras, usuários autorizados e teste de envio.

**Métricas e indicadores.** KPIs e como a coleta acontece.

**Critérios de sucesso.** Resultados esperados, prazo e responsável.

**Notas.** Notas gerais.

## O que dá para fazer

Começar do zero, preencher as seções que salvam e gravar.

<table data-view="cards"><thead><tr><th>Voz</th><th data-card-target data-type="content-ref">Abrir</th></tr></thead><tbody><tr><td><strong>Voz do Meu Copilot</strong><br>A voz deste colaborador não é a voz do seu Copilot pessoal.</td><td><a href="/assistant/voz">voz</a></td></tr><tr><td><strong>Revisão humana</strong><br>O gestor desta ficha é quem pode ser responsável pela revisão.</td><td><a href="/referencia/nos/revisao-humana">revisao-humana</a></td></tr></tbody></table>

## Limite atual

Área e versão aparecem desligados. Casos de uso aparecem desligados. Conhecimentos internos e sistemas aparecem desligados. Público interno e público externo aparecem desligados. Aparece, ainda sem uso.

**Criar via Modelo** continua **Em breve**.

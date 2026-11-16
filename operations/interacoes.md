# Interações

Interações reúne as conversas de todos os usuários do projeto com os colaboradores digitais. O administrador da plataforma consulta o que foi dito. A conversa abre em somente leitura.

## Para que serve

Ver as conversas do projeto com os colaboradores digitais, de todos os usuários.

## Quem vê

Só o administrador da plataforma, e só com um projeto selecionado. Sem projeto, a entrada some do menu. Quem administra só o projeto não vê esta lista.

## Onde fica

`/operations/interactions`. A conversa aberta fica em `/operations/interactions/[id]`. No menu do IA Operations, a entrada **Interações** está no grupo Orquestração e Execução.

## O que a tela mostra

O título é **Interações**. O texto diz **Conversas de todos os usuários do projeto com os colaboradores digitais**.

A lista traz **Usuário**, **Colaborador digital**, **Canal**, **Início da conversa**, **Mensagens**, **Última mensagem** e **Ações**. O usuário mostra o nome e, quando existe, o e-mail. Mais de uma pessoa na mesma conversa aparece como o nome e um **+** com a quantidade. O colaborador digital mostra o nome e, quando existe, o setor. O início traz um trecho da conversa e a data.

{% hint style="info" %}
Sem conversa no recorte, a tela diz **Nenhuma interação encontrada.**
{% endhint %}

Sem projeto selecionado, a tela diz **Selecione um projeto para ver as interações.** Sem acesso, diz **Você não tem acesso a esta consulta.** Se a lista não carrega, diz **Não foi possível carregar as interações.** e oferece **Tentar de novo**.

## Campos

**Colaborador digital** e **Usuário** começam em **Todos**. **Canal** oferece **Chat**, **E-mail** e **WhatsApp**. Clicar de novo no canal escolhido volta para todos.

**Período** começa em **Últimos 7 dias**. Também há **Últimos 30 dias**, **Todo o período** e **Personalizado**. No personalizado, **De** e **Até** marcam as datas. Se a data inicial vier depois da final, a tela diz **A data inicial precisa ser anterior ou igual à data final.**

A busca pede **Buscar no texto das conversas...**

## O que dá para fazer

Filtrar, buscar e abrir uma conversa. A linha e **Ações** abrem a mesma conversa. O aviso começa com **Somente leitura** e diz que você está vendo a interação daquela pessoa com aquele colaborador digital. Em seguida: **Esta abertura fica registrada na Auditoria.** **Voltar para a lista** retorna para `/operations/interactions`. O cabeçalho da conversa também traz **Interações**.

Se a conversa não existir neste projeto, a tela diz **Esta interação não está disponível neste projeto.** Se não abrir, diz **Não foi possível abrir esta interação.**

<table data-view="cards"><thead><tr><th>Outra lista</th><th data-card-target data-type="content-ref">Abrir</th></tr></thead><tbody><tr><td><strong>Interações humanas</strong><br>Fila do que o fluxo parou para uma pessoa decidir ou responder.</td><td><a href="interacoes-humanas.md">interacoes-humanas.md</a></td></tr><tr><td><strong>Interações do Assistant</strong><br>Achar uma conversa já feita no Assistant.</td><td><a href="/assistant/interacoes">interacoes</a></td></tr><tr><td><strong>Auditoria</strong><br>Mostra quem fez o quê no projeto.</td><td><a href="auditoria.md">auditoria.md</a></td></tr></tbody></table>

## Limite atual

A consulta é do administrador da plataforma, com projeto selecionado. A conversa aberta não recebe resposta. A abertura fica registrada na Auditoria.

## Dúvidas comuns

**Não acho Interações no menu de Operations.**
A entrada aparece para o administrador da plataforma, com um projeto selecionado. Sem projeto, ela some.

**Esta lista é a de Interações humanas?**
Interações humanas é a fila do que o fluxo parou para uma pessoa decidir. Esta tela mostra as conversas dos usuários com os colaboradores digitais.

**Dá para responder por aqui?**
A conversa abre com o aviso **Somente leitura**.

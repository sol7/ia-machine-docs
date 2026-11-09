# Usuários

Usuários são as pessoas do projeto e o papel de cada uma. O papel decide o que a pessoa vê. Viewer não vê Colaboradores digitais. Quem não é administrador não vê esta tela, nem Conectores, Runners, Robots, Auditoria, Conta, Projetos e Chaves. Convidar serve para quem ainda não está no projeto. Criar serve para cadastrar a pessoa.

## Para que serve

Lista as pessoas do projeto e o papel de cada uma. A tela também se apresenta como **Gerenciar Usuários** e **Gerencie os usuários do projeto**.

## Quem vê

Só administrador.

## Onde fica

`/settings/users`.

## O que a tela mostra

Os **Usuários Cadastrados** e quantos foram encontrados. A busca é **Buscar por nome ou e-mail...**. Dá para filtrar por perfil e limpar os filtros. Limpar filtros devolve a lista inteira quando a busca apertou demais o recorte.

{% hint style="info" %}
A busca sem resultado mostra **Nenhum usuário encontrado**.
{% endhint %}

## Campos

**Novo Usuário** ou **Criar Usuário** abre o formulário "Preencha as informações para criar um novo usuário."

* **Nome Completo.** Mínimo de 3 caracteres.
* **Telefone.** Com DDD.
* **Perfil.** A opção de administrador se chama **Administrador**.
* **Idioma.** Português (Brasil), Inglês (EUA), Espanhol ou Português (Portugal). O idioma é o da pessoa, não o da conta inteira.
* **Fuso Horário.**
* **Usuário Habilitado.** Desligado, o cadastro existe e o acesso não segue habilitado.
* **Cargo** e **Setor**, quando o cadastro do projeto usa esses campos. Se o projeto não usa, os campos não entram no formulário.
* **Papel no projeto.** É o que liga a pessoa a este projeto. O perfil Administrador é outra escolha, a da conta de administrador.

## O que dá para fazer

Criar, convidar, editar, visualizar e excluir. **Convidar Usuário** envia o acesso para quem ainda não está no projeto. **Visualizar usuário** abre as informações somente para leitura. **Editar Usuário** altera os mesmos dados.

{% hint style="success" %}
A criação confirmada mostra "Usuário criado com sucesso." **Atualizar Usuário** confirma "Usuário atualizado com sucesso."
{% endhint %}

## Limite atual

{% hint style="danger" %}
A exclusão confirma "Usuário excluído com sucesso."
{% endhint %}

Quem não é administrador não vê Usuários.

## Dúvidas comuns

**A pessoa não vê Colaboradores digitais.**
Se o papel é Viewer, essa entrada some. Papel no projeto e perfil Administrador não são o mesmo campo. Ajuste o papel se ela precisa abrir a força de trabalho.

**O telefone do Meu Copilot não muda no passo Quem sou eu.**
Lá a dica é: "Para mudar, edite seu cadastro." O telefone com DDD deste formulário é o cadastro do usuário.

**Convidei e a pessoa não aparece como eu esperava.**
Convidar envia o acesso para quem ainda não está no projeto. Criar preenche o formulário de um usuário novo. Visualizar só lê. A busca sem resultado mostra **Nenhum usuário encontrado**: confira nome ou e-mail antes de criar de novo.

**Excluir tira a pessoa da Auditoria?**
A exclusão do usuário confirma "Usuário excluído com sucesso." Na Auditoria, quando o registro já foi excluído, a lista marca como excluída. O rastro da ação não é apagado por esta confirmação.

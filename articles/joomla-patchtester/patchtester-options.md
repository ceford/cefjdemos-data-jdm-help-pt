<!-- Filename: Help4.x:Components_Patch_Tester_Options / Display title: Opções do Testador de Patch  -->

## Descrição

O *Joomla! Patch Tester* é usado por Testadores para verificar se os patches de código produzidos por Desenvolvedores realmente fazem o que deveriam fazer sem efeitos colaterais indesejados. A página de *Opções* é utilizada para configurar a conexão com o Github.

### Elementos Comuns

Alguns elementos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Guia de Permissões](jdocmanual?article=help/common-elements/edit-permissions).

Mais Informações: [Guia para Iniciantes em Testes de Bugs no Joomla](https://brian.teeman.net/joomla/873-a-dummies-guide-to-joomla-bug-testing)

## Como Acessar

- Selecione **Componentes → Testador de Patches** no menu do Administrador.
  - Selecione o botão *Opções* na Barra de Ferramentas.

## Captura de tela

![Formulário de opções do Patchtester](../../../pt/images/joomla-patchtester/patchtester-options-github-repository-tab.png)

## Campos do Formulário

### Aba do Repositório GitHub

- **Repositório GitHub** O padrão é `Joomla! CMS`. Use-o.

### Aba de Autenticação do GitHub

Você precisa de uma conta no GitHub e um Token do GitHub. Tudo gratuito - veja os detalhes na aba de Autenticação do GitHub.

![Opções do Patchtester aba de autenticação do github](../../../pt/images/joomla-patchtester/patchtester-options-github-authentication-tab.png)

- **Método de Autenticação do GitHub** Escolha o método Token. O método de
  Credenciais não funcionará a partir de setembro de 2020.
- **Token do GitHub** Cole o Token obtido do GitHub.

### Aba de Configurações do Servidor CI

Essas configurações são usadas para testes automatizados. Use os padrões para
testes manuais.

![Opções do Patchtester aba de configurações do servidor ci do github](../../../pt/images/joomla-patchtester/patchtester-options-ci-server-settings-tab.png)

- **Endereço do Servidor CI** Padrão: `https://ci.joomla.org`
- **Alternar Integração CI** Padrão: Desligado

*Traduzido por openai.com*


<!-- Filename: Help4.x:Menu_Item:_Login_Form / Display title: Formulário de Login   -->

## Descrição

O tipo de item de menu **Formulário de Login** é usado para criar uma página contendo um
formulário de login.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba de Detalhes](jdocmanual?article=help/menu-items-common/menu-item-details).
* [A Aba Tipo de Link](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [A Aba de Exibição de Página](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [A Aba de Metadados](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [A Aba de Associações](jdocmanual?article=help/common-elements/edit-associations).
* [A Aba de Atribuição de Módulos](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Como Acessar

Para criar um novo item de menu **Formulário de Login**:

- Selecione **Menus → \[nome do menu\]** no menu do Administrador
  (por exemplo, **Menus → Menu Principal**). Em seguida...
  - Selecione o botão Novo na Barra de Ferramentas. Depois...
  - Selecione o botão Selecionar Tipo de Item de Menu.
  - Na caixa de diálogo modal, selecione o item Usuários para abrir uma lista e, em seguida, selecione o item **Formulário de Login**.

Para editar um item de menu Formulário de Login existente:

- Selecione seu Título na lista *Menus: Itens*.

## Captura de Tela

![Aba de detalhes do formulário de login](../../../pt/images/menu-items/users-login-form-details-tab.png)

## Campos do Formulário

### Aba Opções

![Aba de detalhes do formulário de login](../../../pt/images/menu-items/users-login-form-options-tab.png)

#### Painel de Login

- **Escolher Tipo de Redirecionamento de Login** Isso pode ser um *Item de Menu* ou uma *URL Interna*. Os campos a seguir mudam dependendo da configuração deste parâmetro. Para um site multilíngue, *Item de Menu* é recomendado.
  - **Redirecionamento de Login do Item de Menu** Selecione ou crie um item de menu para a página para a qual redirecionar após um login bem-sucedido. Se nenhum item de menu for selecionado, os usuários serão redirecionados para seu perfil após o login.
  - **Redirecionamento de Login** Selecione uma URL interna para redirecionar após o login.
- **Descrição de Login** Mostrar ou ocultar a descrição de login.
- **Texto da Descrição de Login** Insira um texto para exibir na página de login.
- **Imagem de Login** Selecione ou carregue uma imagem para exibir na página de login.
- **Descrição da Imagem (Texto Alternativo)** Necessário para leitores de tela para fins de acessibilidade.
- **Sem Descrição** Uma caixa de seleção para selecionar se a imagem é puramente decorativa e não requer explicação.

#### Painel de Logout

Este painel utiliza os mesmos títulos de campo para controlar o processo de logout.

## Dicas

- A **URL de Login e Logout** pode ser usada para enviar um usuário para uma página específica criada para fornecer algum feedback ao usuário. Por exemplo, uma página intitulada *Você está agora Conectado* com algumas informações gerais. O uso de um Módulo de Usuário para mostrar links para Atualizar Perfil de Usuário, Visualizar Perfil de Usuário e outras funções do Usuário poderiam ser mostradas nesta página, aprimorando a experiência do usuário no site.

*Traduzido por openai.com*


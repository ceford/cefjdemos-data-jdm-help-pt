<!-- Filename: Help4.x:Menu_Item:_Create_Article / Display title: Criar Artigo -->

## Descrição

O item de menu *Criar Artigo* permite que os usuários enviem um artigo através da interface do Site. Normalmente, isso está disponível apenas para usuários que tenham feito login no Frontend do site. Os usuários devem ter permissão para criar artigos.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba Detalhes](jdocmanual?article=help/menu-items-common/menu-item-details).
* [A Aba Tipo de Link](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [A Aba de Exibição da Página](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [A Aba de Metadados](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [A Aba de Associações](jdocmanual?article=help/common-elements/edit-associations).
* [A Aba de Atribuição de Módulo](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Como Acessar

Selecione **Menus → \[nome do menu\]** no menu do Administrador.

Para adicionar um Item de Menu:

1. Selecione o botão **Novo** na Barra de Ferramentas.
2. Selecione o botão **Selecionar** do *Tipo de Item de Menu*.
3. Selecione o item **Artigos** no diálogo pop-up.
4. Selecione o item **Criar Artigo**.

Para editar um Item de Menu:

- Selecione um **Título** da lista

## Captura de Tela

![Item de Menu Artigos Criar Aba de Detalhes do Artigo](../../../pt/images/menu-items/articles-create-article-details-tab.png)

## Campos do Formulário

- **Título** O título que será exibido para este item de menu.
- **Alias** O nome interno do item de menu. Normalmente, você pode deixar
  este campo em branco e o Joomla preencherá com um valor padrão: Título em letras minúsculas
  e com traços em vez de espaços.

### Detalhes

#### Painel Esquerdo

- **Tipo de Item de Menu** O Tipo de Item de Menu selecionado quando este item de menu
  foi criado. Este pode ser um dos tipos de item de menu principais ou um tipo de item de menu
  fornecido por uma extensão instalada.
- **Link** O link gerado pelo sistema para este item de menu. Este campo
  não pode ser alterado e é apenas para informação.
- **Janela de Destino** Selecione na lista suspensa.
- **Estilo do Template** Selecione na lista suspensa.

#### Painel Direito

- **Menu** Mostra em qual menu o link aparecerá.

### Opções

![Aba de detalhes dos artigos do item de menu Criar Artigo](../../../pt/images/menu-items/articles-create-article-options-tab.png)

- **Categoria Específica**
  - *Sim* Os artigos serão atribuídos à categoria especificada. O usuário
    não poderá selecionar uma categoria.
  - *Não* O usuário pode selecionar a categoria na caixa de listagem. Somente
    categorias para as quais o usuário tenha permissão de *Criar* serão exibidas.
- **Redirecionamento após Envio/Cancelamento** Selecione a página para a qual o usuário será
  redirecionado após um envio de artigo bem-sucedido.
- **Redirecionamento Personalizado no Cancelamento**
  - *Sim* Defina uma página para redirecionar quando o usuário cancelar o envio do artigo.
  - *Não* Quando o usuário cancelar o envio do artigo, ele será redirecionado para
    a página de *Redirecionamento após Envio/Cancelamento*.

## Exemplo de Captura de Tela do Frontend

Esta captura de tela mostra o template de Frontend do núcleo do Joomla, **Cassiopeia**, com todas as opções de Layout de Edição definidas como 'Ocultar'.

![articles-create-article-frontend.png](../../../en/images/menu-items/articles-create-article-frontend.png)

## Dicas

Um usuário não autorizado normalmente receberá um erro ao selecionar un item de menu *Criar Artigo*. Por essa razão, é prática comum dar ao item de menu um Nível de Acesso de Visualização que só pode ser visto por usuários autorizados a adicionar artigos.

*Traduzido por openai.com*


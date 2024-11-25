<!-- Filename: Help4.x:Menu_Item:_List_All_News_Feed_Categories / Display title: Listar Todas as Categorias do Feed de Notícias -->

## Descrição

O tipo de item de menu **Listar Todas as Categorias em uma Árvore de Categorias de Feeds de Notícias** é usado para mostrar uma lista de todas as Categorias de Feeds de Notícias RSS. As categorias são exibidas em uma lista hierárquica. Dependendo das opções selecionadas para este layout, pode-se selecionar um título de categoria para mostrar os Feeds de Notícias nessa categoria.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Guia de Detalhes](jdocmanual?article=help/menu-items-common/menu-item-details).
* [A Guia de Categoria](jdocmanual?article=help/menu-items-common/menu-item-category).
* [A Guia de Layouts de Lista](jdocmanual?article=help/menu-items-common/menu-item-list-layouts).
* [A Guia de Tipo de Link](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [A Guia de Exibição de Página](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [A Guia de Metadados](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [A Guia de Associações](jdocmanual?article=help/common-elements/edit-associations).
* [A Guia de Atribuição de Módulo](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Como Acessar

Para criar um novo item de menu Listar Todas as Categorias em uma Árvore de Categoria de Feed de Notícias:

- Selecione **Menus → \[nome do menu\]** no menu do Administrador
  (por exemplo, **Menus → Menu Principal**). Em seguida...
  - Selecione o botão Novo na Barra de Ferramentas. Em seguida...
  - Selecione o botão Selecionar Tipo de Item de Menu.
  - Na caixa de diálogo modal, selecione o item Feeds de Notícias para abrir uma lista e,
    em seguida, selecione o item **Listar Todas as Categorias de Feed de Notícias**.

Para editar um item de menu Listar Todas as Categorias de Feeds de Notícias existente:

- Selecione seu Título na lista de Itens: Menus.

## Captura de Tela

![Lista de Itens de Menu de todas as Categorias do Feed de Notícias na aba de detalhes](../../../pt/images/menu-items/news-feeds-list-all-categories-details-tab.png)

## Campos do Formulário

### Aba Categorias

![Lista de Itens do Menu todas as Categorias do Feed de Notícias aba de categorias](../../../pt/images/menu-items/news-feeds-list-all-categories-tree-categories-tab.png)

- **Descrição da Categoria de Nível Superior** Mostrar ou ocultar a descrição da categoria de nível superior. Note que essa descrição pode ser substituída para este layout inserindo uma *Descrição Alternativa*.
- **Descrição Alternativa** Se você inserir algum texto neste campo, ele substituirá a Descrição da Categoria de Nível Superior, se houver uma. Se a opção Descrição do Nível Superior estiver configurada como *Mostrar*, esta descrição será exibida em vez da descrição normal da categoria.
- **Níveis de Subcategorias** O número de níveis de subcategorias a serem exibidos no layout. Selecione *Todos* para mostrar todos os níveis na hierarquia de subcategorias.
- **Categorias Vazias** Mostrar ou ocultar as categorias que não contêm itens de conteúdo ou subcategorias.
- **Descrições de Subcategorias** Mostrar ou ocultar a descrição da categoria de subcategorias.
- **\# Feeds na Categoria** Mostrar ou ocultar o número de Feeds de Notícias em uma Categoria.

### Aba Opções de Exibição de Feed

![Lista de Itens do Menu todas as Categorias do Feed de Notícias aba de categorias](../../../pt/images/menu-items/news-feeds-list-all-categories-tree-feed-display-options-tab.png)

- **Imagem do Feed** Mostrar ou ocultar a imagem dos Feeds de Notícias.
- **Descrição do Feed** Mostrar ou ocultar as descrições dos Feeds de Notícias.
- **Conteúdo do Feed** Mostrar ou ocultar o conteúdo dos Feeds de Notícias.
- **Contagem de Caracteres** Número de caracteres a serem exibidos se o Conteúdo do Feed dos Feeds de Notícias estiver configurado para ser exibido.

## Dicas

- As categorias podem ser *aninhadas* em níveis, similar a pastas em um disco rígido. Em teoria, não há limite absoluto para o número de níveis que você pode ter. No entanto, como questão prática, é recomendado manter os níveis no mínimo. O layout Mostrar Todas as Categorias pode não funcionar corretamente se o número de níveis mostrados for maior que cinco.
- Se você configurar os títulos das categorias como vinculáveis, o usuário poderá navegar até a categoria. Se houver um item de menu pré-existente para esta categoria (por exemplo, um item de menu Lista de Categorias), então as opções desse item de menu controlarão a exibição dessa página. Caso contrário, as opções definidas para o item de menu atual Mostrar Todas as Categorias controlarão a exibição da página.
- Você pode definir a opção de vincular a uma lista em dois lugares.
  - Em *Feed de Notícias: Opções*, você pode definir o valor padrão para todas as categorias.
  - Em *Categoria: Editar* para uma Categoria de Feeds de Notícias, você pode definir um valor para uma categoria específica. Se isso for definido, ele substituirá o valor padrão.


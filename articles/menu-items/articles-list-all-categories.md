<!-- Filename: Help4.x:Menu_Item:_List_All_Categories / Display title: Listar Todas as Categorias -->

## Descrição

O tipo de item de menu *Listar Todas as Categorias em uma Árvore de Categorias de Artigo* é usado para mostrar Categorias em uma lista hierárquica. Dependendo das opções selecionadas para este layout, você pode clicar em um Título de categoria para mostrar os artigos naquela categoria.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba de Detalhes](jdocmanual?article=help/menu-items-common/menu-item-details).
* [A Aba de Categoria](jdocmanual?article=help/menu-items-common/menu-item-category).
* [A Aba de Layout do Blog](jdocmanual?article=help/menu-items-common/menu-item-blog-layout).
* [A Aba de Layouts de Lista](jdocmanual?article=help/menu-items-common/menu-item-list-layouts).
* [A Aba de Opções](jdocmanual?article=help/menu-items-common/menu-item-article-options).
* [A Aba de Integração](jdocmanual?article=help/menu-items-common/menu-item-integration).
* [A Aba de Tipo de Link](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [A Aba de Exibição da Página](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [A Aba de Metadados](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [A Aba de Associações](jdocmanual?article=help/common-elements/edit-associations).
* [A Aba de Atribuição de Módulo](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Como Acessar

Selecione **Menus → \[nome do menu\]** no menu do Administrador.

Para adicionar um Item de Menu:

1.  Selecione o botão **Novo** na Barra de Ferramentas.
2.  Selecione o botão **Selecionar** Tipo de Item do Menu.
3.  Selecione o item **Artigos**.
4.  Selecione o item **Listar Todas as Categorias em uma Árvore de Categoria de Artigo**.

Para editar um Item de Menu:

- selecione um **Título** da lista

## Captura de Tela

![Item de Menu Artigos Listar Todas as Categorias aba de detalhes](../../../pt/images/menu-items/articles-list-all-categories-details-tab.png)

## Campos do Formulário

- **Título** O título que será exibido para este item de menu.
- **Apelido** O nome interno do item de menu. Normalmente, você pode deixar este campo em branco e o Joomla preencherá com um valor padrão, o título em letras minúsculas e com traços no lugar de espaços.

### Aba Detalhes

#### Painel Esquerdo

- **Tipo de Item de Menu** O tipo de item de menu selecionado quando este item de menu foi criado. Pode ser um dos tipos de itens de menu principais ou um tipo de item de menu fornecido por uma extensão instalada.
- **Selecione a Categoria de Nível Superior**
  - *Raiz* Incluir todas as categorias de artigos.
  - Caso contrário, selecione a categoria de nível superior desejada. Todas as categorias filhas da categoria selecionada aparecerão no item de menu.
- **Link** O link gerado pelo sistema para este item de menu. Este campo não pode ser alterado e serve apenas para informação.
- **Janela de Destino** Selecione na lista suspensa.
- **Estilo de Template** Selecione na lista suspensa.

#### Painel Direito

- **Menu** Mostra em qual menu o link aparecerá.

### Aba Categorias

![Lista de Artigos de Item de Menu Todas as Categorias aba de categorias](../../../pt/images/menu-items/articles-list-all-categories-categories-tab.png)

- **Descrição da Categoria de Nível Superior** Mostrar a descrição para a categoria de nível superior.
- **Descrição Alternativa** Insira uma descrição para substituir a descrição da categoria para o item de menu.
- **Níveis de Subcategoria** Controlar quantos níveis de subcategorias exibir.
- **Categorias Vazias** Mostrar categorias que não contêm artigos ou subcategorias.
- **Descrições de Subcategorias** Mostrar a descrição das subcategorias.
- **\# Artigos na Categoria** Mostrar uma contagem do número total de artigos em cada categoria.

### Aba Layout de Blog

As Opções de Layout de Blog controlam a aparência do detalhamento da categoria se isso resultar em um layout de blog.

O formulário de layout de blog tem um layout diferente do nos Elementos Comuns acima, mas os campos são semelhantes.

### Aba Compartilhada

As Opções Compartilhadas se aplicam para Opções Compartilhadas em Lista, Blog e em Destaque, a menos que sejam alteradas pelas configurações do menu.

![Lista de Artigos de Item de Menu Todas as Categorias aba compartilhada](../../../pt/images/menu-items/articles-list-all-categories-shared-tab.png)

- **Paginação** A paginação fornece links de página na parte inferior da página que permitem ao Usuário navegar por páginas adicionais. Esses links são necessários se os Artigos não couberem em uma única página.
  - *Ocultar* Links de paginação não mostrados. *Nota* Os usuários não poderão navegar para páginas adicionais.
  - *Mostrar* Links de paginação mostrados, se necessário.
  - *Automático* Links de paginação mostrados, se necessário.
- **Resumo da Paginação** Mostrar o número da página atual e o total de páginas (por exemplo, *Página 1 de 2*) na parte inferior de cada página.

## Dicas

- As categorias podem ser *aninhadas* em níveis, similar a pastas em um disco rígido. Em teoria, não há limite absoluto para o número de níveis que você pode ter. No entanto, como questão prática, é recomendado manter os níveis no mínimo. O layout Mostrar Todas as Categorias pode não funcionar corretamente se o número de níveis exibidos for maior que 5.
- Se você configurar os títulos das categorias como vinculáveis, o usuário pode explorar mais a fundo a categoria. Quando fizerem isso, normalmente verão um item de menu Lista de Categoria ou Blog de Categoria, dependendo da opção selecionada. Se houver um item de menu pré-existente para esta categoria (por exemplo, um item de menu Blog de Categoria), então esse item de menu aparecerá na exploração e as opções definidas para esse item de menu controlarão a exibição da página. Caso contrário, as opções definidas para o item de menu atual Mostrar Todas as Categorias controlarão a exibição da página.
- Você pode definir a opção para explorar uma lista ou blog de duas formas.
  - Em *Artigos: Opções* você pode definir o valor padrão para todas as categorias.
  - Em *Categoria: Editar* você pode definir um valor para uma categoria específica. Se isso for definido, ele substitui o valor padrão.
- Para personalizar um *Formato de Data* você pode usar `D M Y` para dia, mês e ano ou `d-m-y` para uma versão curta, por exemplo, 17-08-05. Se deixado em branco, a tradução da chave DATE_FORMAT_LC1 é usada do seu arquivo de idioma. 

*Traduzido por openai.com*


<!-- Filename: Help4.x:Articles / Display title: Artigos -->

## Descrição

O «Gestor de Artigos» é utilizado para encontrar, marcar os destaques,
adicionar e editar artigos.

Articles are the basic units of information in the content system and
the bottom level in the content hierarchy. Each Article is in exactly
one Category.

## Como Aceder
Selecione **Painel principal → Site → Artigos**

To add a Article:

- click the **New** toolbar button

To edit a Article:

- select a **Title** from the list

## Captura de Ecrã

![Articles list](../../../ptbr/images/articles/articles-list.png "Article list")

## Cabeçalhos de Coluna

- **Checkbox**. Check this box to select articles. To select all
  articles, check the box in the column heading. After boxes are checked
  the toolbar button 'Actions' get active.
- **Ordem**. You can change the order of an article within a list as
  follows:
  - Select the Ordering icon <i class="fa-solid fa-sort"></i> in the first
  column heading to make it active.
  - Select one of the vertical ellipsis icons <span class="icon-ellipsis-v"></span>
 and drag it up or down to change the
    position of that row in the list.
  - In the Filter Options you may limit the list to articles that are
    assigned for example to a Language.
- **Em destaque**. Click the icon to toggle. The article will show on
  the Featured Articles
  page.
- **Estatuto**. Status of article. Hover icon for informations.
- **Título**. The title of the article. Edit the article by clicking on
  the Title.
- **Acesso**. The viewing Access level  for this article.
- **Autor**. Name of the User who created this article.
- **Associação**. Shows the associated articles. Click on the Language
  Code to open the article. Multilingual only.
- **Idioma**. Articles language, default is 'All'.
- **Data de criação**. The date this article was created.
- **Acessos**. The number of times an article has been viewed.
- **ID**. A unique identification number for this article, you cannot
  change this number.

## Filtros de Lista

**Search bar**. Near the top of the page you will see the search bar
shown in the Screenshot above.

- **Search by Text**. Enter part of the search term and click the Search
  icon. *Hover* to see a *Tooltip* indicating which fields will be
  searched.To 'Search by ID' enter "id:x", where "x" is the ID number
  (for example, "id:19").
- **Opções de filtro**. Click to display the additional filters.
- **Limpar**. Click to clear the Filter field and restore the list to
  its unfiltered state.
- **Ordering**. Shows the current list ordering field. 2 ways to change
  the order:
  - Select from the dropdown list. Ordering may be in ascending or
    descending order.
  - Click a column heading. The column heading toggles between ascending
    and descending order.
- **Number to Display**. Shows the number of articles in a list. Select
  from the dropdown list to change the number displayed.The default for
  a site is '20' but this may be changed in the Global Configuration.

### Opções de filtro

Próximo do topo da página irá ver a barra de filtro mostrada na [Captura
de Ecrã](#screenshot) acima.

- **Escolher destacados**. Select from Unfeatured Articles / Featured
  Articles.
- **Selecionar estatuto**. Select from Trashed / Unpublished / Published
  / Archived / All.
- **Escolher categorias**. Select from the list of available categories.
- **Selecionar acesso**. Select from the list of available viewing
  access levels.
- **Escolher autor**. Select from the list of available authors.
- **Escolher idioma**. Select from the list of available languages.
- **Escolher etiqueta**. Select from the list of available tags.
- **Máximo de níveis**. Select from the list of available levels.

### Pagination

**Page Controls**. When the number of articles is more than one page,
you will see a page control bar near the bottom of the page shown in the
Screenshot above. The current page number being viewed
has a dark colour background.

- **Start**. Click to go to the first page.
- **Prev**. Click to go to the previous page.
- **Page numbers**. Click to go to the desired page.
- **Next**. Click to go to the next page.
- **End**. Click to go to the last page.

## Toolbar

No topo da página, irá ver a barra de ferramentas mostrada na [Captura
de Ecrã](#screenshot) acima.

- **Novo**. Opens the editing screen to create a new article.
- **Ações**. Reveals a list of actions for selected articles. Check one
  or more articles checkboxes to activate the list.
  - **Publicar**. Makes the selected articles available to visitors to
    your website.
  - **Despublicar**. Makes the selected articles unavailable to visitors
    to your website.
  - **Despublicar**. Marks selected articles as featured.
  - **Retirar destaque**. Changes the status of featured articles to
    unfeatured.
  - **Arquivar**. Changes the status of the selected articles to
    indicate that they are archived.
  - **Validar**. Checks-in the selected articles.
  - **Reciclagem**. Changes the status of the selected articles to
    indicate that they are trashed.
  - **Em lote**. Batch processes the selected articles.
- **Opções**. Abre a janela das «Opções» onde as definições como os
  parâmetros predefinidos podem ser editados.
- **Ajuda**. Abre este ecrã de ajuda.

## Batch Process

The Batch Process allows a change in settings for a group of selected
articles.

![articles batch process](../../../ptbr/images/articles/articles-list-batch.png "Articles batch process")

**How to Batch Process** a group of articles:

1.  Select one or more articles on the list by checking the desired
    checkboxes.
2.  Click the Batch Toolbar button.
3.  Set one or more of the following values:
    - To change the **Language**, select the desired new language from
      the Set Language list box.
    - To change the **Access Levels**, select the desired new access
      level from the Set Access Level list box.
    - To change the **Category**, select a category. To leave the
      category unchanged, use the default value of 'Select'.
      - To **copy** the articles to a different category, select the
        desired category from the category list box and check the Copy
        option. In this case, the original articles are unchanged and
        the copies are assigned to the new category and, if selected,
        the new language, access level, and tag.
      - To **move** the articles to a different category, select the
        desired category from the category list box and check the Move
        option. In this case, the original articles will be moved to a
        new category and, if selected, be assigned the new language,
        access level, and tag.
    - To add **Tags**, select the desired Tags from the dropdown or
      choose to keep the tags currently added to the original articles.
4.  When all of the settings are entered, click on Process to perform
    the changes. A message **"Batch process completed successfully."**
    will show.

## Quick Tips

- If Joomla is installed without sample data, one article category
  called 'Uncategorised' is created automatically.
- To see trashed and archived articles, set the Status filter to 'All'.
- To change the ordering of articles within a category, click on the
  Ordering column heading to sort by this column. Also, it is easier to
  see the ordering if you filter on the desired category.

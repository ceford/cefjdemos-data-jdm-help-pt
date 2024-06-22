<!-- Filename: Help4.x:Articles:_Edit / Display title: Artigo - Editar -->

## Descrição

This screen is used to add a new or edit a existing Article, usually
using a Wysiwyg editor. The default editor is TinyMCE but if other
editors are installed the default editor may be set to something else
for the site as a whole or for individual users.

Most parameters have suitable defaults but you might wish to set a
specific Category or provide article-specific Metadata.

## Tutorials

[Adding an Image to an Article](jdocmanual?article=user/articles/adding-an-image-to-an-article "Adding an Image to an Article")

## How to Access
Selecione **Conteúdos → Artigos**

To add a Article:

- click the **New** toolbar button

To edit a Article:

- select a **Title** from the list

## Screenshot

![Articles edit screenshot](../../../ptbr/images/articles/articles-edit-content-tab.png "Articles edit")

## Form Fields

- **Título**. The Title for this article.
- **Alternativo**. The internal name of this article. Normally, you can
  leave this blank and Joomla will fill in a default value Title in
  lower case and with dashes instead of spaces.

### Conteúdos guia

#### Left Panel

- **Texto do artigo**. This is where you enter the contents of the
  article. Joomla includes 3 editors, the default Editor - TinyMCE
  is shown above.

  The CMS Content dropdown list provides for access to link to an Article,
  Contact, Field, Media, Menu, Module, Page Break or Read More break.
- **Alternar editor**. A Toggle Editor button show below the edit window.
  This button allows you to toggle between TinyMCE and Editor - None.

#### Right Panel

- **Estatuto**. The published status of this article.
  - Publicado: Article is visible in the Frontend of the site.
  - Não publicado: Article is will not be visible to guests in the
    Frontend of the site. It may be visible to logged in users who have
    edit state permission for the article.
  - Arquivado: Article will no longer show on menu items
    or Category
    List.
  - Na reciclagem: Article is deleted from the site but still in the
    database.
- **Categoria**. Select the Category for this article.
- **Em destaque**. Select Yes if article will be shown in the Featured menu item
- **Acesso**. Select the viewing access level for this article. The
  access levels depend on what has been set up in Users: Access Levels.
- **Idioma**. Select the language for this article. Keep the default of
  'All' if you are not using the multi-language feature.
- **Etiquetas**. Assign tags to this article. You may select a tag from
  a pre-defined list or
  enter a new tag by typing the name in the field and pressing enter.
- **Nota**. This is normally for the administrator's use (for example,
  to document information about this article) and does not show in the
  Frontend.
- **Notas de versão**. Optional field to identify the version of this
  article in the article's Version History.

### Imagens e ligações guia

**Note**: This can be hidden by a user with Admin permissions in the
Article: Options.
This section lets you display images and links in your articles using
standardised layouts.

![Articles edit images and links tab](../../../ptbr/images/articles/articles-edit-images-tab.png "Articles edit images and links tab")

#### Imagem de introdução

- **Imagem de introdução**. Click the Select button to select an image
  to be displayed in a fixed location in the Intro Text of this article.
  This will open a window that allows you to select an image from your
  images folder.
- **Descrição da imagem (texto alternativo)**. Set the alt attribute for
  this image. A few descriptive words for screen readers.
- **Sem descrição**. Check in the rare instance of a purely decorative
  image. Note that if the Image Description is empty and the No
  Description checkbox is unchecked then the image will fail to meet
  accessibility criteria. If an image description is present this
  checkbox has no effect.
- **Classe da imagem**. You can add any CSS class for your own styling
  ideas. For image position use for example float-start and float-end.

- **Legenda**. Create a caption for this image.

#### Imagem completa - artigo

- **Imagem completa - artigo**. Click the Select button to select an
  image to be displayed in a fixed location in the Full Text of this
  article. This will open a window that allows you to select an image
  from your images folder.
- **Descrição da imagem (texto alternativo)**. Set the alt attribute for
  this image. A few descriptive words for screen readers.
- **Sem descrição**. Check in the rare instance of a purely decorative
  image. Note that if the Image Description is empty and the No
  Description checkbox is unchecked then the image will fail to meet
  accessibility criteria. If an image description is present this
  checkbox has no effect.
- **Classe da imagem**. You can add any CSS class for your own styling
  ideas. For image position use for example float-start and float-end.

- **Legenda**. Enter an optional caption for this image.

#### Ligação A

- **Ligação A**. The URL for the first link to be displayed in a fixed
  location in the article text. This must be a full URL, not relative.
  For example, it normally would start with `https:`.
- **Texto ligação A**. The text used for Link A. If blank, the URL will
  be displayed.
- **Janela alvo**. Sets the default value for the target for the first
  Link in this article. Choices are:
  - Abrir na janela de origem: Opens the in the main browser window,
    replacing the current Joomla article.
  - Abrir em nova janela: Opens the link in a new browser window.
  - Abrir em janela flutuante: Opens the link in a pop-up browser window
    (without full navigation controls).
  - Modal: Opens the link in a modal pop-up window.

**Ligação B**, **Ligação C**: Same options as Link A.

### Opções guia

**Note**: This can be hidden by a user with Admin permissions in the
Article: Options.
This is a set of options you can use to control how this article will
show in the Frontend.

![Options tab](../../../ptbr/images/articles/articles-edit-options-tab.png "Options Tab")

#### Visual

- **Visual**. Use a layout from the supplied article view or overrides in the templates.
- **Título**. Show the Article's Title.
- **Títulos com hiperligação**. Show the title as a link to the article.
- **Etiquetas**. Enter tags for this article. Select existing tags by
  entering in the first few letters or create new tags by entering them
  here.
- **Texto introdutório**.
  - Exibir: The Intro Text of the article will show when you drill down
    to the article.
  - Ocultar: Only the part of the article after the Read More break will
    show.
- **Informações do artigo - Posição**.
  - Acima: Puts the article information block above the text.
  - Abaixo: Puts the article information block below the text.
  - Dividir: Splits the article information block into 2 separate
    blocks. One block is above and the other is below the text.
- **Informações do artigo - Título**. Displays 'Details' on top of the
  article information block.

#### Categoria

- **Categoria**. Show the Article's Category Title.
- **Categoria com Hiperligação**. Show the title as a link to that
  Category.
- **Categoria hospedeira**. Show the Article's Parent Category Title.
- **Ligação da categoria hospedeira**. Show the title as a link to that
  Category.

#### Associações

- **Associações**. Show the associated flags or Language Code.
  Multilingual only.

#### Autor

- **Autor**. Show the author of the Article.
- **Ligação para a página de contacto do autor**. Show it as a link to a
  Contact layout for that author.Note: The author must be set up as a Contact.

#### Data

- **Data de criação**. Show the Article's create date.
- **Data de modificação**. Show the Article's modify date.
- **Data de publicação**. Show the Article's start publishing date.

#### Opções

- **Navegação**. Show a navigation link 'Prev' or 'Next' when you drill
  down to the article.
- **Acessos**. Show the number of times the article has been displayed
  by a user.
- **Ligações reservadas**. If Yes, the Intro Text for restricted
  articles will show. Clicking on the Read more link will require users
  to log in to view the full article content.
- **Posicionamento das ligações.**
  - Acima: Links are shown above the content.
  - Abaixo: Links are shown below the content.
- **Texto - Ler mais**. Customise the text that shows for the default
  wording 'Read more'.
- **Título de página do Browser**. Text for the Browser page title to be
  used when the article is viewed with a non-article menu item. If
  blank, the article's title is used instead.

### Campos guia

This section shows the custom fields which are defined for this article.

![Fields tab](../../../ptbr/images/articles/articles-edit-fields-tab.png "Filds Tab")

### Schema tab

![Schema tab](../../../ptbr/images/articles/articles-edit-schema-tab.png "Schema Tab")

The schema mechanism allows you to enter metadata for individual articles,
choosing from the following schema types:

* None
* Article
* BlogPosting
* Book
* Event
* JobPosting
* Organisation
* Person
* Recipe
* Custom

Each is a plugin which can disable or enable as required. More schmema types
my be added later or available from third party sources.

### Publicação guia

This section allows you to enter parameters and Metadata for this Article.

**Note**: This can be hidden by a user with Admin permissions in the
Article: Options.

![Publishing tab](../../../ptbr/images/articles/articles-edit-publishing-tab.png "Publishing Tab")

#### Publicação

- **Iniciar publicação**. Date and time to start publishing. Enter
  article ahead of time and then have it published automatically at a
  future time.
- **Terminar publicação**. Date and time to finish publishing. The
  article is automatically changed to Unpublished state at a future
  time.
- **Iniciar destaque**. Date and time to start featured state. Enter
  article ahead of time and then have it featured automatically at a
  future time.
- **Terminar destaque**. Date and time to finish featured state. The
  article is automatically changed to Unfeatured state at a future time.
- **Data de criação**. The current time when the Article was created.
  Enter in a different date and time or click on the calendar icon to
  find the desired date.
- **Criado por**. Name of the User who created this Article. This will
  default to the currently logged-in user. If you want to change this to
  a different user, click the Select User button.
- **Criado por (pseudónimo)**. Enter in an alias for the Author of this
  Article. This allows you to display a different Author name.
- **Data de alteração**. Date of last modification.
- **Modificado por**. Username who performed the last modification.
- **Revisão**. Number of revisions to this Article.
- **Acessos**. The number of times this Article has been viewed.
- **ID**. A unique identification number for this Article, you cannot
  change this number. When creating a new Article, this field displays
  "0" until you save the new entry.

#### Metadados

- **Metadescrição**. An paragraph to be used as the description of the
  page.
- **Termos chave**. Entry for keywords.
- **Robôs**. The instructions for web 'robots' that browse to this page.
  Set 'Use Global' in Global Configuration.
- **Autor**. Entry for an Author name within the metadata.
- **Direitos de utilização**. Describe what rights others have to use
  this content.

### Associações guia

**Note**: This can be hidden by a user with Admin permissions in the
Article: Options.
Tab is shown on Multilingual Sites
only.

![Associations tab](../../../ptbr/images/articles/articles-edit-associations-tab.png "Associations Tab")

### Configurar ecrã de edição guia

**Note**: This can be hidden by a user with Admin permissions in the
Article: Options.

![Configure edit screen tab](../../../ptbr/images/articles/articles-edit-editor-tab.png "Configure edit screen Tab")

- **Opções de publicação**. If Hide, the Publishing Options tab
  will not show in the Backend. This means that Backend users will not
  be able to edit the fields in this tab. These fields will always be
  set to their default values.
- **Artigos - Opções**. If Hide, the Article Options tab
  will not show in the Backend. This means that Backend users will not
  be able to edit the fields in this tab. These fields will always be
  set to their default values.
- **Administrador - Imagens e ligações padrão**. If Yes, the Images and
  Links tab will show.
- **Área de visitantes - Imagens e ligações padrão**. If Yes, the Images
  and Links tab will show in the Frontend article editor screen.

### Permissões guia

This is where you can enter permissions for this article.

**Note**: This can be hidden by a user with Admin permissions in the
Article: Options.

![Permissions tab](../../../ptbr/images/articles/articles-edit-permissions-tab.png "Permissions Tab")

To change the permissions for this article, do the following.

1.  Select the **Group** by clicking its title located on the left.
2.  Find the desired **Action**.
    - **Eliminar**. Users can delete this article.
    - **Editar**. Users can edit this article.
    - **Editar estatuto**. User can change the published state and
      related information for this article.
3.  Select the desired permission for the action you wish to change.
    - **Herdado**. Inherited for users in this Group from the Global Configuration,
      Articles Options,
      or Articles Category.
    - **Permitido**. Allowed for users in this Group.Note: If this
      action is Denied at one of the higher levels, the Allowed
      permission here will not take effect. A Denied setting cannot be
      overridden.
    - **Negado**. Denied for users in this Group.
4.  Click **Save** in **Toolbar** at top. When the screen refreshes, the
    Calculated Setting column will show the effective permission for
    this Group and Action.

## Barra de Ferramentas

No topo da página, irá ver a barra de ferramentas mostrada na [Captura
de Ecrã](#screenshot) acima.

- **Guardar**. Guarda o item e fica no ecrã atual.
- **Guardar e fechar**. Saves the article and closes the current screen.
  - **Guardar e novo**. Guarda o item e mantém o ecrã de edição aberto e
    pronto para criar outro item.
  - **Guardar no Menu**. Saves the article to a menu item and opens the
    menu item screen.
  - **Guardar como cópia**. Saves your changes to a copy of the current
    article. Does not affect the current article.
- **Fechar**. Fecha o ecrã atual e volta ao ecrã anterior sem guardar
  quaisquer modificações que tenham sido efetuadas.
- **Versões**. Opens the Article Version History window to show any
  prior versions of this article. This allows you to view older versions
  of this article and, if desired, restore from an older version.
- **Pré-visualizar**. Opens a modal dialog showing a site view of this
  article. Requires shared sessions
  or being logged in into the Frontend.
- **Accessibility Check**. Opens a window showing accessibility check
  results of the article.
- **Associações**. With a specific language set for an article, allows
  side by side editing in another language. This icon is shown on
  Multilingual Sites
  only.
- **Toggle Inline Help**. Show help text below some options.
- **Ajuda**. Abre este ecrã de ajuda.

## Quick Tips

- There are 2 methods to insert an image into article using the TinyMCE
  editor.
  1.  The CMS Content
      dropdown list provides access to the Media screen
      that lets you browse image files and upload images.
  2.  The 'Insert' dropdown list is a simple form for which you need to
      know the image url. It is used for external images.
- **Read more**
  breaks allow you to save space on the Front Page or on any blog layout
  page by showing just the first portion of an Article. Page break
  allow you to provide multi-page navigation for long Articles. You can
  use both on one Article, if desired.For example, you could put a Read
  more break after the first paragraph of a multi-page article, and have
  Page breaks after each page. No page navigation would display on the
  Front Page until the User selects the Read more link. At that time,
  the Article's table of contents would display showing links to every
  page.

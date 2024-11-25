<!-- Filename: Help4.x:Articles:_Edit / Display title: Artigos: Editar -->

## Descrição

Esta página é usada para adicionar um novo artigo ou editar um artigo existente, geralmente usando um editor Wysiwyg. O editor padrão é o TinyMCE, mas se outros editores estiverem instalados, o editor padrão pode ser configurado para algo diferente para o site como um todo ou para usuários individuais.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba Esquema](jdocmanual?article=help/common-elements/edit-schema).
* [A Aba de Publicação](jdocmanual?article=help/common-elements/edit-publishing).
* [A Aba de Associações](jdocmanual?article=help/common-elements/edit-associations).
* [A Aba de Permissões](jdocmanual?article=help/common-elements/edit-permissions).
* [O Popup do Histórico de Versões](jdocmanual?article=help/common-elements/edit-version-history).

Ou em artigos de Usuário:

* [Adicionando uma Imagem a um Artigo](jdocmanual?article=user/articles/adding-an-image-to-an-article)

## Como Acessar

* Selecione **Conteúdo → Artigos** no menu do Administrador. Ou...
* Selecione **Artigos** no Painel Inicial. Então...
  * Selecione um **Título** de artigo existente na lista para editá-lo. Ou...
  * Selecione o botão **Novo** na Barra de Ferramentas para criar um novo artigo.
Você também pode criar um novo artigo selecionando o ícone **+** no Menu ou
Painel Inicial.

## Captura de Tela

![Captura de tela de edição de artigos](../../../pt/images/articles/articles-edit-content-tab.png)


## Campos do Formulário

- **Título** O título deste artigo.
- **Alias** O nome interno deste artigo. Normalmente, você pode deixar
  este campo em branco e o Joomla irá preencher um valor padrão com base no Título, mas
  em letras minúsculas e com hífens invés de espaços.

### Aba de Conteúdo

#### Painel Esquerdo

- **Texto do Artigo** É aqui que você insere o conteúdo do artigo.
    O Joomla inclui 3 editores, o Editor padrão - TinyMCE
    está mostrado acima.

    A lista suspensa de Conteúdo CMS permite acessar o link para um Artigo,
    Contato, Campo, imagem de Mídia, Menu, Módulo, Interrupção de Página ou Interrupção de Ler Mais.

    O símbolo de elipse (<span class="icon-ellipsis-h"></span>) alterna a visibilidade
    de ferramentas extras.
- **Alternar Editor** O botão abaixo da janela de edição permite alternar
    entre o editor TinyMCE e nenhum editor. Isso permite ver e
    às vezes corrigir o código HTML.

#### Painel Direito

- **Status** O status de publicação deste artigo.
  - *Publicado* O artigo está visível no Frontend do site.
  - *Não publicado* O artigo não será visível para visitantes no
    Frontend do site. Pode ser visível para usuários logados que têm
    permissão para editar o estado do artigo.
  - *Arquivado* O artigo não aparecerá mais nos itens de menu ou na Lista de Categorias.
  - *No Lixo* O artigo é excluído do site, mas ainda está no banco de dados.
- **Categoria** Selecione a Categoria para este artigo.
- **Em destaque** Selecione Sim se o artigo será mostrado no item de menu Em destaque.
- **Acesso** Selecione o nível de acesso de visualização para este artigo. Os
  níveis de acesso dependem do que foi configurado em Usuários: Níveis de Acesso.
- **Idioma** Selecione o idioma para este artigo. Mantenha o padrão
  de 'Todos' se você não estiver usando o recurso multi-idioma.
- **Tags** Atribua tags a este artigo. Você pode selecionar uma tag de uma
  lista predefinida ou
  inserir uma nova tag digitando o nome no campo e pressionando enter.
- **Nota** Isto é normalmente para o uso do administrador (por exemplo,
  para documentar informações sobre este artigo) e não aparece no
  Frontend.
- **Nota de Versão** Campo opcional para identificar a versão deste
  artigo no Histórico de Versões do artigo.

### Aba de Imagens e Links

**Nota:** Esta aba pode ser escondida em *Artigo: Opções* por um usuário com
permissões de Administrador. Ela permite a exibição de imagens e links em artigos usando
layouts padronizados.

#### Imagem de Introdução

- **Imagem de Introdução** Clique no botão Selecionar para escolher uma imagem a ser
  exibida em um local fixo no Texto de Introdução deste artigo. Isso
  abrirá uma janela que permite a seleção de uma imagem da pasta de imagens.
- **Descrição da Imagem (Texto Alternativo)** Defina o atributo alt para esta
  imagem. Algumas palavras descritivas para leitores de tela.
- **Sem Descrição** Marque em casos raros de imagem meramente decorativa.
  Observe que se a Descrição da Imagem estiver vazia e a caixa Sem Descrição
  não estiver marcada, então a imagem não atenderá aos critérios de acessibilidade.
  Se uma descrição da imagem estiver presente, esta caixa de seleção não terá efeito.
- **Classe da Imagem** Adicione qualquer classe CSS para estilização personalizada.
  Por exemplo, para a posição da imagem use float-start ou float-end.
- **Legenda** Crie uma legenda para esta imagem.

#### Imagem do Artigo Completo

- **Imagem do Artigo Completo** Clique no botão Selecionar para escolher uma imagem a ser
  exibida em um local fixo no Texto Completo deste artigo.
  Isso abrirá uma janela que permite a seleção de uma imagem da
  pasta de imagens.
- **Descrição da Imagem (Texto Alternativo)** Defina o atributo alt para esta
  imagem. Algumas palavras descritivas para leitores de tela.
- **Sem Descrição** Marque em casos raros de imagem meramente decorativa.
  Observe que se a Descrição da Imagem estiver vazia e a caixa Sem Descrição
  não estiver marcada, então a imagem não atenderá aos critérios de acessibilidade.
  Se uma descrição da imagem estiver presente, esta caixa de seleção não terá efeito.
- **Classe da Imagem** Adicione qualquer classe CSS para estilização personalizada.
  Por exemplo, para a posição da imagem use float-start ou float-end.
- **Legenda** Digite uma legenda opcional para esta imagem.

#### Link A

- **Link A** A URL para o primeiro link a ser exibido em um local fixo
  no texto do artigo. Deve ser uma URL completa, não relativa.
  Por exemplo, normalmente começaria com `https:`.
- **Texto do Link A** O texto usado para o Link A. Se em branco, a URL será
  exibida.
- **Janela de Destino da URL** Define o valor padrão para o destino do
  primeiro Link neste artigo. As opções são:
  - *Abrir na janela principal* Abre na janela principal do navegador,
    substituindo o artigo atual do Joomla.
  - *Abrir em nova janela* Abre o link em uma nova janela do navegador.
  - *Abrir em pop-up* Abre o link em uma janela pop-up do navegador (sem
    controles de navegação completos).
  - *Modal* Abre o link em uma janela pop-up modal.

#### Link B, Link C

- Mesmas opções que o Link A.

### Aba de Opções

**Nota**: Esta aba pode ser escondida por um usuário com permissões de Administrador em
Artigo: Opções. É um conjunto de opções usadas para controlar como este
artigo aparecerá no Frontend.

#### Layout

- **Layout** Use um layout da visualização de artigo fornecida ou substituições nos templates.
- **Título** Mostrar o Título do Artigo.
- **Títulos Linkados** Mostrar o título como um link para o artigo.
- **Tags** Insira tags para este artigo. Selecione tags existentes
  digitando as primeiras letras ou crie novas tags digitando-as
  aqui.
- **Texto de Introdução**
  - *Mostrar* O Texto de Introdução do artigo aparecerá em uma página que exibe o
    artigo completo.
  - *Esconder* Apenas a parte do artigo após a quebra de Ler Mais
    será exibida em uma página que exibe o artigo completo.
- **Posição das Informações do Artigo**
  - *Acima* Coloca o bloco de informações do artigo acima do texto.
  - *Abaixo* Coloca o bloco de informações do artigo abaixo do texto.
  - *Dividido* Divide o bloco de informações do artigo em 2 blocos separados.
    Um bloco está acima e o outro está abaixo do texto.
- **Título das Informações do Artigo** Exibe 'Detalhes' no topo do bloco
  de informações do artigo.

#### Categoria

- **Categoria** Mostrar o Título da Categoria do Artigo.
- **Link da Categoria** Mostrar o título como um link para essa Categoria.
- **Categoria Pai** Mostrar o Título da Categoria Pai do Artigo.
- **Link da Categoria Pai** Mostrar o título como um link para essa Categoria.

#### Associações

- **Associações** Mostrar as bandeiras associadas ou Código do Idioma.
  Somente multilíngue.

#### Autor

- **Autor** Mostrar o autor do Artigo.
- **Link para a Página de Contato do Autor** Mostrar como um link para um
  layout de Contato para esse autor. Nota: O autor deve estar configurado como um Contato.

#### Data

- **Data de Criação** Mostrar a data de criação do Artigo.
- **Data de Modificação** Mostrar a data de modificação do Artigo.
- **Data de Publicação** Mostrar a data de início da publicação do Artigo.

#### Opções

- **Navegação** Mostrar links de navegação, *Anterior* e/ou *Próximo*, ao
  exibir uma página contendo o artigo completo.
- **Acessos** Mostrar o número de vezes que o artigo foi exibido por um usuário.
- **Links Não Autorizados** Se Sim, o Texto de Introdução para artigos restritos
  será mostrado. Clicar no link Ler mais exigirá que os usuários façam login
  para ver o conteúdo completo do artigo.
- **Posicionamento dos Links**
  - *Acima* Os links são mostrados acima do conteúdo.
  - *Abaixo* Os links são mostrados abaixo do conteúdo.
- **Texto do Ler Mais** Personalize o texto que aparece para o padrão
  'Ler mais'.
- **Título da Página do Navegador** Texto para o título da página do Navegador a ser
  usado quando o artigo é visualizado com um item de menu não de artigo. Se em branco, o
  título do artigo é usado em vez disso.

### Aba de Campos

Esta seção mostra os campos personalizados que estão definidos para este artigo. Estes
são campos que não estão atribuídos a um Grupo de Campos. Cada Grupo de Campos, se definido,
aparecerá como uma aba separada.

### Aba Configurar Tela de Edição

**Nota:** Isto pode ser escondido por um usuário com permissões de Administrador em
Artigo: Opções.

- **Opções de Publicação** Se Ocultar, a aba Opções de Publicação
  não aparecerá no Backend. Isso significa que os usuários do Backend não
  poderão editar os campos nesta aba. Estes campos sempre estarão
  definidos para os valores padrão.
- **Opções do Artigo** Se Ocultar, a aba Opções do Artigo
  não aparecerá no Backend. Isso significa que os usuários do Backend não
  poderão editar os campos nesta aba. Estes campos sempre estarão
  definidos para os valores padrão.
- **Imagens e Links do Administrador** Se Sim, a aba Imagens e Links
  aparecerá.
- **Imagens e Links no Frontend** Se Sim, a aba Imagens e Links
  aparecerá na tela do editor de artigo do Frontend.

## Dicas

- Existem 2 métodos para inserir uma imagem em um artigo usando o editor TinyMCE.
  1. A lista suspensa *CMS Content* fornece acesso à tela de Mídia.
  2. A lista suspensa *Insert* é um formulário simples que requer a URL da imagem. Ela é usada para imagens externas.
- Um inserção *Ler Mais* economiza espaço em qualquer página de layout Destacado ou Blog ao mostrar apenas a primeira parte de um Artigo. As inserções *Page Break* oferecem navegação em várias páginas para artigos longos. Ambos podem ser utilizados em um único artigo, se desejado. Por exemplo, uma quebra *Ler Mais* poderia ser colocada após o primeiro parágrafo, e quebras *Page Break* poderiam ser colocadas após grupos de parágrafos posteriores para criar um artigo em várias páginas. Nenhuma navegação de página seria exibida na página Destacada ou Blog até que o Usuário selecione o link Ler mais. Nesse momento, o sumário do Artigo seria exibido, mostrando links para cada página.


<!-- Filename: Help4.x:Site_Modules:_Articles_-_Category / Display title: Módulos: Artigos - Categoria  -->

## Descrição

O tipo de módulo *Artigos - Categoria* exibe uma lista de artigos publicados de uma ou mais categorias.

### Elementos Comuns

Alguns elementos desta página são cobertos em artigos de Ajuda separados:

* [Barras de ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [Os Módulos: Aba de Módulos](jdocmanual?article=help/modules/modules-module-tab).
* [Os Módulos: Aba de Atribuição de Menu](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [Os Módulos: Aba Avançada](jdocmanual?article=help/modules/modules-advanced-tab).
* [A Aba de Permissões](jdocmanual?article=help/common-elements/edit-permissions).

<!-- ToDo: Um tutorial para mostrar como usar este módulo -->

## Como Acessar

- Selecione **Sistema → Gerenciar Painel → Módulos do Site** no menu
  do Administrador. Em seguida...
  - Para criar um novo módulo: selecione o botão **Novo** na Barra de Ferramentas. Em seguida...
    - Selecione o tipo de módulo necessário.
  - Para editar um módulo existente:
    - Encontre o módulo na lista de módulos instalados e selecione o link do título na coluna **Título**.

## Captura de Tela

![guia do módulo de categoria de artigos](../../../pt/images/modules-site/modules-articles-category-module-tab.png)

## Campos do Formulário

- **Título** O título do módulo. Este também é o título exibido
  para o módulo, dependendo do campo de formulário *Mostrar Título*.

### Aba do Módulo

#### Painel Esquerdo

- **Modo** Selecione o modo a ser usado. Se o Modo Normal for escolhido, basta
  configurar o módulo e ele exibirá uma lista estática de Artigos nos
  itens de menu aos quais você atribuir o módulo. Se o Modo Dinâmico for escolhido, você
  ainda pode configurar o módulo normalmente, porém agora a opção de Categoria 
  não será mais utilizada. Em vez disso, o módulo detectará dinamicamente se 
  você está ou não em uma visualização de Categoria e exibirá a lista de artigos dentro
  dessa Categoria de acordo. Quando o Modo Dinâmico é escolhido, é melhor
  deixar o módulo configurado para exibir em todas as páginas, pois ele decidirá
  se deve ou não exibir algo dinamicamente.
- **Exibir na Página do Artigo** Este item aparece se o Modo *Dinâmico* for selecionado.
  Selecione para Mostrar ou Ocultar uma Lista de Artigos nas Páginas de Artigo. Isso significa que
  o módulo só se exibirá dinamicamente em Páginas de Categoria.

### Aba de Opções de Filtragem

![opções de filtragem de categoria de artigos aba](../../../pt/images/modules-site/modules-articles-category-filtering-options-tab.png)

- **Artigos em Destaque** Mostrar ou ocultar ou selecionar Apenas Artigos em Destaque.
- **Contagem** O número de itens a exibir. O valor padrão de 0
  exibirá todos os artigos.
- **Tipo de Filtragem de Categoria** Incluir ou excluir as categorias selecionadas.
- **Categoria** Selecione uma ou mais categorias.
- **Artigos de Categorias Filhas** Incluir ou excluir artigos de categorias filhas.
- **Profundidade da Categoria** O número de níveis de categorias filhas a retornar.
- **Tipo de Filtragem de Autor** Incluir ou excluir artigos dos autores selecionados.
- **Autores** Selecione um ou mais autores da lista.
- **Tipo de Filtragem de Alias do Autor** Incluir ou excluir os aliases de autor selecionados.
- **Aliases de Autor** Selecione um ou mais aliases de autor da lista.
- **IDs de Artigo para Excluir** Insira cada ID de Artigo para excluir em uma nova linha.
- **Filtragem de Data** Selecione o tipo de filtragem de data.
- **Campo de Intervalo de Data** Selecione qual intervalo de campo de data usar.
- **Intervalo de Data de Início** Se o Intervalo de Data for selecionado acima, insira uma data de início.
- **Até a Data** Se o Intervalo de Data for selecionado acima, insira uma data final.
- **Data Relativa** Se a Data Relativa for selecionada acima, insira um valor numérico para dias.
  Os resultados serão obtidos em relação à data atual e ao valor
  inserido.

### Aba de Opções de Ordenação

![opções de ordenação de categoria de artigos aba](../../../pt/images/modules-site/modules-articles-category-ordering-options-tab.png)

- **Campo do Artigo para Ordenar Por** Selecione um campo da lista. A Ordenação
  em Destaque deve ser usada apenas quando a Opção de Filtragem para Artigos
  em Destaque estiver definida como *Apenas*.
- **Direção da Ordenação** Selecione a direção da ordenação dos artigos.

### Aba de Opções de Agrupamento

![opções de agrupamento de categoria de artigos aba](../../../pt/images/modules-site/modules-articles-category-grouping-options-tab.png)

- **Agrupamento de Artigos** Selecione um método de agrupamento de artigos da lista.
- **Direção do Agrupamento** Selecione a direção da ordenação.
- **Formato de Exibição de Mês e Ano** Insira um formato de data válido.

### Aba de Opções de Exibição

![opções de exibição de categoria de artigos aba](../../../pt/images/modules-site/modules-articles-category-display-options-tab.png)

- **Títulos Vinculados** Mostrar títulos como links para artigos.
- **Data** Mostrar ou ocultar a data do artigo.
- **Campo de Data** Selecione o campo de data a ser exibido.
- **Formato de Data** Insira um formato de data válido.
- **Categoria** Mostrar ou ocultar o nome da categoria do artigo.
- **Visualizações** Mostrar ou ocultar as visualizações do artigo.
- **Autor** Mostrar ou ocultar o nome do autor ou alias do autor.
- **Texto de Introdução** Mostrar ou ocultar o texto de introdução do artigo.
- **Limite de Texto de Introdução** O número máximo de caracteres a exibir.
- **Mostrar "Leia Mais"** Mostrar ou ocultar o link *Leia mais...* se o
  texto principal do artigo tiver sido fornecido.
- **Mostrar Título com Leia Mais** Mostrar ou ocultar o título do artigo no
  link *Leia mais...*.
- **Limite de "Leia Mais"** Limitar o número de caracteres do título do artigo a ser exibido
  no link *Leia mais...*. 

*Traduzido por openai.com*


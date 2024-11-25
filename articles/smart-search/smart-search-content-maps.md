<!-- Filename: Help4.x:Smart_Search:_Content_Maps / Display title: Pesquisa Inteligente: Mapas de Conteúdo -->

## Descrição

A página *Pesquisa Inteligente: Mapas de Conteúdo* mostra os mapas de conteúdo atualmente no índice da Pesquisa Inteligente. Os mapas de conteúdo permitem que você faça uma referência cruzada do seu conteúdo indexado (artigos, etc.) com informações meta relacionadas, como a categoria em que ele se encontra. Cada item de conteúdo que é indexado pela Pesquisa Inteligente é adicionado a um ou mais mapas de conteúdo que podem ser usados como filtros ao pesquisar no índice.

Os mapas de conteúdo são divididos em duas partes:

- Grupo de Mapas: São super-contêineres para um tipo específico de informação. Por exemplo, um Grupo de Mapas pode ser *Tipo*, *Categoria*, *Evento*, *Idioma* ou *Autor*.
- Mapa de Conteúdo: Os mapas de conteúdo são os valores reais para a informação meta em um Grupo de Mapas específico. Os Mapas de Conteúdo são, por exemplo, os nomes das categorias ou autores.

Esses Grupos de Mapas e Mapas de Conteúdo formam o painel de pesquisa avançada disponível na interface do usuário. Para cada Grupo de Mapas, pode haver uma lista selecionável em forma de drop-down, e os Mapas de Conteúdo são adicionados como valores à lista respectiva. Criadores de sites mais avançados podem substituir os layouts padrão e usar listas de seleção múltipla ou caixas de seleção em vez disso.

É importante notar que Grupos de Mapas e Mapas de Conteúdo de diferentes tipos de conteúdo são mesclados em uma única lista. Um artigo do Joomla em uma categoria chamada *Notícias* e um feed de notícias ou contato em uma categoria com o mesmo nome são mapeados para o mesmo Mapa de Conteúdo no mesmo Grupo de Mapas. Isso é um pouco como etiquetar diferentes tipos de conteúdo com o mesmo rótulo. O efeito disso é que o visitante do seu site não precisa saber como o seu conteúdo é classificado para definir os filtros corretos para encontrá-lo.

A tela de mapas de conteúdo mostra todos os Grupos de Mapas dentro do índice da Pesquisa Inteligente juntamente com um número que indica a quantidade de Mapas de Conteúdo dentro desse Grupo de Mapas e os itens dentro de um Mapa de Conteúdo. Clicar no número de um Grupo de Mapas permite que você veja o Mapa de Conteúdo dentro desse Grupo de Mapas junto com o número de itens de conteúdo que pertencem a esse Mapa de Conteúdo. Um item de conteúdo pode pertencer a múltiplos Mapas de Conteúdo dentro de um Grupo de Mapas assim como a múltiplos Grupos de Mapas.

### Elementos Comuns

Alguns elementos desta página são abordados em artigos de Ajuda separados:

* [Barras de ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de Lista](jdocmanual?article=help/common-elements/list-filters).
* [Cabeçalhos de Coluna de Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordenação de Itens da Lista](jdocmanual?article=help/common-elements/list-ordering).
* [Paginação de Lista](jdocmanual?article=help/common-elements/list-pagination).

### Tutorial

* Se você é novo na Pesquisa Inteligente, deve ler o [guia de início rápido da Pesquisa Inteligente](https://docs.joomla.org/Smart_Search_quickstart_guide).

## Como acessar

- Selecione **Componentes → Pesquisa Inteligente → Mapas de Conteúdo** no menu do Administrador.

## Captura de Tela

![mapas de conteúdo de pesquisa inteligente](../../../pt/images/smart-search/smart-search-content-maps.png)

## Cabeçalhos de Colunas

- **Status** O status do item de conteúdo dentro da Busca Inteligente. Alterar o status afeta apenas se o item de conteúdo está disponível nos resultados de pesquisa e não afeta o item de conteúdo em si.
- **Título** O título do Grupo de Mapas ou Mapa de Conteúdo.
- **Mapas** O número de mapas dentro do Grupo de Mapas. Selecionar o número mostrará os mapas dentro do Grupo de Mapas.
- **Conteúdo Indexado Publicado** O número de itens de conteúdo publicados no Grupo de Mapas. Selecionar o número mostrará os itens de conteúdo publicados dentro do Grupo de Mapas.
- **Conteúdo Indexado Não Publicado** O número de itens de conteúdo não publicados no Grupo de Mapas. Selecionar o número mostrará os itens de conteúdo não publicados dentro do Grupo de Mapas.

## Barra de Ferramentas

- **Ações** Revela uma lista de ações para os itens selecionados. Marque uma ou mais caixas de seleção de itens para ativar a lista.
  - **Publicar**. Torna os Grupos de Mapas ou Mapas de Conteúdo selecionados disponíveis para visitantes do seu site.
  - **Despublicar.** Torna os Grupos de Mapas ou Mapas de Conteúdo selecionados indisponíveis para visitantes do seu site. Um Grupo de Mapas despublicado não será exibido como uma lista de seleção no front-end. Um Mapa de Conteúdo despublicado não aparecerá na lista de seleção para o Grupo de Mapas no qual ocorre. A reindexação não altera o estado de publicação de Grupos de Mapas ou Mapas de Conteúdo.
- **Excluir** Exclui os Grupos de Mapas ou Mapas de Conteúdo selecionados. Funciona com um ou vários Grupos de Mapas ou Mapas de Conteúdo selecionados. Você pode recuperar Grupos de Mapas ou Mapas de Conteúdo excluídos executando novamente o indexador de Pesquisa Inteligente.
- **Estatísticas** Mostra algumas estatísticas básicas sobre a Pesquisa Inteligente. 

*Traduzido por openai.com*


<!-- Filename: Help6.x:List_Filters / Display title: Filtros de Lista -->

## Propósito¶

A maioria dos componentes possui visualizações de lista que exibem itens do banco de dados. Pode haver centenas de itens, milhares talvez, ou até milhões. Portanto, Filtros de Lista são usados para reduzir a lista exibida àqueles que provavelmente contêm o que você precisa trabalhar.

Por exemplo, itens enviados para a lixeira normalmente não são exibidos por padrão. Se você deseja ver seus itens na lixeira, precisa configurar o filtro **- Selecionar Status -** para **Lixeira**. A captura de tela a seguir mostra os Filtros para a página de Artigos.

## Opções de Filtro da Lista de Artigos¶

![Lista de artigos](../../../pt/images/common-elements/articles-list-filter-options.png)

Para **mostrar** ou **ocultar** as Opções, selecione o botão **Opções de Filtro**. Observe
que as Opções são sempre exibidas ao retornar a qualquer página em que uma Opção
tenha sido selecionada.

O número de Opções exibidas varia com o componente. Mesmo o componente de Conteúdo,
que exibe a lista de Artigos, pode ter filtros adicionais. Por exemplo, um filtro **- Selecionar Etapa -** é exibido se o componente de Conteúdo
tiver **Workflows** ativados.

## A Barra de Pesquisa

### Pesquisa por Texto

*Passe o mouse* ou *selecione* o campo de *Pesquisa* para ver uma *Dica* ou ouvir um *Áudio*
equivalente indicando quais campos serão pesquisados. O comportamento padrão
é pesquisar o texto inserido dentro do texto do título.

O componente de conteúdo permite um prefixo para buscar dentro do ID, Autor ou
Conteúdo. Cada um desses termos precisa de dois-pontos, mas pode estar em qualquer *Caixa*. Por
exemplo: *ID:19* ou *Autor:João* ou *conteúdo:lorem ipsum*.

Para realizar uma pesquisa, insira parte do termo de pesquisa e selecione o ícone **Pesquisa**
(<span class="filter-search-bar__button-icon icon-search" aria-hidden="true"></span>).

### Opções de Filtro e Limpar

O botão **Opções de Filtro** é usado para alternar a visualização dos vários filtros. Se
não houver Filtros para um componente, este botão estará ausente.

O botão **Limpar** é usado para limpar todos os filtros e restaurar a lista para seu
estado não filtrado. Se não houver filtros para um componente, este botão estará
ausente.

### Ordem dos Resultados

A ordem em que os resultados são apresentados pode ser selecionada pelo usuário. Para artigos, a
ordem padrão é *ID Decrescente*, que coloca os artigos mais recentes no
topo da lista. Mas você pode desejar buscar artigos por mais acessados,
*Acessos decrescentes*, ou artigos que logo serão despublicados,
*Término de Publicação ascendente*.

A ordem dos resultados pode ser alterada ao selecionar um ícone de ordenação nos cabeçalhos das colunas da lista.
O ícone padrão *ID Decrescente* é representado por um
cifrão apontando para baixo (<span class="ms-1 icon-caret-down" aria-hidden="true"></span>).
Ele muda para um cifrão apontando para cima se a ordem de classificação for invertida, *ID Ascendente*.

### Número de Resultados

O número de resultados em uma lista é configurado na página de Configuração Global, aba Site,
campo Limite Padrão de Lista. O valor padrão para uma nova instalação é 20.

Há ocasiões em que isso não é conveniente. Você pode querer ver *50* ou
*100*. Tenha cuidado ao escolher *Todos*. Pode demorar muito para recuperar
os resultados e renderizar a página. O servidor pode ficar sem memória ou tempo e acionar
um erro fatal. E seu navegador pode demorar para exibir a página.

O valor padrão para este conjunto de documentação foi definido para 5 porque isso é
suficiente para capturas de tela ilustrativas.

## Como Usar Filtros

O propósito de cada filtro deve ser autoexplicativo a partir do rótulo do seletor não filtrado. Por exemplo, o filtro de Artigos **- Selecionar Status -** oferece cinco opções: *Lixeira*, *Não Publicado*, *Publicado*, *Arquivado* e *Todos*. A última é funcionalmente equivalente a sem filtro (*- Selecionar Status -*).

Quando uma opção de filtro é alterada, a página recarrega automaticamente com os novos resultados filtrados pela nova opção de filtro.

## Ocultar Colunas

Algumas listas de componentes têm muitas colunas e podem ser muito largas para a sua tela. Isso é especialmente verdadeiro para algumas traduções do texto dos cabeçalhos das colunas. O resultado mais incômodo é que os Títulos podem quebrar e ficar difíceis de ler.

Para dar mais espaço ao Título, você pode abrir a lista suspensa de Colunas e selecionar colunas menos importantes para ocultar. Em seguida, feche novamente a lista de Colunas. O efeito é imediato, pois utiliza JavaScript para ocultar as colunas selecionadas no layout. Elas ainda permanecem na página.

As suas configurações são salvas pelo seu navegador e serão usadas até que você as altere novamente, mesmo que você saia e entre novamente.

*Traduzido por openai.com*


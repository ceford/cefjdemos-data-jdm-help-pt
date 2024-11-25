<!-- Filename: Help4.x:Articles:_Options / Display title: Artigos: Opções -->

## Descrição

A página *Artigos: Opções* é usada para definir valores padrão globais para artigos. Eles são utilizados quando a opção *Usar Global* é selecionada em um item de menu de Artigos. Por exemplo, para mostrar a *Data de Criação* de um artigo nos itens de menu de Artigos, defina essa opção como *Mostrar* aqui e ela será o valor padrão.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Guia de Permissões](jdocmanual?article=help/common-elements/edit-permissions).

## Como Acessar

Selecione o botão **Opções** na Barra de Ferramentas de qualquer página da lista de *Artigos*.

## Captura de Tela

![Captura de tela das opções de artigos](../../../pt/images/articles/articles-options-articles-tab.png)

## Campos de Formulário

### Aba Artigos

Essas configurações se aplicam aos layouts de artigos, a menos que sejam alteradas para um item de menu ou artigo específico.

- **Escolher um Layout** Selecione o valor padrão para itens de menu Artigo Único.
- **Título** Mostrar o Título do Artigo.
- **Títulos Vinculados** Mostrar o título como um link para o artigo.
- **Texto de Introdução**
  - **Mostrar** O Texto de Introdução do artigo será exibido no artigo completo.
  - **Ocultar** Apenas a parte do artigo após a quebra "Leia Mais" será mostrada no artigo completo.
- **Posição das Informações do Artigo**
  - **Acima** Coloca o bloco de informações do artigo acima do texto.
  - **Abaixo** Coloca o bloco de informações do artigo abaixo do texto.
  - **Dividido** Divide o bloco de informações do artigo em 2 blocos separados. Um bloco está acima e o outro está abaixo do texto.
- **Título das Informações do Artigo** Exibe a palavra *Detalhes* no topo do bloco de informações do artigo.
- **Categoria** Mostrar o Título da Categoria do Artigo.
  - **Link da Categoria** Mostrar o título como um link para essa Categoria. Nota: Isso pode ser configurado para layout de blog ou lista com a opção *Escolher um Layout* na aba Categoria.
- **Categoria Pai** Mostrar o Título da Categoria Pai do Artigo.
  - **Link da Categoria Pai** Mostrar o título como um link para essa Categoria. Nota: Isso pode ser configurado para layout de blog ou lista com a opção *Escolher um Layout* na aba Categoria.
- **Associações** Mostrar as bandeiras associadas ou Código de Idioma. Apenas para multilinguagem.
  - **Usar Bandeiras de Imagem** Exibir escolha de idioma como bandeiras de imagem se Associações estiver definido para *Mostrar*.
- **Autor** Mostrar o autor do Artigo.
  - **Link para a Página de Contato do Autor** Mostrar como um link para um layout de Contato para esse autor. Nota: O autor deve ser configurado como um Contato. Além disso, um link não será exibido se houver um valor de Pseudônimo do Autor para o contato.
- **Data de Criação** Mostrar a data de criação do Artigo.
- **Data de Modificação** Mostrar a data de modificação do Artigo.
- **Data de Publicação** Mostrar a data de início da publicação do Artigo.
- **Navegação** Mostrar um link de navegação *Anterior* ou *Próximo*.
- **Link "Leia Mais"** Mostrar o link Leia Mais para conectar da parte do artigo antes da quebra Leia Mais para o resto do Artigo.
- **Leia Mais com Título**
  - *Mostrar* O título do artigo faz parte do link Leia Mais. O link estará no formato "Leia Mais: \[título do artigo\]".
  - *Ocultar* O link será "Leia mais".
- **Limite de Caracteres "Leia Mais"** O número máximo de caracteres do título a ser incluído. Nota: Isso pode impedir que o texto Leia Mais se torne excessivamente longo se o artigo tiver um título muito longo.
- **Tags** Mostrar as tags para cada artigo.
- **Registrar Visualizações** Registrar o número de vezes que o artigo foi visualizado.
- **Visualizações** Mostrar o número de vezes que o artigo foi exibido por um usuário.
- **Links Não Autorizados**
  - *Sim* O Texto de Introdução para artigos restritos será exibido. Clique no link Leia mais exigirá que os usuários façam login para ver o conteúdo completo do artigo.
  - *Não* Artigos que o usuário não está autorizado a visualizar (com base no nível de acesso à visualização do artigo) não aparecerão.
- **Posicionamento dos Links**
  - *Acima* Links são mostrados acima do conteúdo.
  - *Abaixo* Links são mostrados abaixo do conteúdo.

### Aba Layout de Edição

Estas opções controlam o layout da página de edição de artigos.

![Opções de artigos aba de layout de edição](../../../pt/images/articles/articles-options-editing-layout-tab.png)

- **Permitir Captcha ao enviar** Selecione o plugin de captcha que será utilizado no formulário de envio de artigo. Se *Usar Global* estiver selecionado, certifique-se de que um plugin de captcha esteja selecionado na Configuração Global.
- **Opções de Publicação** Ocultar a aba de Opções de Publicação no Backend ao editar artigos. Isso significa que os usuários do Backend não poderão editar os campos nesta aba. Esses campos sempre estarão definidos para seus valores padrão.
- **Opções de Artigo** Ocultar a aba de Opções de Artigo no Backend ao editar artigos. Isso significa que os usuários do Backend não poderão editar os campos nesta aba. Esses campos sempre estarão definidos para seus valores padrão.
- **Opções de Tela de Edição** Ocultar a aba Configurar Tela de Edição ao editar artigos.
- **Permissões do Artigo** Ocultar a aba de Permissões ao editar artigos.
- **Associações Multilingues** Ocultar a aba de Associações ao editar artigos.
- **Ativar Versões** Salvar histórico de versões para Artigos e Categorias.
- **Número Máximo de Versões** O número máximo de versões a serem armazenadas para um Artigo ou Categoria. Se um Artigo ou Categoria for salvo e o número máximo de versões for alcançado, a versão mais antiga será excluída automaticamente. Se definido como "0", as versões nunca serão excluídas automaticamente.
- **Imagens e Links do Frontend** Ocultar a aba de Imagens e Links na tela do editor de artigos do Frontend.
- **Imagens e Links do Administrador** Ocultar a aba de Imagens e Links no Backend ao editar artigos.
- **URL A Janela de Alvo** Define o valor padrão para o alvo do primeiro Link no artigo. As opções são:
  - *Abrir na janela principal* Abre na janela principal do navegador, substituindo o artigo atual do Joomla.
  - *Abrir em nova janela* Abre o link em uma nova janela do navegador.
  - *Abrir em popup* Abre o link em uma janela de navegador popup (sem controles de navegação completos).
  - *Modal* Abre o link em uma janela popup modal.
- **URL B Janela de Alvo** Define o valor padrão para o alvo do segundo Link no artigo. Mesmas opções que a URL A.
- **URL C Janela de Alvo** Define o valor padrão para o alvo do terceiro Link no artigo. Mesmas opções que a URL A.
- **Classe da Imagem de Introdução** Define o atributo de classe para uma Imagem de Introdução selecionada no campo Imagem de Introdução.
- **Classe da Imagem de Texto Completo** Define o atributo de classe para uma Imagem de Artigo Completo selecionada no campo Imagem de Artigo Completo.

### Aba Categoria

Essas configurações se aplicam às Opções de Categoria de Artigos, a menos que sejam alteradas pelas configurações individuais de categoria ou menu.

![Opções de artigos aba categoria](../../../pt/images/articles/articles-options-category-tab.png)

- **Escolher um Layout** Selecione o layout padrão para exibir quando um link de Categoria for selecionado.
- **Título da Categoria** Mostrar o título da categoria.
- **Descrição da Categoria** Mostrar a descrição da categoria.
- **Imagem da Categoria** Mostrar a imagem da categoria.
- **Níveis de Subcategorias** Controlar quantos níveis de subcategorias exibir.
- **Categorias Vazias** Mostrar categorias que não contêm artigos ou subcategorias.
- **Mensagem de Sem Artigos** Mostrar uma mensagem "Não há artigos nesta categoria".
- **Título das Subcategorias** Mostrar as Subcategorias como subtítulo na página.
- **Descrições das Subcategorias** Mostrar as descrições das subcategorias.
- **\# Artigos na Categoria** Mostrar uma contagem do número total de artigos em cada categoria.
- **Tags** Mostrar as tags para a categoria.

### Aba Categorias

Essas configurações se aplicam às Opções de Categorias de Artigos, a menos que sejam alteradas pelas configurações individuais de categoria ou menu.

![Opções de artigos aba categorias](../../../pt/images/articles/articles-options-categories-tab.png)

- **Descrição da Categoria de Nível Superior** Mostrar a descrição para a categoria de nível superior.
- **Níveis de Subcategorias** Controlar quantos níveis de subcategorias exibir.
- **Categorias Vazias** Mostrar categorias que não contêm artigos ou subcategorias.
- **Descrições das Subcategorias** Mostrar a descrição das subcategorias.
- **\# Artigos na Categoria** Mostrar uma contagem do número total de artigos em cada categoria.

### Aba Layouts de Blog/Destaque

Essas configurações se aplicam a layouts de blog ou destaque, a menos que sejam alteradas para um item de menu específico.

![Opções de artigos aba layouts de blog e destaque](../../../pt/images/articles/articles-options-blog-layouts-tab.png)

- **\# Artigos Principais** Número de Artigos a serem mostrados usando a largura total da área de exibição principal. "0" significa que nenhum Artigo será exibido usando a largura total. Se um Artigo tiver uma quebra "Leia mais...", apenas a parte do texto antes da quebra (o texto de Introdução) será exibida.
- **Classe do Artigo Principal** Adicione qualquer classe CSS para personalizar o layout. Adicione uma borda superior com a classe boxed. Para posição de imagem, use por exemplo imagem-esquerda, imagem-direita. Adicione imagem-alternada para ordenação alternada de imagens de introdução.
- **\# Artigos de Introdução** Determina o número de Artigos a serem exibidos após o Artigo principal. Esses Artigos serão exibidos no número de colunas definido no parâmetro Colunas abaixo. Se um Artigo tiver uma quebra "Leia mais...", apenas o texto antes da quebra (texto de introdução) será exibido, seguido por um link "Leia mais...". A ordem na qual os artigos são exibidos é determinada pelos parâmetros Ordem da Categoria e Ordem do Artigo abaixo.
- **Classe do Artigo** Adicione qualquer classe CSS para personalização de estilo. Adicione uma borda superior com a classe boxed. Para posição de imagem, use por exemplo imagem-esquerda, imagem-direita. Adicione imagem-alternada para ordenação alternada de imagens de introdução.
- **\# Colunas** O número de colunas a serem usadas na área de Artigos de Introdução. Isso normalmente varia de 1 a 3 (dependendo do modelo em uso). Se 1 for usado, os Artigos de Introdução serão exibidos usando a largura total da área de exibição, assim como os Artigos Principais.
- **Direção Multi-Coluna** Em layouts de blog multi-colunas, se deve ordenar os artigos para Baixo nas colunas ou Ao Longo das colunas.
  - *Para Baixo* Ordena os artigos indo para baixo na primeira coluna e depois indo para a próxima coluna.
  - *Ao Longo* Ordena os artigos indo ao longo das colunas e depois voltando para a primeira coluna.
- **\# Links** O número de Links a serem exibidos na área de Links da página. Esses links permitem que um Usuário se conecte a Artigos adicionais, se houver mais Artigos do que cabem na primeira página do Layout de Blog.
- **Incluir Subcategorias**
  - *Nenhuma* Apenas artigos da categoria atual serão exibidos.
  - *Toda* Todos os artigos da categoria atual e todas as subcategorias serão exibidos.
  - *1-5* Todos os artigos da categoria atual e subcategorias até e incluindo esse nível serão exibidos.
- **Imagem de Introdução Vinculada** Se Sim, um clique na imagem de introdução exibirá o artigo.

### Aba Layouts de Lista

Essas configurações se aplicam às Opções de Layouts de Lista, a menos que sejam alteradas para um item de menu ou categoria específico.

![Opções de artigos aba layouts de lista](../../../pt/images/articles/articles-options-list-layouts-tab.png)

- **Exibir Seleção** Mostrar o controle Exibir \# que permite ao usuário selecionar o número de artigos a exibir.
- **Campo de Filtro** Mostrar um campo de texto no Frontend onde um usuário pode filtrar os artigos. Opções no menu de edição do item de Backend.
  - *Ocultar* Não mostrar um campo de filtro.
  - *Título* Filtrar pelo título do artigo.
  - *Autor* Filtrar pelo nome do autor.
  - *Visualizações* Filtrar pelo número de visualizações do artigo.
  - *Tags* Filtrar pelas tags do artigo.
  - *Mês (publicado)* Filtrar pelo mês dos artigos publicados.
- **Cabeçalhos de Tabela** Mostrar um cabeçalho na lista de artigos no Frontend.
- **Data** Mostrar uma data na lista.
  - *Ocultar* Não mostrar nenhuma data.
  - *Criada* Mostrar a data de criação.
  - *Modificada* Mostrar a data da última modificação.
  - *Publicada* Mostrar a data de início da publicação.
- **Visualizações** Mostrar o número de visualizações dos artigos.
- **Autor** Mostrar o nome do autor.
- **\# Artigos a Listar** Número de artigos mostrados na lista.

### Aba Compartilhada

Essas configurações se aplicam às Opções Compartilhadas em layouts de Lista, Blog e Destaque, a menos que sejam alteradas pelas configurações de menu.

![Opções de artigos aba compartilhada](../../../pt/images/articles/articles-options-shared-tab.png)

- **Ordem da Categoria**
  - *Sem Ordem* Os artigos são ordenados apenas pela Ordem dos Artigos, sem considerar a Categoria.
  - *Título Alfabético* Categorias são exibidas em ordem alfabética (A a Z).
  - *Título Reverso Alfabético* Categorias são exibidas em ordem alfabética reversa (Z a A).
  - *Ordem da Categoria* Categorias são ordenadas de acordo com a coluna Ordem inserida em Artigos: Categorias.
- **Ordem do Artigo**
  - *Mais Recentes Primeiro* Artigos são exibidos começando com os mais recentes e terminando com os mais antigos.
  - *Mais Antigos Primeiro* Artigos são exibidos começando com os mais antigos e terminando com os mais recentes.
  - *Título Alfabético* Artigos são exibidos por Título em ordem alfabética (A a Z).
  - *Título Reverso Alfabético* Artigos são exibidos por Título em ordem alfabética reversa (Z a A).
  - *Autor Alfabético* Artigos são exibidos por Autor em ordem alfabética (A a Z).
  - *Autor Reverso Alfabético* Artigos são exibidos por Autor em ordem alfabética reversa (Z a A).
  - *Mais Visualizados* Artigos são exibidos pelo número de visualizações, começando pelos com mais visualizações e terminando pelos com menos visualizações.
  - *Menos Visualizados* Artigos são exibidos pelo número de visualizações, começando pelos com menos visualizações e terminando pelos com mais visualizações.
  - *Ordenação* Artigos são ordenados de acordo com a coluna Ordem inserida em Artigos.
  - *Ordenação Reversa* Artigos são ordenados de forma reversa à de acordo com a coluna Ordem inserida em Artigos.
- **Data para Ordenação** A data usada quando os artigos são classificados por data.
  - *Criada* Use a data de criação do artigo.
  - *Modificada* Use a data de modificação do artigo.
  - *Publicada* Use a data de início da publicação do artigo.
- **Paginação** Paginação fornece links de página na parte inferior da página que permitem ao Usuário navegar para páginas adicionais. Estes são necessários se os Artigos não couberem em uma página.
  - *Ocultar* Links de paginação não são mostrados. Nota: Os usuários não poderão navegar para páginas adicionais.
  - *Mostrar* Links de paginação são mostrados se necessário.
  - *Auto* Links de paginação são mostrados se necessário.
- **Resumo da Paginação** Mostrar o número da página atual e o total de páginas (por exemplo, "Página 1 de 2") na parte inferior de cada página.
- **Artigos em Destaque**
  - *Mostrar* Exibir artigos em destaque e artigos não em destaque.
  - *Ocultar* Exibir apenas artigos não em destaque.
  - *Apenas* Exibir apenas artigos em destaque.

### Aba Integração

Essas configurações determinam como o Componente de Artigos será integrado com outras extensões.

![Opções de artigos aba integração](../../../pt/images/articles/articles-options-integration-tab.png)

#### Painel de Feed de Notícias

- **Link de Feed RSS** Se configurado para Mostrar, um Link de Feed será exibido como um ícone de feed na barra de endereços da maioria dos navegadores.
- **Incluir no Feed**
  - *Texto de Introdução* Apenas o texto de introdução do artigo será exibido no feed.
  - *Texto Completo* O texto completo do artigo será exibido no feed.
- **Link "Leia Mais"** Mostrar um link "Leia mais" no feed.

#### Painel de Roteamento

- **Remover IDs das URLs** Remove o ID do banco de dados dos artigos em um link.

#### Painel de Campos Personalizados

- **Editar Campos Personalizados** Habilitar a criação de campos personalizados.

#### Painel de Fluxo de Trabalho

- **Habilitar Fluxo de Trabalho** Usar fluxos de trabalho personalizados para gerenciar artigos.

## Dicas

- Usuários novatos podem manter os valores padrão aqui.
- Usuários experientes podem economizar tempo criando valores padrão apropriados aqui. Novos itens de menu e artigos poderão então usar os valores padrão para a maioria das opções.
- Todos os valores configurados aqui podem ser substituídos no nível do item de menu, categoria ou artigo.

*Traduzido por openai.com*


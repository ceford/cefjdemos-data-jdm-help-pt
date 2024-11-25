<!-- Filename: Help4.x:Glossary / Display title: Glossário -->

O Glossário do Joomla! é útil para explicar os termos comuns usados nos tutoriais, telas de ajuda e documentação avançada do Joomla!.
## Lista de Controle de Acesso

## Apelido

## Âncora

Uma âncora é criada usando a tag `<a>` no HTML. Uma âncora permite que você coloque um marcador dentro de uma página HTML. No Joomla!, você pode colocar uma âncora dentro de um artigo (por exemplo, usando o editor TinyMCE). Isso permite que você crie um link que irá diretamente para esse ponto do artigo.

O código fonte HTML para uma âncora é como o seguinte:

```html
<a name="my_anchor" title="Minha Âncora"></a>
```

Você pode vincular a uma âncora dentro da mesma página usando o código HTML

```html
<a href="#my_anchor"></a>
```

Clicar nesse link levará você diretamente ao local da tag de âncora.

Você pode vincular a uma âncora em uma página diferente anexando "#" mais o nome da âncora ao final do URL. No exemplo acima, se o URL do artigo fosse `http://www.mysite.com/my_article.html`, então você poderia vincular diretamente à âncora nessa página com o URL `http://www.mysite.com/my_article.html#my_anchor`.

## Artigo

## Folha de Estilo em Cascata (CSS)

Uma Folha de Estilo em Cascata ou CSS é usada para controlar a apresentação de uma página XHTML. Por exemplo, um arquivo CSS costuma controlar a fonte, margens, cor, gráficos de fundo e outros aspectos da aparência de uma página web. O CSS permite que você separe o conteúdo de uma página XHTML da sua aparência. No Joomla!, os arquivos CSS (por exemplo, template.css) normalmente fazem parte do template.

**Veja também:** Template, Sufixo de Classe de Página, Sufixo de Classe de Módulo

## Categoria

Toda parte de um site Joomla! ou de qualquer tipo de CMS precisa de um método para exibir e armazenar seu conteúdo de forma lógica. O método usual é por categorias e subcategorias. O Joomla! permite diversas maneiras de exibir e usar conteúdo controlado por categorização. Alguns dos tipos de conteúdo que possuem categorização são Artigos (o conteúdo principal das páginas da web), Banners e Contatos.

Uma categoria chamada *Sem Categoria* é a categoria padrão atribuída à maioria dos tipos de conteúdo. A categoria *Sem Categoria* não é descritiva e deve ser usada conforme necessário para tipos de conteúdo que não se encaixam em uma categoria específica.

Ao criar e atribuir categorias, você deve ter uma estrutura planejada. Como exemplo, esta é uma forma de categorizar vários artigos sobre pássaros:

- Crie duas categorias de artigos de nível superior chamadas *Animais* e *Plantas*.
- Sob a categoria *Animais*, crie subcategorias chamadas *Aves* e 
  *Mamíferos*.
- Sob a subcategoria *Aves*, crie categorias intituladas *Falcões*, *Papagaios* 
  e *Pardais*. Esta é a estrutura de categorias resultante:

```
- Animais
  - Aves
    - Falcões
    - Papagaios
    - Pardais
  - Mamíferos
```

Agora você pode criar vários artigos nas subcategorias Falcão, Papagaio e Pardal usando os diferentes gêneros ou nomes comuns dos tipos específicos desses pássaros.

## Chrome

Os recursos visíveis da interface gráfica de um aplicativo são
às vezes chamados de *chrome*.  

## Componente

## Núcleo

A palavra *núcleo* no Joomla! refere-se aos arquivos distribuídos necessários para criar e administrar um site com um CMS Joomla. O núcleo do Joomla contém toda a funcionalidade necessária para criar e gerenciar um novo site de forma rápida e fácil.  

## Prefixo da Tabela do Banco de Dados

O prefixo da tabela do banco de dados é uma string (de alguns caracteres) adicionada ao início do nome das tabelas do Joomla!. Usar um prefixo permite que você execute várias instalações do Joomla! usando um único banco de dados.

O prefixo da tabela do banco de dados pode ser definido durante a instalação. Alterá-lo posteriormente é possível, mas requer acesso ao banco de dados através de um meio não-Joomla ou uma extensão Joomla, como o Akeeba Admin Tools, e causará algum tempo de inatividade.

Os desenvolvedores de extensões precisam usar a string `#__` para representar o prefixo. Esta será substituída pelo prefixo real em tempo de execução.

## Extensão

## LDAP

## Idioma

Os idiomas são talvez o tipo de extensão mais básico e crítico. Os idiomas são disponibilizados como um pacote de idioma principal ou um pacote de idioma de extensão. Esses pacotes consistem em arquivos INI que contêm pares de chave/valor para fornecer a tradução de cadeias de texto estáticas dentro do código-fonte do Joomla!. Isso permite que tanto o núcleo do Joomla! como os componentes e módulos de terceiros sejam internacionalizados. Os pacotes de idioma principal também incluem um arquivo meta XML que descreve o idioma e fornece informações sobre as fontes a serem usadas para geração de conteúdo PDF.

## Menu

No Joomla!, um **Menu** é um módulo que contém um conjunto de **itens de menu** usados para navegação. Cada item de menu define um URL para uma página no site. Ele contém configurações que controlam a exibição do conteúdo e do estilo da página.

## Model-View-Controller

O Joomla faz uso extensivo do padrão de design
<a href="http://en.wikipedia.org/wiki/Model-view-controller"
class="external text" target="_blank"
rel="nofollow noreferrer noopener">Model-View-Controller</a>.

Quando o Joomla é iniciado para processar uma solicitação de um usuário, como um GET
para uma página específica, ou um POST contendo dados de formulário, uma das primeiras
coisas que o Joomla faz é analisar a URL para determinar qual
componente será responsável por processar a solicitação e passar
o controle para esse componente.

Se o componente foi projetado de acordo com o padrão MVC, ele passará
o controle para o controlador. O controlador é responsável por
analisar a solicitação e determinar quais modelos serão necessários para
satisfazer a solicitação, e qual visão deve ser usada para retornar os resultados
ao usuário.

O modelo encapsula os dados utilizados pelo componente. Na maioria dos casos,
esses dados virão de um banco de dados, seja o banco de dados do Joomla, ou algum
banco de dados externo, mas também é possível que o modelo obtenha dados
de outras fontes, como através de uma API de serviços web em execução em outro
servidor. O modelo também é responsável por atualizar o banco de dados quando
apropriado. O propósito do modelo é isolar o controlador e
visão dos detalhes de como os dados são obtidos ou alterados.

A visão é responsável por gerar a saída que é enviada ao
navegador pelo componente. Ela chama o modelo para qualquer informação que
precise e a formata de maneira apropriada. Por exemplo, uma lista de itens de dados
puxados do modelo poderia ser embalada em uma tabela HTML pela visão.

Como o Joomla é projetado para ser altamente modular, a saída do
componente geralmente é apenas parte da página web completa que o usuário
verá no fim. Uma vez que a visão gerou a saída, o
componente retorna o controle de volta ao framework do Joomla, que então carrega
e executa o template. O template combina a saída do
componente e quaisquer módulos que estejam ativos na página atual, para que
possa ser entregue ao navegador como uma página única.

Para proporcionar maior poder e flexibilidade aos web designers, que podem estar
apenas interessados em criar novos designs ao invés de manipular o
código subjacente, o Joomla divide a visão tradicional em uma visão
separada e layout. A visão puxa dados do modelo, como em um padrão MVC
tradicional, mas então simplesmente disponibiliza esses dados para o layout, que
é responsável por formatar os dados para apresentação ao usuário. A
vantagem de ter essa divisão é que o sistema de templates do Joomla
fornece um mecanismo simples para que layouts sejam sobrescritos no
template. Esses sobrescritos de layout (frequentemente chamados de "sobrescritos de template"
porque fazem parte do template, embora na verdade seja o
layout que está sendo sobrescrito) são agrupados com o template e dão
ao designer do template controle completo sobre toda a saída do
núcleo do Joomla e quaisquer extensões de terceiros instaladas que cumpram com
o padrão de design MVC.

## Módulo

## Sufixo de Classe de Módulo

Um Sufixo de Classe de Módulo é um parâmetro usado em módulos para adicionar uma nova classe CSS a um módulo. Ele é usado em conjunto com os estilos definidos em um arquivo user.css para alterar a aparência padrão de um módulo.

O novo nome de classe pode ser usado para adicionar qualquer estilo desejado ao módulo sem a necessidade de recriar todo o código CSS existente. Note que, se você criar um novo nome de classe, certifique-se de que ele tenha um nome exclusivo e não entre em conflito com nenhum nome de classe existente.

## Posição do Módulo

## Módulo chrome

## PHP

PHP é uma linguagem de script de computador projetada para criar páginas web dinâmicas. PHP é amplamente utilizado para desenvolvimento web e pode ser incorporado ao HTML. Geralmente, ele é executado em um servidor web, recebendo código PHP como entrada e gerando páginas web como saída. Joomla! é principalmente escrito usando a linguagem PHP.  

## Sufixo de Classe de Página

Um Sufixo de Classe de Página é um parâmetro usado em itens de menu de conteúdo para adicionar uma nova classe CSS ao layout da página. Ele é utilizado em conjunto com estilos definidos em um arquivo user.css para alterar a aparência padrão de um módulo.

O novo nome da classe pode ser usado para adicionar qualquer estilo desejado à página sem a necessidade de recriar todo o código CSS existente. Observe que, se você criar um novo nome de classe, certifique-se de que ele tenha um nome exclusivo e que não entre em conflito com nenhum nome de classe existente.

## Remendo

## Plugin

## URLs Amigáveis para Motores de Busca

URLs amigáveis para motores de busca é um termo comumente abreviado como URLs SEF ou simplesmente SEF. URLs normais do Joomla! se parecem com isto:

    http://www.seusite.org/index.php?option=com_content&view=section&id=3&Itemid=41

Opcionalmente, você pode fazer com que as URLs se pareçam com páginas HTML estáticas como esta:

    http://www.seusite.org/perguntas-frequentes.html

Existem opções integradas para gerar URLs SEF. Estas são ativadas nas *Configurações de SEO* (Otimização para Motores de Busca) na aba Site da página de Configuração Global. Existem também extensões de terceiros que criam URLs SEF para Joomla!.

## Menus divididos

Um menu dividido é quando diferentes níveis de um único menu são exibidos em dois ou mais locais em uma única página da web.

Por exemplo, uma exigência comum é que um menu de itens de nível superior apareça no topo da página. Quando um desses itens é clicado, o usuário é levado a uma página onde um menu secundário, digamos, no lado esquerdo da página, mostra itens de segundo nível dentro do escopo do item de nível superior.

Os menus aparecem em locais separados na página, mas estão relacionados porque um mostra apenas itens de nível superior, enquanto o outro mostra itens de segundo nível. Esta ideia pode ser estendida para incluir menus para itens de terceiro nível e além.

Isso pode ser implementado no Joomla usando um único menu multinível e, em seguida, criando mais de um módulo de menu, cada um referindo-se a um nível diferente.

## Modelo

Um modelo é um tipo de extensão do Joomla! que controla a aparência da página.
- Um modelo do site controla a aparência pública do conteúdo do site.
- Um modelo de administrador controla a aparência do site para tarefas administrativas, tais como: gerenciamento de usuários, menus, artigos, categorias, módulos, componentes, plugins e modelos.

## Estilo de modelo

## Pacote de Atualização

Um Pacote de Atualização no Joomla! é um conjunto de arquivos que contém os arquivos que mudaram entre as versões do Joomla!. Quando este arquivo é descompactado, ele substitui a versão antiga dos arquivos modificados pela nova versão. Por exemplo, se cinquenta arquivos foram alterados entre as versões 5.1 e 5.2, o pacote de atualização conteria esses cinquenta arquivos e instruções sobre como executar a atualização. Às vezes, isso inclui atualizações de banco de dados e remoção de arquivos que não são mais usados.


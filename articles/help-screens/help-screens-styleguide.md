<!-- Filename: Help4.x:Help_screens_styleguide / Display title: Guia de Estilo para Telas de Ajuda -->

<div class="alert alert-warning">
Este guia de estilo é para a instalação do Joomla MediaWiki (docs.joomla.org).
</div>

Este é um trabalho em andamento e deve ser utilizado como uma diretriz para a criação de telas de ajuda para o **Joomla 3.x**. As telas de ajuda que existem no Wiki do Joomla! Docs estão sendo acessadas por todas as instalações do Joomla! que utilizam o sistema de ajuda padrão. Ao seguir este guia de estilo, o Projeto Joomla! pode oferecer consistência em todas as telas de ajuda para facilitar a navegação.

Se você tiver alguma dúvida, por favor, poste na página de discussão associada à tela de ajuda clicando na aba ***Discussão*** no topo da página da tela de ajuda.

## Layout da Tela de Ajuda

### Descrição

Cada tela de ajuda deve ter uma seção "**Descrição**". Esta seção detalha o que a tela faz e é utilizada nas tabelas de telas de ajuda ao longo deste wiki. <a href="https://docs.joomla.org/Menu_Management#Menu_Management_Help_Screens" class="mw-redirect" title="Menu Management">Aqui está um exemplo de uso</a>.

Não há um formato específico para esta seção, pois a descrição deve estar diretamente correlacionada com o propósito e a funcionalidade da tela. Pode haver subseções na descrição que abordem detalhes mais específicos. Tente manter a descrição breve e direta. Se a descrição for longa, considere usar marcadores para resumi-la.

## Como Acessar

Cada tela de ajuda deve ter uma seção **Como Acessar** que fornece os passos necessários para chegar à tela que está sendo descrita. Isso pode ser redundante, pois um usuário deve estar na tela do administrador para ter acessado a tela de ajuda. Lembre-se de que as telas de ajuda podem ser acessadas de várias maneiras. Por exemplo, alguém que usa um mecanismo de busca para descobrir como fazer algo pode encontrar uma tela de ajuda no wiki sem nunca ter acessado o sistema de ajuda.

#### Notas:

- Se a maneira de acessar a tela for a partir de outra tela, então o nome
  dessa tela deve ser um link para sua tela de ajuda.
- Você "clica" em botões, incluindo botões de barra de ferramentas, mas você "seleciona"
  itens de menu. O uso consistente desta terminologia deve ajudar os usuários.
- Para facilitar a renderização, a seta para a direita (→), **Este
  apontando → para aquele**.

### Captura de Tela

Captura de tela mostrando a aparência geral da tela.

#### Notas:

- As imagens de captura de tela podem ter qualquer largura, mas imagens maiores devem ter o
  \|800px adicionado na fonte.
- O nome do arquivo deve seguir nossas
  <a href="https://docs.joomla.org/JDOC:Image_naming_convention"
  class="mw-redirect" title="JDOC:Image naming convention">convenções padrão de nomenclatura
  </a> para telas de ajuda.
  **Help-3x-***\<caminho-do-sistema-de-menu-em-minúsculas-separado-por-hífens\>***-screen-en.png**.
  Por exemplo, uma captura de tela da tela do Gerenciador de Artigos seria
  **\[\[Arquivo:Help-3x--content-article-manager-screen-en.png\]\]**.
- O nome do arquivo deve sempre incluir um código de idioma no final do
  nome; para inglês, -en é adicionado.
- Você pode usar arquivos .png ou .jpg.

## Campos do Formulário (por Aba)

### Aba de Detalhes

Esta seção deve ser incluída apenas em telas de ajuda que descrevem telas que incluem um formulário. Isso inclui todas as telas de adicionar/editar, mas também inclui telas como Configuração Global do Site e pop-ups modais como <a href="https://docs.joomla.org/Help4.x:Components_Article_Manager_Options" title="Help4.x:Components Article Manager Options">Help4.x:Components Article Manager Options</a>.

### Outros Tipos de Aba

Se os campos estiverem agrupados em conjuntos de campos ou abas, agrupe os campos sob subtítulos.

### Cabeçalhos de Coluna

Esta seção deve ser incluída apenas em telas de ajuda que descrevem telas de gerenciadores de back-end; ou seja, onde você tem uma lista de itens sendo mostrada. Esta seção deve descrever cada uma das colunas da lista.

### Filtros de Lista

Esta seção deve ser incluída apenas em telas de ajuda que descrevem telas de gerenciadores de back-end; ou seja, onde você tem uma lista de itens sendo mostrada. Esta seção deve descrever como usar os filtros de lista para filtrar o conteúdo da tela. Veja <a href="https://docs.joomla.org/Screen.content.15#List_Filters" title="Screen.content.15">Screen.content.15#List_Filters</a> como exemplo da versão 1.5.

### Opções

Esta seção deve ser incluída apenas em telas de ajuda onde a tela possui um botão de barra de ferramentas "Opções", que abre uma sub-tela de opções modal. Se houver muitas opções e a tela de ajuda ficaria excessivamente longa se fossem descritas aqui, então vincule a uma tela de ajuda separada com um sufixo "\_Options". Por exemplo, veja <a href="https://docs.joomla.org/Help4.x:Components_Article_Manager_Options" title="Help4.x:Components Article Manager Options">Components Article Manager Options</a>.

Como a tela modal de Opções geralmente é dividida em abas, você deve adicionar uma subseção sob essa seção para cada aba. Por exemplo, se houver uma aba rotulada "Configuração de Edição", então você deve adicionar um cabeçalho de terceiro nível com esse nome e dentro dessa subseção você deve descrever cada um dos campos disponíveis. Você deve iniciar cada subseção com uma captura de tela do painel de Opções apropriado.

### Barra de Ferramentas

Obviamente, esta seção deve ser incluída apenas em telas de ajuda onde uma barra de ferramentas está presente.

Descreve os botões disponíveis e suas funções associadas. Use **fragmentos** aqui porque muitos serão iguais para diferentes telas. É melhor fornecer uma imagem da barra de ferramentas.

A primeira palavra deve sempre ser um verbo e, a menos que seja um verbo irregular, também deve terminar com a letra "s". Isso significa que você deve estruturar a descrição como se estivesse usando a palavra "isso" como o sujeito, mas deixe o sujeito fora da frase. Isso fará com que a frase seja, na verdade, um fragmento de frase. Por exemplo:

- Em vez de "Para encontrar tesouros escondidos, clique neste botão."
  - Diga, "Encontra tesouros escondidos."
- Em vez de "Você pode clicar neste botão para inserir uma imagem de John Stamos no documento atual."
  - Diga, "Insere uma imagem de John Stamos."
- Em vez de "Informe-se que uma imagem de John Stamos é a mesma coisa que um tesouro escondido."
  - Diga, "Informa que uma imagem de John Stamos é a mesma coisa que um tesouro escondido."

Como muitas barras de ferramentas são as mesmas em várias telas, a convenção de nomenclatura de arquivos de imagem para barras de ferramentas visa facilitar o reuso das imagens de barras de ferramentas sempre que possível. As imagens da barra de ferramentas devem seguir esta convenção de nomenclatura: Help\<versão\>-Toolbar-\<listadeícones\>.png onde \<listadeícones\> é uma lista separada por '-' das legendas da barra de ferramentas. Cada palavra deve ser capitalizada, espaços e '&' removidos. Por exemplo: Help30-Toolbar-New-Edit-Delete-Options-Help.png

### Processo em Lote

Esta seção deve ser incluída apenas em telas de ajuda onde a tela possui um recurso de processo em lote. Por exemplo, veja <a href="https://docs.joomla.org/Help4.x:Components_Banners_Categories" title="Help4.x:Components Banners Categories">Help4.x:Components Banners Categories</a>.

### Dicas

Como o nome sugere, esta seção deve incluir dicas, sugestões ou sugestões que possam ajudar o usuário a realizar tarefas envolvendo a tela.


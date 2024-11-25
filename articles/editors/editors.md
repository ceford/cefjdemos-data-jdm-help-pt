<!-- Filename: Help4.x:Editors / Display title: Editores -->

## TinyMCE

TinyMCE é o editor padrão para usuários Frontend e Backend. O editor permite que os usuários tenham uma interface de processamento de texto familiar para usar ao editar Conteúdo.

O TinyMCE pode ser configurado com 3 conjuntos diferentes de botões de ferramentas. Isso é definido no plugin Editor - TinyMCE.

### Barras de Ferramentas

#### Preset Simples

O conjunto de ferramentas 2 fornece uma linha de botões, como mostrado abaixo. O conjunto é atribuído por padrão ao grupo de usuários Públicos.

<img
src="https://docs.joomla.org/images/thumb/5/52/Help-4x-editor-tinymce-simple-en.png/600px-Help-4x-editor-tinymce-simple-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/5/52/Help-4x-editor-tinymce-simple-en.png/900px-Help-4x-editor-tinymce-simple-en.png 1.5x, https://docs.joomla.org/images/thumb/5/52/Help-4x-editor-tinymce-simple-en.png/1200px-Help-4x-editor-tinymce-simple-en.png 2x"
data-file-width="1451" data-file-height="80" width="600" height="33"
alt="barra de ferramentas tinymce configuração simples" />

- Os botões permitem que você deixe o texto em: negrito, sublinhado ou tachado.
- Desfazer e Refazer.
- Lista não ordenada, Lista ordenada.
- Colar como Texto: Frequentemente, ao copiar e colar texto de outras fontes, como arquivos PDF, documentos de Texto ou páginas da web, o texto selecionado contém informações de formatação que não são necessárias ou desejadas. Usar o 'Colar como Texto' removerá toda a formatação do texto.

#### Preset Médio

O conjunto de ferramentas 1 fornece duas linhas de botões, como mostrado abaixo. O conjunto é atribuído por padrão ao grupo de usuários Gerente e Registrado.

<img
src="https://docs.joomla.org/images/thumb/0/07/Help-4x-editor-tinymce-advanced-en.png/800px-Help-4x-editor-tinymce-advanced-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/07/Help-4x-editor-tinymce-advanced-en.png/1200px-Help-4x-editor-tinymce-advanced-en.png 1.5x, https://docs.joomla.org/images/thumb/0/07/Help-4x-editor-tinymce-advanced-en.png/1600px-Help-4x-editor-tinymce-advanced-en.png 2x"
data-file-width="1977" data-file-height="236" width="800" height="95"
alt="barra de ferramentas tinymce configuração média" />

Esta opção fornece todos os mesmos botões documentados na barra de ferramentas do Conjunto 2 acima. Além disso, as seguintes opções estão disponíveis.

#

#### Médio: Primeira Linha

- Conteúdo CMS: A lista suspensa fornece acesso para vincular a um Artigo, Contato, Campo, Mídia, Menu ou Módulo.

Artigo: O exemplo mostra como criar facilmente um link para qualquer artigo no site atual.

<img
src="https://docs.joomla.org/images/thumb/5/52/Help-4x-article-quick-link-button-en.png/600px-Help-4x-article-quick-link-button-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/5/52/Help-4x-article-quick-link-button-en.png/900px-Help-4x-article-quick-link-button-en.png 1.5x, https://docs.joomla.org/images/thumb/5/52/Help-4x-article-quick-link-button-en.png/1200px-Help-4x-article-quick-link-button-en.png 2x"
data-file-width="2304" data-file-height="1321" width="600" height="344"
alt="diálogo de seleção de artigo" />

Para criar um link para o artigo desejado:

- Coloque o cursor no ponto do artigo onde você deseja que o título do artigo vinculado seja inserido.
- Clique no botão Artigo para abrir a janela.
- Clique no título para selecionar o artigo desejado na janela. Você pode usar a pesquisa e os filtros para ajudar a encontrar o artigo desejado.
- Um link com o título do artigo será inserido na localização atual do cursor.
- Se necessário, você pode editar o texto do link.

Da mesma forma, você pode vincular outros itens, como Mídia, Módulos, e assim por diante.

Quebra de Página: Este botão permite inserir uma quebra de página dentro de um artigo. Uma quebra de página permite a navegação da página quando o artigo é exibido em um layout. Isso é útil para artigos longos. Quando este botão é pressionado, uma janela é exibida, como mostrado abaixo:

<img
src="https://docs.joomla.org/images/thumb/6/66/Help-4x-editor-pagebreak-button-en.png/600px-Help-4x-editor-pagebreak-button-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/6/66/Help-4x-editor-pagebreak-button-en.png/900px-Help-4x-editor-pagebreak-button-en.png 1.5x, https://docs.joomla.org/images/thumb/6/66/Help-4x-editor-pagebreak-button-en.png/1200px-Help-4x-editor-pagebreak-button-en.png 2x"
data-file-width="1542" data-file-height="862" width="600" height="335"
alt="botão de quebra de página" />

- **Título da Página**. Insira o título a ser exibido para a nova página (por exemplo, 'Página 2').
- **Alias do Índice**. Campo opcional a ser exibido no índice para esta página. Em um artigo de várias páginas, o Joomla exibe um 'índice' para a página que permite ao usuário selecionar qualquer página. Se este campo estiver vazio, o Título da Página será usado. Se você quiser um título diferente no índice, insira-o aqui.
- **Inserir Quebra de Página**. Clique neste botão para inserir a quebra de página com os campos preenchidos. A Quebra de Página será exibida como uma linha cinza pontilhada no artigo. Observe que uma quebra de página não pode ser editada. Se você precisar mudar um campo na quebra de página, clique no artigo logo após a quebra de página, pressione Backspace até que a quebra de página seja excluída e, em seguida, insira uma nova quebra de página com as informações desejadas.
- A configuração é definida no plugin Conteúdo - Quebra de Página.

Leia Mais: Este botão insere uma quebra Leia mais no artigo. Isso aparece como uma linha vermelha pontilhada no artigo.

- Se um artigo tiver uma quebra Leia mais, apenas o texto antes da quebra, chamado de Texto de Introdução, será inicialmente exibido, junto com um link Leia mais. Se o usuário clicar neste link, ou o artigo inteiro ou apenas a parte após o link Leia mais será exibido. Isso depende da configuração dos parâmetros do Texto de Introdução do artigo.
- A quebra Leia mais permite economizar espaço nas páginas exibindo apenas o Texto de Introdução.
- Se você quiser inserir quebras para um artigo exibido em um Layout de Artigo, use o botão Quebra de Página.

Os botões na lista suspensa de conteúdo do CMS podem ser desativados em Plugins - editors-xtd.

- Os botões no canto superior esquerdo permitem tornar o texto em itálico. Ao lado estão os botões para alinhar à esquerda, à direita, centralizado e justificado.
- Formatos: Selecione formatos predefinidos para Títulos, Inline, Blocos e assim por diante.
- Diminuir recuo (mover para a esquerda) e Aumentar recuo (indentar à direita).
- 3 pontos: Mostrar segunda linha da Barra de Ferramentas.

#### Médio: Segunda Linha

- Inserir/editar Link: Para inserir ou editar um link, selecione o texto vinculado e pressione este botão. Um diálogo popup será exibido, permitindo-lhe inserir detalhes sobre o link.
- Remover Link: Para remover um link, destaque o texto vinculado e pressione este botão.
- Âncora: Uma âncora é um marcador dentro de um artigo que permite vincular diretamente a esse ponto no artigo.
- Código-fonte: Um popup é exibido mostrando o código-fonte HTML, permitindo que você edite o código-fonte HTML.
- Inserir uma linha horizontal: Para inserir uma linha horizontal, mova o cursor para o local desejado no artigo e clique neste botão.
- Tabela: Inserir Nova Tabela, Propriedades da Linha da Tabela, Propriedades da Célula da Tabela, Inserir Linha Antes, Inserir Linha Depois, Excluir Linha, Inserir Coluna Antes, Inserir Coluna Depois, Excluir Coluna, Dividir Células Mescladas da Tabela, Mesclar Células da Tabela.
- Subscrito, Sobrescrito, Caractere Especial.
- Pré-visualizar texto em popup.

#### Preset Avançado

O conjunto de ferramentas 0 oferece as opções de edição mais extensas, como mostrado abaixo. O conjunto é atribuído por padrão ao grupo de usuários Administrador, Editor e Superusuários.

<img
src="https://docs.joomla.org/images/thumb/6/6a/Help-4x-editor-tinymce-extended-en.png/800px-Help-4x-editor-tinymce-extended-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/6/6a/Help-4x-editor-tinymce-extended-en.png/1200px-Help-4x-editor-tinymce-extended-en.png 1.5x, https://docs.joomla.org/images/thumb/6/6a/Help-4x-editor-tinymce-extended-en.png/1600px-Help-4x-editor-tinymce-extended-en.png 2x"
data-file-width="1977" data-file-height="393" width="800" height="159"
alt="barra de ferramentas tinymce configuração avançada" />

Esta opção fornece todos os mesmos botões documentados na barra de ferramentas do Conjunto 1 acima. Além disso, as seguintes opções estão disponíveis.

#### Avançado: Primeira Linha

- Blocos: Parágrafo, Títulos, Preformatados.
- Fontes: Selecione a fonte desejada.
- Tamanho da Fonte: Selecione o tamanho da fonte desejado.
- Localizar e Substituir.
- Inserir/editar imagem: Para inserir uma imagem, coloque o cursor no local desejado e pressione este botão. Um diálogo popup será exibido que permite inserir a Fonte, Largura ou Altura e outras informações sobre a imagem.

#### Avançado: Segunda Linha

- Selecionar cor do Texto ou cor de Fundo.
- Tela cheia.
- Emoticons.
- Inserir mídia: Para inserir mídia, coloque o cursor no local desejado e pressione este botão. Um diálogo popup será exibido permitindo que você insira o Tipo, Arquivo ou URL e outras informações sobre a mídia.
- Direção da Esquerda para a Direita ou Direção da Direita para a Esquerda: Esses botões permitem inserir ou alterar a direção do texto, por exemplo, para idiomas que leem da direita para a esquerda.
- Recortar, Copiar, Colar.
- Mostrar caracteres invisíveis (como finais de parágrafo).
- Mostrar blocos.
- Espaço não separável.
- Citação em bloco.
- Inserir Modelo.

#### Avançado: Terceira Linha

- Imprimir o texto do artigo.
- Inserir/editar amostra de código.
- Inserir data/hora.
- Limpar formatação.

### Acessibilidade

TinyMCE é compatível com leitores de tela, como
<a href="https://www.freedomscientific.com/products/software/jaws/"
rel="nofollow noreferrer noopener">JAWS</a> e
<a href="https://www.nvaccess.org/"
rel="nofollow noreferrer noopener">NVDA</a>. Você pode usá-lo efetivamente mesmo sem usar o mouse.

| Tarefa                                   | PC                     | macOS                  |
|------------------------------------------|------------------------|------------------------|
| Focar/saltar para a barra de menu        | Alt+F9                 | ⌥+F9                   |
| Focar/saltar para a barra de ferramentas | Alt+F10                | ⌥+F10                  |
| Focar/saltar para o caminho do elemento  | Alt+F11                | ⌥+F11                  |
| Fechar menu/submenu/diálogo              | Esc                    | esc                    |
| Retornar para a área de conteúdo do editor | Esc                  | esc                    |
| Navegar para a esquerda/direita pelo menu/barra de ferramentas | Tab e as Teclas de Setas | Tab e as Teclas de Setas |

Atalhos de teclado

Veja mais informações:

- <a href="https://www.tiny.cloud/docs/advanced/accessibility/"
  rel="nofollow noreferrer noopener">TinyMCE - Acessibilidade</a>
- Uma lista dos
  <a href="https://www.tiny.cloud/docs/advanced/keyboard-shortcuts/"
  rel="nofollow noreferrer noopener">atalhos de teclado</a> disponíveis (pc, mac) dentro do corpo do editor.

## CodeMirror

O 'Editor - CodeMirror' é projetado para facilitar a inserção de código HTML
em um artigo ou descrição. O CodeMirror suporta realce de sintaxe
e auto-completação, como mostrado nesta captura de tela.

<img
src="https://docs.joomla.org/images/thumb/f/fa/Help-4x-screenshot-editor-codemirror-example-en.png/800px-Help-4x-screenshot-editor-codemirror-example-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/f/fa/Help-4x-screenshot-editor-codemirror-example-en.png/1200px-Help-4x-screenshot-editor-codemirror-example-en.png 1.5x, https://docs.joomla.org/images/thumb/f/fa/Help-4x-screenshot-editor-codemirror-example-en.png/1600px-Help-4x-screenshot-editor-codemirror-example-en.png 2x"
data-file-width="1977" data-file-height="905" width="800" height="366"
alt="exemplo do codemirror" />

- Os botões mostrados abaixo da janela de edição fornecem acesso para vincular a qualquer
  item do site.
- O CodeMirror oferece algumas das mesmas vantagens do uso do 'Editor -
  Nenhum', mas torna um pouco mais fácil trabalhar com código HTML bruto.
- A configuração é definida no plugin do Editor -
  CodeMirror.

## Nenhum

Se 'Editor - Nenhum' for selecionado para um Usuário, então um editor de texto simples é exibido. Isso permite que você insira HTML bruto, não formatado. Você pode usar o botão 'Visualizar' da barra de ferramentas para pré-visualizar como o HTML será exibido.

Note que a opção 'Nenhum' pode ser útil se você estiver inserindo HTML 'modelo' ou personalizado, por exemplo, para criar um link do PayPal. O TinyMCE reformata automaticamente e remove algumas partes do HTML quando um arquivo é salvo. Isso pode fazer com que HTML complexo não funcione corretamente.

Se isso acontecer, você pode temporariamente mudar o editor para 'Nenhum' e criar o conteúdo desejado. Note que, se você quiser editar esse conteúdo no futuro, deve ter cuidado para alterar seu editor para 'Nenhum'. Caso contrário, se você abrir e salvar o conteúdo com o TinyMCE, pode perder seu HTML personalizado.

O plugin 'Editor - Nenhum' não tem configuração.

*Traduzido por openai.com*


<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_Editor_Group / Display title: Grupo de Editores  -->

## Descrição do Grupo

Plugins de editor ajudam os usuários a inserir texto com marcação ou layouts para propósitos especiais, como fragmentos de HTML ou código. Para utilizar um Editor, o desenvolvedor de software marca o campo de entrada de dados como tipo `Editor`. Se nenhum plugin de editor estiver habilitado, ele será exibido como um campo de área de texto simples. Com um ou mais plugins do editor habilitados, o plugin padrão do site é usado, definido na Configuração Global, a menos que seja substituído pelo plugin preferido do usuário, definido no Perfil do Usuário. O Joomla possui os três plugins de editor principais listados abaixo. Plugins de editor adicionais de terceiros podem estar disponíveis. Alguns editores têm uma seleção muito grande de opções.

### Editor - CodeMirror

O editor CodeMirror é um editor de código mais adequado para código-fonte. Ele possui realce de sintaxe de código para muitas linguagens de programação. Ele pode mostrar tags desencontradas e também ajuda a manter a indentação de código consistente.

![Formulário de opções do CodeMirror](../../../en/images/plugins/plugin-group-editor-codemirror.png)

- **Numerar linhas** Exibir números de linha no editor.
- **Dobra de Código** Permite que blocos de código sejam dobrados.
- **Gutters** Marcador de Código e Dobra de Código.
- **Realçar Linha Ativa** Adiciona um destaque à linha na qual o cursor está.
- **Realçar Seleções Correspondentes** Destaca instâncias da palavra selecionada em todo o documento.
- **Corresponder Tags** Destaca tags correspondentes.
- **Corresponder Parênteses** Destaca parênteses correspondentes.
- **Conclusão de Tags** Completa automaticamente as tags.
- **Conclusão de Parênteses** Completa automaticamente os parênteses.
- **Mapa de Teclas** Faz o CodeMirror funcionar como outros editores populares.
- **Alternar Tela Cheia** Seleciona a tecla de função a ser usada para alternar o modo de tela cheia.
- **Usar Modificadores** Seleciona quaisquer teclas modificadoras a serem usadas com a tecla de alternância de tela cheia.

![Formulário de opções avançadas do CodeMirror](../../../en/images/plugins/plugin-group-editor-codemirror-advanced.png)

- **Tema** Define as cores para o editor.
- **Cor da Linha Ativa** A cor a ser usada para destacar a linha ativa. Será exibido com 50% de opacidade.
- **Cor das Tags Correspondentes** A cor de fundo a ser usada para destacar tags correspondentes. Será exibido com 50% de opacidade.
- **Fonte** A fonte a ser usada no editor. Se não estiver instalada, será carregada de https://www.google.com/fonts/.
- **Tamanho da Fonte (px)** O tamanho da fonte no editor.
- **Altura da Linha (em)** A altura de uma linha de texto. Isso é medido em ems, significando que 1.0 é igual ao tamanho da fonte e 2.0 é igual a 2x o tamanho da fonte.
- **Estilo da Barra de Rolagem** Selecione o estilo da barra de rolagem que gostaria que o CodeMirror usasse.
- **Pré-visualização** Um exemplo de como os campos do seu editor CodeMirror ficarão com as configurações atuais (salve para atualizar).

### Editor - Nenhum

Este plugin carrega um editor de texto básico. Esta opção pode ser usada quando você está colando código HTML de outra fonte e não quer que o HTML seja alterado por um editor WYSIWYG. Este plugin não possui opções.

### Editor - TinyMCE

O editor TinyMCE é um editor WYSIWYG e é o editor padrão para entrada de HTML no Joomla!.

![Formulário de opções do plugin TinyMCE](../../../en/images/plugins/plugin-group-editor-tinymce.png)

- **Definir guia de seleção** Selecione a funcionalidade *Conjunto 2*, *Conjunto 1* ou *Conjunto 0*. Com *Conjunto 2* selecionado, você vê o editor para uso *Público*. *Conjunto 1* selecionado é o padrão para Gestores e Registrados, *Conjunto 0* selecionado é o padrão para Administradores, Editores e Super Usuários.

Cada Guia tem uma longa lista de opções que não são ilustradas aqui. A lista a seguir é uma seleção.

- **Tema do Site** Escolha o tema que será aplicado ao editor TinyMCE quando exibido em seu website.
- **Tema do Administrador** Escolha o tema que será aplicado ao editor TinyMCE quando exibido no seu Backend de Administrador.
- **Modo da Barra de Ferramentas** Controla como exibir os botões da barra de ferramentas que não estão na primeira linha.
- **Arrastar e Soltar Imagens** Habilitar arrastar e soltar para upload de imagens.
- **Diretório de Imagens** O diretório com os arquivos de imagem a serem listados em relação à pasta de imagens padrão (definida em Mídia > Opções).
- **Codificação de Entidades** Controla como as entidades HTML são codificadas. A configuração recomendada é `raw`. `nomeado` = usa codificação de entidade nomeada (por exemplo, `<`). `numérico` = usa codificação HTML numérica (por exemplo, `%03c`). `raw` = Não codifica entidades HTML. Note que a pesquisa de conteúdo pode não funcionar corretamente se a configuração não for `raw`.
- **Seleção Automática de Idioma** Se Sim, o idioma do editor corresponderá automaticamente ao idioma da IU selecionado. Se o idioma não existir, o idioma do editor será o inglês por padrão.
- **Direção do Texto** Se o idioma é lido da *Esquerda para a Direita* ou *Direita para a Esquerda* (por exemplo, como o Árabe). O padrão é *Esquerda para a Direita*.
- **Classes CSS do Template** Se carrega ou não o arquivo *editor.css*. Se nenhum arquivo desse tipo for encontrado para o template padrão, o arquivo *editor.css* do template do sistema é usado. O padrão é *Sim*.
- **Classes CSS Personalizadas** Caminho completo opcional para um arquivo CSS personalizado. Se inserido, isto sobrescreve a configuração de classes CSS do Template.
- **URLs** Se usa URLs Relativos ou Absolutos para links. O padrão é *Relativos*.
- **Novas Linhas** Se interpreta novas linhas como *Elementos P* ou *Elementos BR*. O padrão é *Elementos P*.
- **Usar Filtro de Texto do Joomla** Se ligado, o filtro de texto da Configuração Global do Joomla para cada grupo de usuários é aplicado. Se desligado, os filtros definidos aqui são usados para todos os grupos de usuários.
- **Elementos Proibidos** Os elementos que serão limpos do texto. O padrão é *applet*, que removerá elementos de applet do texto.
- **Elementos Válidos** Define quais elementos permanecerão no texto editado quando o editor salvar (o conjunto de regras padrão para essa opção é uma mistura das especificações completas do HTML5 e HTML4).
- **Elementos Válidos Estendidos** Lista opcional de elementos HTML válidos para adicionar ao conjunto de regras existente.
- **Redimensionamento** Ativar/desativar o redimensionamento da área do editor (vertical e também horizontalmente, se o *Redimensionamento Horizontal* estiver habilitado).
- **Redimensionamento Horizontal** Ativar/desativar o redimensionamento horizontal.
- **Caminho do Elemento** Se ajustado para ON, exibe as classes definidas para o texto marcado.
- **Contagem de Palavras** Ativar/desativar a contagem de palavras.
- **Markdown** Permite o uso da sintaxe estilo Markdown para criar links, listas e outros estilos. Esta sintaxe especial é convertida e salva como html regular. Por exemplo, o usuário pode digitar # texto para produzir um cabeçalho ou **texto** para deixar o texto em negrito.
- **Imagem Avançada** Ativar/desativar uma caixa de diálogo de imagem mais avançada.
- **Lista Avançada** Ativar/desativar a capacidade de definir formatos de número e tipos de marcadores em listas ordenadas e não ordenadas.
- **Menu de Contexto** Ativar/desativar o menu de contexto.
- **Plugin Personalizado** Adicione plugins personalizados do TinyMCE ao editor especificando-os aqui.
- **Botão Personalizado** Adicione botões personalizados do TinyMCE ao editor especificando-os aqui.

#### Aba Avançada do TinyMCE

![Formulário de Opções Avançadas do TinyMCE](../../../en/images/plugins/plugin-group-editor-tinymce-advanced.png)

- **Número de Conjuntos** Número de conjuntos que podem ser criados. Mínimo 3.
- **Altura do HTML** A altura, em pixels, da janela pop-up do modo HTML.
- **Largura do HTML** A largura, em pixels, da janela pop-up do modo HTML.

*Traduzido por openai.com*


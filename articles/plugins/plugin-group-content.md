<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_Content_Group / Display title: Grupo de Conteúdo -->

## Descrição do Grupo

### Conteúdo - Confirmar Consentimento

![Plugin de consentimento confirmado de conteúdo](../../../en/images/plugins/plugin-group-content-confirm-consent.png)

- **Política de Privacidade Breve** Aviso breve do texto que será exibido acima da Caixa de Consentimento de Privacidade.
- **Artigo de Privacidade** Se necessário, selecione/crie seu Artigo de Privacidade para vincular ao seu formulário.

Para mais informações, veja Configuração do Plugin - Consentimento de Privacidade.

### Conteúdo - Contato

![Plugin de contato de conteúdo](../../../en/images/plugins/plugin-group-content-contact.png)

- **Redirecionamento** Você pode vincular o nome do autor a:
  - Página de contato associada.
  - Página da web especificada no perfil de contato associado.
  - Email especificado no perfil de contato associado.
- **Aplicar link também ao nome fictício** Vincule aos dados reais do usuário mesmo que um pseudônimo de autor seja definido nas opções do artigo.

### Conteúdo - Ocultação de Email

Este plugin oculta todos os e-mails no conteúdo usando JavaScript para enganar spambots. Isso ajuda a impedir que e-mails contidos nos artigos sejam adicionados a listas de spam. Você pode desativar a Ocultação de Email dentro de um artigo inserindo {emailcloak=off} em qualquer parte do texto do artigo. Nesse caso, nenhum endereço de e-mail no artigo será ocultado por este plugin.

![Plugin de ocultação de email de conteúdo](../../../en/images/plugins/plugin-group-content-email-cloaking.png)

- **Modo** Como os e-mails serão exibidos. As opções são *Como endereço mailto clicável* ou como *Texto não clicável*.

### Conteúdo - Campos

Este plugin permite que você exiba um campo personalizado que foi inserido com o plugin *Botão - Campos* ou usando a Sintaxe: `{field #}` diretamente na área do editor. Sintaxe:

- **`{field 1}`** exibirá o campo com o ID 1.
- **`{field 1,foo}`** exibirá o campo selecionado usando o layout alternativo `foo`.
- **`{fieldgroup 2}`** exibirá todos os campos dentro do grupo de campos com o ID 2.

### Conteúdo - Joomla

![Plugin de Joomla de conteúdo](../../../en/images/plugins/plugin-group-content-joomla.png)

- **Verificar Exclusão de Categoria** Verifique se as categorias estão completamente vazias antes de serem excluídas.
- **Email em Novo Artigo no Site** Enviar email para usuários se *Enviar email* estiver *On* quando houver um novo artigo enviado via Frontend.

### Conteúdo - Carregar Módulos

Este plugin permite que você coloque um Módulo dentro de um Artigo com a sintaxe: `{loadposition xx}`, onde `xx` é um código de posição definido pelo usuário. Por exemplo, se você criar um Módulo com o valor de Posição de `myposition1`, então ao digitar o texto `{loadposition myposition1}` dentro de um Artigo fará com que esse Módulo seja exibido naquele ponto no Artigo.

![Plugin de carregar módulos de conteúdo](../../../en/images/plugins/plugin-group-content-load-modules.png)

- **Estilo** O Estilo para o Módulo carregado.

### Conteúdo - Quebra de Página

Este plugin adiciona funcionalidades de índice a um Artigo paginado. Isso é feito automaticamente através do uso do botão de Quebra de Página adicionado à parte inferior do painel de texto em um Artigo. O código HTML está incluído aqui como referência do que está disponível. A Quebra de Página será exibida na janela de texto como uma linha horizontal simples.

![Plugin de quebra de página de conteúdo](../../../en/images/plugins/plugin-group-content-page-break.png)

- **Mostrar Título do Site** Se os atributos de título e cabeçalho do plug-in serão ou não adicionados à tag Título do Site.
- **Cabeçalho do Índice do Artigo** Mostrar ou ocultar o Cabeçalho do Índice do Artigo. O Cabeçalho é exibido no topo da Tabela de Conteúdo.
- **Cabeçalho do Índice do Artigo Personalizado** Insira um texto personalizado para o Cabeçalho do Índice do Artigo. Se estiver vazio, o padrão será usado.
- **Tabela de Conteúdos** Se irá ocultar ou mostrar uma tabela de conteúdos para Artigos de várias páginas.
- **Mostrar tudo** Se irá ou não dar aos Usuários a opção de mostrar todas as páginas de um Artigo.
- **Estilo de Apresentação** Exibir o artigo com páginas separadas, abas ou sliders.

![Descrição de quebra de página de conteúdo](../../../en/images/plugins/plugin-group-content-page-break-description.png)

### Conteúdo - Navegação de Página

Este plugin permite que você adicione links de navegação Próximo & Anterior aos Artigos, por exemplo, ao usar um layout de blog ou lista. Esta funcionalidade pode ser controlada com os seguintes parâmetros do Joomla!:

- **Mostrar Navegação** no Artigo - tela de Configuração Global
- **Mostrar Navegação** nos Parâmetros - seção Componente do Item de Menu - Novo/Editar - Parâmetros - Componente para a tela de layout dos Artigos.

Observe que, se o plug-in de Navegação de Página estiver desativado nesta tela, nenhuma Navegação de Página será exibida e as configurações dos parâmetros acima não terão efeito.

![Plugin de navegação de página de conteúdo](../../../en/images/plugins/plugin-group-content-page-navigation.png)

- **Posição** Posição do link de navegação. As opções são *Acima* do Artigo ou *Abaixo* do Artigo.
- **Relativo a** Atribui a localização relativa para os parâmetros de Posição. Texto irá colocá-lo diretamente acima ou abaixo do conteúdo do artigo. Artigo Completo irá colocá-lo acima ou abaixo da exibição completa incluindo título e ler mais.
- **Texto do Link** Escolha o que exibir como o texto do link.

### Conteúdo - Pesquisa Inteligente

Mudanças no conteúdo não atualizarão o índice de Pesquisa Inteligente se você não habilitar este plugin.

### Conteúdo - Voto

![Plugin de voto de conteúdo](../../../en/images/plugins/plugin-group-content-vote.png)

- **Posição** Posição da votação.

*Traduzido por openai.com*


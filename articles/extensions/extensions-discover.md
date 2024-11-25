<!-- Filename: Help4.x:Extensions:_Discover / Display title: Extensões: Descobrir   -->

## Descrição

Esta página permite que você descubra extensões que não passaram pelo processo normal de instalação. Por exemplo, algumas extensões têm um tamanho de arquivo muito grande para serem enviadas usando a interface web devido a limitações do ambiente de hospedagem web. Usando este recurso, você pode enviar arquivos de extensões diretamente para o seu servidor web utilizando outros meios, como FTP ou SFTP, e colocar esses arquivos de extensão no diretório apropriado. Você pode então usar o recurso de descoberta para encontrar a extensão recém-carregada e ativá-la na sua instalação do Joomla!. Usando a operação de descoberta, você também pode descobrir e instalar várias extensões ao mesmo tempo. Uma extensão pode ser instalada com a função de descoberta e os seguintes passos:

1. Envie os arquivos de extensão descompactados para o diretório apropriado na sua instalação do Joomla!. Por exemplo, se você quiser enviar uma extensão de modelo de site para sua instalação do Joomla!, você criaria um diretório para a extensão de modelo no subdiretório /templates da sua instalação do Joomla!. Em seguida, você enviaria os arquivos da extensão de modelo para esse diretório.
2. Depois de enviar os arquivos da extensão, volte para a página Descobrir do Gerenciador de Extensões e selecione o botão **Descobrir** na barra de ferramentas. Isso iniciará a função de busca que procurará nos diretórios de extensão do Joomla! à procura de extensões não instaladas.
3. Se a extensão que você enviou for compatível com a sua versão do Joomla! e ainda não estiver instalada, ela aparecerá na lista de extensões descobertas nesta página.
4. Marque a caixa de seleção à esquerda da extensão descoberta e, em seguida, selecione o botão **Instalar** na barra de ferramentas. Isso instalará a extensão na sua instalação do Joomla!.

### Elementos Comuns

Alguns elementos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de Lista](jdocmanual?article=help/common-elements/list-filters).
* [Cabeçalhos das Colunas da Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordenação de Itens da Lista](jdocmanual?article=help/common-elements/list-ordering).
* [Paginação de Lista](jdocmanual?article=help/common-elements/list-pagination).

## Como Acessar

- Selecione **Sistema → Painel de Instalação → Descobrir** no menu do Administrador.

## Captura de tela

![Lista de descoberta de extensões](../../../pt/images/extensions/discover-list.png)

## Cabeçalhos de Coluna

- **Nome** O nome da extensão.
- **Localização** Indica se é uma extensão de site ou de administrador.
- **Tipo** O tipo de extensão – Módulo, Plugin, Template, Idioma.
- **Versão** O número da versão da extensão.
- **Data** A data de lançamento da extensão.
- **Autor** O autor da extensão.
- **Diretório** Se a extensão for um plugin, isto mostra o subdiretório dentro do diretório /plugins da instalação do Joomla! onde a extensão está localizada. Por padrão, o Joomla! possui os seguintes subdiretórios no diretório Plugins, cada um representando diferentes tipos de plugins definidos: autenticacao, conteudo, editores, editores-xtd, extensao, pesquisa, sistema, usuario.
- **ID** O número de ID. Um número de identificação exclusivo atribuído a esta entrada. Ele é atribuído automaticamente pelo Joomla! e é usado para a identificação interna da entrada. O número não pode ser alterado.

## Dicas

- Se você tiver muitas extensões que deseja instalar, pode carregá-las
  todas nos diretórios apropriados da sua instalação do Joomla! e
  então usar esta tela para descobrir todas elas em uma única operação. Você pode
  instalar todas as extensões em um passo selecionando todas
  elas e clicando no botão **Instalar** na barra de ferramentas.

*Traduzido por openai.com*


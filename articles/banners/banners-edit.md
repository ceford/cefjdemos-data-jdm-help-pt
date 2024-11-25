<!-- Filename: Help4.x:Banners:_Edit / Display title: Banners: Editar -->

## Descrição

Usado para adicionar ou editar banners que podem ser exibidos em seu site Joomla! Lembre-se de criar pelo menos um Cliente de Banner e uma Categoria de Banner antes de criar qualquer Banner.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba de Publicação](jdocmanual?article=help/common-elements/edit-publishing).
* [O Pop-up de Histórico de Versões](jdocmanual?article=help/common-elements/edit-version-history).

## Como Acessar

No menu do Administrador:
- Selecione **Componentes → Banners** para ir à página de lista de Banners.
- Selecione o botão **Novo** na Barra de Ferramentas para criar um novo Banner.
- Selecione um **nome** de Banner na coluna *Nome* para editar um Banner existente.

## Captura de Tela

Um banner pode ser uma imagem clicável ou algum código personalizado. O Tipo de Imagem é mostrado na captura de tela abaixo. O tipo personalizado tem a caixa de seleção de imagem substituída por uma área de texto para código.

![Guia de edição de detalhes do banner](../../../pt/images/banners/banners-edit-details-tab.png)

## Campos do Formulário

- **Nome** O nome do Banner. Este é o nome que será exibido na coluna *Nome* da lista de Banners.
- **Alias** O nome interno do item. Normalmente, você pode deixar este campo em branco e o Joomla preencherá com um valor padrão derivado do Nome, mas em letras minúsculas e com hífens em vez de espaços.

## Aba de Detalhes

### Painel Esquerdo

- **Tipo** O tipo de banner a ser exibido. As opções são um arquivo de imagem ou código HTML personalizado.
  - **Imagem** Arquivo de imagem a ser exibido no banner. Clique no botão *Selecionar* para procurar e selecionar o arquivo de imagem a ser usado. Use a página de Mídia para enviar arquivos de imagem do Banner para o seu site. As imagens para Banners precisam estar no diretório /images/banners/.
    - **Largura** A largura fixa para redimensionar a imagem do banner. Deixe em branco se quiser usar a largura real do arquivo de imagem do banner.
    - **Altura** A altura fixa para redimensionar a imagem do banner. Deixe em branco se quiser usar a altura real do arquivo de imagem do banner.
    - **Texto Alternativo** Texto a ser exibido no lugar da imagem do banner no caso de a imagem não poder ser exibida.
    - **Texto Alternativo** Texto alternativo para a imagem do Banner.
  - **Personalizado** Selecione Personalizado se quiser inserir um código personalizado para o seu banner.
    - **Código Personalizado** Use {CLICKURL} e {NAME} para mesclar os valores 'URL de Clique' e 'Nome', respectivamente, em seu código personalizado. Por exemplo:<br>
      `<a href=`&#34;`{CLICKURL}"><img src=`&#34;`enter url to image" alt="{NAME}" title="{NAME}"></a>`.
      Outra opção é inserir um código HTML personalizado. Por exemplo:<br>
      `<div class="yourclass"><a href=`&#34;`https://yourdomain.com"><img src=`&#34;`pathofyourimage"></a></div>`
- **URL de Clique** O URL para o qual será navegada quando o Usuário clicar no Banner.
- **Descrição** Insira uma descrição para o Banner.

### Painel Direito

- **Status** O status publicado do item.
- **Fixado** Se o Banner está ou não *fixado*. Se um ou mais Banners em uma Categoria forem designados como *fixos*, eles terão prioridade sobre Banners que não são fixos.
    - Por exemplo, se dois Banners em uma Categoria estão fixados e um terceiro Banner não está fixado, o terceiro Banner não será exibido se a configuração do módulo de exibição de Banner for *Fixado, Aleatório* ou *Fixado, Ordenado*. Apenas os dois Banners fixados serão exibidos. Se os banners fixados tiverem um número fixo de impressões, uma vez que essas impressões sejam esgotadas, os banners fixados não serão mais exibidos e os banners não fixados começarão a ser exibidos automaticamente.
- **Idioma** Idioma do item.
- **Nota de Versão** Campo opcional para identificar esta versão do item na janela de Histórico de Versões do item.

### Aba de Detalhes do Banner

![Banners editar aba de detalhes do banner](../../../pt/images/banners/banners-edit-banner-details-tab.png)

- **Máx. Impressões** O número de impressões adquiridas para este Banner. As impressões são o número de vezes que um Banner será exibido em uma página. Selecione a caixa 'Ilimitado' se for permitido um número ilimitado de Impressões.
- **Total de Impressões** O número de vezes que este Banner foi exibido em uma página da web para um usuário. Nenhuma entrada é permitida. Você pode redefinir este número para 0 pressionando o botão 'Redefinir impressões'.
- **Total de Cliques** O número de vezes que este Banner foi clicado. Nenhuma entrada é permitida. Você pode redefinir este número para 0 pressionando o botão *Redefinir cliques*.
- **Cliente** O Cliente para este Banner. Selecione um da lista suspensa de Clientes existentes.
- **Tipo de Compra:** O tipo de compra do banner. Isto é usado para indicar como o cliente do banner adquiriu o tempo de exibição do banner.
- **Rastrear Impressões** Se deve ou não rastrear o número de vezes que o banner é exibido para visitantes do site.
- **Rastrear Cliques** Se deve ou não rastrear o número de vezes que o banner é clicado por visitantes do site.

## Dicas

- Banners são colocados em páginas específicas adicionando Módulos do tipo *Banners* usando a lista de Módulos.
- Se você tem uma série de Banners que gostaria de exibir em uma ou mais páginas em ordem aleatória:
  1. Crie os Banners que deseja incluir, certificando-se de que eles tenham o mesmo Cliente e Categoria.
  2. Crie um Módulo de Banner para esse Cliente e Categoria e, na Atribuição de Menu, escolha as Seleções de Menu para o módulo ser exibido.
  3. No Módulo de Banner, defina o valor *Randomize* para *Sticky, Randomize*.

  Com essas configurações, os diferentes Banners para aquele Cliente e Categoria serão exibidos nas páginas selecionadas em ordem aleatória.


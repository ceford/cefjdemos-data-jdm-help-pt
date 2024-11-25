<!-- Filename: Help4.x:Components_Weblinks_Links_Edit / Display title: Link da Web: Editar   -->

## Descrição

Este formulário é usado para adicionar um novo Link da Web ou editar um link existente. Note que você precisa criar pelo menos uma Categoria de Links da Web antes de poder criar seu primeiro Link da Web.

### Elementos Comuns

Alguns elementos desta página são abordados em artigos de ajuda separados:

* [Barras de ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba de Associações](jdocmanual?article=help/common-elements/edit-associations).

## Como Acessar

- Selecione **Componentes → Links da Web → Links** no menu do
  Administrador. Em seguida...
- Selecione o botão **Novo** na Barra de Ferramentas para criar um novo link. Ou...
- Selecione um título na lista de links para editar um link existente.

## Captura de Tela

![editar link da web aba de link da web](../../../pt/images/weblinks/web-link-edit-web-link-tab.png)

## Campos do Formulário

#### Painel Esquerdo

- **URL** A URL do Link da Web.
- **Descrição** A descrição do item. Descrições de Categoria, Subcategoria e Link da Web podem ser exibidas em páginas web, dependendo das configurações de parâmetro. Essas descrições são inseridas usando o mesmo editor utilizado para Artigos.

### Aba Imagens

![aba de edição de imagens do link da web](../../../pt/images/weblinks/web-link-edit-web-link-images-tab.png)

- **Primeira Imagem** Clique em Selecionar para escolher uma imagem a ser exibida com este item na interface.
- **Float da Imagem** Onde posicionar a imagem em relação ao texto na página.
- **Texto Alternativo** Texto alternativo a ser usado para visitantes que não têm acesso às imagens. Este texto é substituído pelo texto da legenda se disponível.
- **Legenda** A legenda da imagem.
- **Segunda Imagem** Clique em Selecionar para escolher uma imagem a ser exibida com este item na interface.
- **Float da Imagem** (Usar Global/Direita/Esquerda/Nenhum). Onde posicionar a imagem em relação ao texto na página.
- **Texto Alternativo** Texto alternativo a ser usado para visitantes que não têm acesso às imagens. Este texto é substituído pelo texto da legenda se disponível.
- **Legenda** A legenda da imagem.

### Aba de Publicação

![aba de edição de publicação do link da web](../../../pt/images/weblinks/web-link-edit-web-link-publishing-tab.png)

- **Iniciar Publicação** Data e hora para começar a publicação. Use este campo se você deseja inserir conteúdo com antecedência e publicá-lo automaticamente em um horário futuro.
- **Finalizar Publicação** Data e hora para finalizar a publicação. Use este campo se você deseja que o conteúdo seja alterado automaticamente para o estado Não Publicado em um horário futuro (por exemplo, quando não for mais aplicável).
- **Data de Criação** Este campo padrão é preenchido com a hora atual quando o Artigo foi criado. Você pode inserir uma data e hora diferentes ou clicar no ícone do calendário para encontrar a data desejada.
- **Criado Por** Nome do Usuário do Joomla! que criou este item. Este será preenchido, por padrão, com o usuário atualmente logado. Se você deseja mudar para um usuário diferente, clique no botão Selecionar Usuário para escolher um usuário diferente.
- **Apelido do Autor** Este campo opcional permite que você insira um apelido para este Autor neste Artigo. Isso permite que você exiba um nome de Autor diferente para este Artigo.
- **Data da Última Modificação** (Somente informativo) Data da última modificação.
- **Modificado Por** (Somente informativo) Nome de usuário que realizou a última modificação.
- **Revisão** (Somente informativo) Número de revisões neste item.
- **Visualizações** O número de vezes que um item foi visualizado.
- **ID** Este é um número de identificação exclusivo para este item atribuído automaticamente pelo Joomla!. Ele é usado para identificar o item internamente, e você não pode alterar este número. Ao criar um novo item, este campo exibe 0 até que você salve a nova entrada, momento em que um novo ID é atribuído.
- **Meta Descrição** Um parágrafo opcional para ser usado como a descrição da página na saída HTML. Geralmente, isso será exibido nos resultados dos motores de busca. Se inserido, isso cria um elemento meta HTML com um atributo name de "description" e um atributo content igual ao texto inserido.
- **Meta Palavras-chave** Entrada opcional para palavras-chave. Deve ser inserido separando por vírgulas (por exemplo, "gatos, cães, animais") e pode ser inserido em maiúsculas ou minúsculas. (Por exemplo, "GATOS" corresponderá a "gatos" ou "Gatos").
- **Referência Externa** Uma referência opcional usada para vincular a fontes de dados externas. Se inserido, isso cria um elemento meta HTML com um atributo name de "xreference" e um atributo content igual ao texto inserido.
- **Robôs** As instruções para "robôs" que navegam para esta página.
  - Usar Global: Use o valor definido em Componente→Opções para este componente.
  - Indexar, Seguir: Indexar esta página e seguir os links nesta página.
  - Não indexar, Seguir: Não indexar esta página, mas seguir os links na página. Por exemplo, você pode fazer isso para uma página de mapa do site onde deseja que os links sejam indexados, mas não quer que esta página apareça nos mecanismos de busca.
  - Indexar, Não seguir: Indexar esta página, mas não seguir links na página. Por exemplo, você pode querer fazer isso para um calendário de eventos, onde deseja que a página apareça nos mecanismos de busca, mas não deseja indexar cada evento.
  - Não indexar, Não seguir: Não indexar esta página ou seguir links na página.
- **Direitos do Conteúdo** Descreva quais direitos outras pessoas têm de usar este conteúdo.

### Aba Opções

![aba de edição de opções do link da web](../../../pt/images/weblinks/web-link-edit-web-link-options-tab.png)

- **Destino** Como abrir o link. As opções são:
  - Abrir na janela principal. Abrir o link na janela atual do navegador, permitindo a navegação Avançar e Voltar.
  - Abrir em nova janela. Abrir o link em uma nova janela do navegador, permitindo a navegação Avançar e Voltar.
  - Abrir em popup. Abrir o link em uma janela popup.
  - Modal. Abrir o link em uma tela modal.
- **Largura** Largura da Janela do IFrame. Insira um número de pixels ou insira uma porcentagem (%). Por exemplo, "550" significa 550 pixels. "75%" significa 75% da largura da página.
- **Altura** Altura da Janela do IFrame. Insira um número de pixels ou insira uma porcentagem (%). Por exemplo, "550" significa 550 pixels. "75%" significa 75% da altura da página.
- **Contar Cliques** Se deseja ou não rastrear quantas vezes este link da web foi aberto.


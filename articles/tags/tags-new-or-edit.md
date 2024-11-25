<!-- Filename: Help4.x:Tags:_New_or_Edit / Display title: Tags: Novo ou Editar -->

## Descrição

A página *Tags: Novo ou Editar* é usada para adicionar ou editar tags que podem ser utilizadas para exibir o conteúdo do site pelo nome da tag.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de Ajuda separados:

* [Barras de ferramentas](jdocmanual?article=help/common-elements/toolbars).

## Como Acessar

- Selecione **Componentes → Tags** no menu do Administrador. Em seguida:
  - Selecione o botão '**Novo'** na Barra de Ferramentas para criar uma nova Tag.
  - Selecione o Título de uma Tag na coluna **Título** da lista para editar
    uma tag existente.

## Captura de Tela

![editar detalhes da guia de tags](../../../pt/images/tags/tags-edit-tag-details-tab.png)

## Campos do Formulário

- **Título** O Nome deste item. Este campo é obrigatório.
- **Alias** O nome interno do item. Normalmente, você pode deixar este
  campo em branco, e o Joomla irá preencher com um valor padrão do Título em minúsculas e com hifens em vez de espaços.

### Guia de Detalhes da Tag

#### Painel Esquerdo

- **Descrição** Indique a finalidade desta tag.

#### Painel Direito

- **Parente** O item (categoria, item de menu, etc.) que é o
  pai do item que está sendo editado.
- **Status** O status de publicação do item.
- **Acesso** O Nível de Acesso de visualização para este item.
- **Idioma** Idioma do item.
- **Nota** Este campo é normalmente para uso do administrador do site (por
  exemplo, para documentar informações sobre este item) e não é exibido no
  Frontend do site.
- **Nota da Versão** Campo opcional para identificar esta versão do item
  na janela de Histórico de Versões do item.

### Guia de Opções

![guia de edição de opções de tag](../../../pt/images/tags/tags-edit-options-tab.png)

#### Painel de Opções

- **Layout** Use um layout da visualização do componente fornecido ou
  substituições nos templates.
- **Classe CSS para link da tag** Adicione classes CSS específicas para o link da tag.
  Se vazio, *label label-info* será adicionado pelo layout padrão da tag.

#### Painéis de Imagens

- **Imagem de Atração** A imagem que será exibida como parte da lista.
- **Float** Atributo de float para a imagem.
- **Alt** Texto alternativo para a imagem.
- **Legenda** A legenda para a imagem.
- **Imagem Completa** Uma imagem que será exibida na visualização única da tag.

### Guia de Publicação

![guia de edição de publicação de tag](../../../pt/images/tags/tags-edit-publishing-tab.png)

#### Painel de Publicação

- **Data de Criação** Data em que o item (Artigo, Categoria, etc.) foi criado.
- **Criado Por** Nome do Usuário Joomla que criou este item. Este
  campo será preenchido automaticamente com o usuário atualmente logado. Se deseja mudar
  isso para um usuário diferente, clique no botão Selecionar Usuário para escolher um outro usuário.
- **Criado por Alias** Este campo opcional permite inserir um
  pseudônimo para este Autor neste Artigo. Isso permite exibir um
  nome de Autor diferente neste Artigo.
- **Data de Modificação** Data da última modificação.
- **Modificado Por** Nome de usuário que realizou a última modificação.
- **Revisão** ...
- **Visualizações** O número de vezes que um item foi visualizado.
- **ID** Este é um número de identificação único para este item atribuído
  automaticamente pelo Joomla. Ele é usado para identificar o item internamente
  e não é possível alterar este número. Ao criar um novo item, este
  campo exibe "0" até você salvar a nova entrada, momento em que um novo
  ID é atribuído a ele.

#### Painel de Metadados

- **Descrição Meta** Um parágrafo opcional a ser usado como a
  descrição da página na saída HTML. Normalmente, isso
  será exibido nos resultados dos motores de busca. Se preenchido, isso cria um
  elemento meta HTML com um atributo name de `<description>` e um atributo
  content igual ao texto inserido.
- **Palavras-chave** Entrada opcional para palavras-chave. Devem ser inseridas separadas
  por vírgulas (por exemplo: gatos, cães, animais) e podem ser escritas em
  maiúsculas ou minúsculas. (Por exemplo: *GATOS* corresponderá a *gatos* ou
  *Gatos*). Palavras-chave podem ser usadas de várias formas:
  1.  Para ajudar os motores de busca e outros sistemas a classificar o conteúdo do
      Artigo.
  2.  Em combinação com tags de Banners, para exibir Banners específicos com base
      no conteúdo do Artigo. Por exemplo, digamos que você tenha um Banner com
      um anúncio de produtos para cães e outro Banner para produtos de gatos. Você
      pode fazer com que seu Banner de cão apareça quando um Usuário estiver visualizando um
      Artigo relacionado a cães e seu Banner de gato para um Artigo relacionado a gatos. Para
      fazer isso, você deve:
      - Adicionar as palavras-chave "cão" e "gato" aos Artigos apropriados.
      - Adicionar as Tags "cão" e "gato" aos Banners apropriados em
        Banners: Editar.
      - Definir o Parâmetro 'Pesquisar por Tags' do módulo Banner para "Sim" na
        lista de Módulos do Site: Banners.
  3.  Apenas para artigos, em combinação com o módulo Artigos - Relacionados,
      para exibir Artigos que compartilhem pelo menos uma palavra-chave em comum. Por
      exemplo, se o Artigo atual exibido tiver as palavras-chave "gatos,
      cães, macacos", quaisquer outros Artigos com pelo menos uma dessas
      palavras-chave aparecerão no módulo 'Artigos - Relacionados'.
- **Autor** Entrada opcional para um nome de Autor dentro dos metadados. Se
  preenchido, isso cria um elemento meta HTML com o atributo name de
  'author' e o atributo content conforme inserido aqui.
- **Robôs** As instruções para 'robôs' da web que navegam até esta
  página.
  - *index, follow* Indexar esta página e seguir os links nesta página.
  - *noindex, follow* Não indexar esta página, mas ainda seguir os
    links na página. Por exemplo, você pode fazer isso para uma página do mapa do site
    onde deseja que os links sejam indexados, mas não queira que esta
    página apareça nos motores de busca.
  - *index, nofollow* Indexar esta página, mas não seguir quaisquer links na
    página. Por exemplo, você pode querer fazer isso para um calendário de eventos,
    onde deseja que a página apareça nos motores de busca, mas não
    queira indexar cada evento.
  - *noindex, nofollow* Não indexar esta página nem seguir quaisquer links
    na página.
  - *Usar Global* Definido na Configuração Global: Configurações de Metadados.


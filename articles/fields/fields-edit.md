<!-- Filename: Help4.x:Fields:_Edit / Display title: Componente: Campo de Edição  -->

## Descrição

A página *Componente: Editar Campo* é semelhante para todos os componentes que implementam campos, mas o título da página muda dependendo do contexto: *Artigos: Editar Campo*, *Contatos: Editar Campo* ou *Usuários: Editar Campo*.

A aba **Geral** muda para refletir o tipo de campo que está sendo editado e, uma vez que um campo foi salvo, seu tipo não pode ser alterado. No entanto, é fácil excluir campos e criar novos.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba de Publicação](jdocmanual?article=help/common-elements/edit-publishing).
* [A Aba de Permissões](jdocmanual?article=help/common-elements/edit-permissions).

## Como Acessar

* Selecione **Conteúdo → Campos** no menu do Administrador. Ou...
* Selecione **Contato → Campos** no menu do Administrador. Ou...
* Selecione **Usuários → Campos** no menu do Administrador. Em seguida...
  * Selecione o botão **Novo** na Barra de Ferramentas para criar um novo campo. Ou...
  * Selecione um **Título** da lista para editar um campo existente.

**Nota:** Há uma lista suspensa que permite a criação de Campos para uma Categoria e Correio no componente de Contato. Elas exigem alguma experiência em codificação para preparar substituições de modelo adequadas.

## Captura de Tela

![Campo de edição de artigos](../../../pt/images/fields/articles-edit-field.png)

## Campos do Formulário

- **Título** O título para este campo.

### Aba Geral

#### Painel Esquerdo

Parâmetros para todos os campos:

- **Tipo** Ao criar um campo, você pode escolher um dos 16 tipos de
  campo. Quando você salva o campo, este tipo é permanente.
- **Nome** O nome será usado para identificar o campo. Deixe em branco e o Joomla preencherá com um valor padrão a partir do título.
- **Rótulo** Use um texto descritivo do campo para o rótulo do campo. Este texto não é traduzível. Se você não inserir nenhum texto para um rótulo, o texto do título também será usado como texto do rótulo.
- **Descrição** A descrição do campo. Um texto que será mostrado como uma dica de ferramenta quando o usuário passar o mouse sobre a caixa de texto enquanto a utiliza no Backend criando um artigo ou um contato ou um componente de terceiros que suporte campos. Este texto não é traduzível. Você não verá esta descrição no Frontend.
- **Obrigatório** Este é um campo obrigatório? Nesse caso, o campo precisa ser preenchido antes de enviar um artigo ou um contato ou um componente de terceiros que suporte campos.

#### Painel Direito

- **Status** O status de publicação deste campo.
  - *Publicado* O campo é visível enquanto edita um artigo ou um contato. E é visível no Frontend.
  - *Não publicado* O campo não será visível para os usuários enquanto editam um artigo ou um contato.
  - *Arquivado* O campo não será mais exibido na edição de um artigo ou um contato. Você pode abri-lo nos Campos quando definir o filtro para arquivado.
  - *Lixeira* O campo é excluído, mas ainda está no banco de dados. Ele pode ser excluído permanentemente do banco de dados nos Campos com a função Limpar Lixeira.
- **Grupo de Campos** Você pode atribuir um campo a um grupo de campos.
- **Categoria** Você pode atribuir um campo a uma ou mais categorias. Note que o padrão *Todos* não inclui artigos *Sem categoria*.
- **Acesso** Selecione o nível de acesso de visualização para este campo. Os níveis de acesso dependem do que foi configurado em *Usuários: Níveis de Acesso*.
- **Idioma** Selecione o idioma para este campo. Se você não estiver usando o recurso de multilíngue do Joomla, mantenha o padrão como *Todos*.
- **Nota** Um campo opcional para fazer suas anotações pessoais para o campo.

### Aba de Opções

![Opções de edição de campo de artigos](../../../pt/images/fields/articles-edit-field-options-tab.png)

#### Opções de Formulário

- **Placeholder** Um texto de espaço reservado que aparecerá dentro do campo como uma dica para a entrada. O espaço reservado está ativo no Backend ao criar um artigo ou um contato ou um componente de terceiros que suporte campos. Você não o vê no Frontend.
- **Classe do Campo** Os atributos de classe do campo quando o campo é renderizado. Se precisar de classes diferentes, liste-as com espaços.
- **Classe do Rótulo (Formulário)** Classe CSS a ser aplicada ao rótulo do campo quando estiver em modo de edição (inserindo entrada em um campo).
- **Editável Em** Em qual parte do site o campo deve ser mostrado. No Backend, no Frontend ou ambos?
- **Atributo Showon** Mostrar ou ocultar condicionalmente o campo dependendo do valor de outros campos. A sintaxe para usar aqui, por exemplo:
  `lista-de-itens:valor1[OU]lista-de-itens:valor2`
  - lista-de-itens: O *nome* de um campo já criado no qual este campo dependerá de ser mostrado.
  - valor1: O valor necessário para que o campo do qual ele depende seja mostrado.
  - `[OU]`: Para criar uma escolha entre vários campos. No exemplo, este campo será mostrado quando o campo *lista-de-itens* tiver o valor:
    *valor1* OU *valor2*
  - `[E]`: Para combinar vários campos. Este campo será mostrado somente
    quando o campo *lista-de-itens* tiver o valor: *valor1* E *valor2*
  - Você também pode usar valor *não é igual* como em
    *lista-de-itens!:valor1* A sintaxe mostrará este campo somente quando
    *lista-de-itens* não é igual a *valor1*
  - Para mostrar este campo quando o campo *lista-de-itens* foi selecionado e
    não tem um valor vazio, use a sintaxe *lista-de-itens!:* (sem um valor especificado).

**Nota:** Campos de subformulário lidam com o identificador *nome* de *lista-de-itens* de maneira diferente. Se você criar um campo personalizado de Subformulário e adicionar este campo condicional lá, você precisa usar *campo\[ID\]*
em vez de *lista-de-itens*, onde ID é o id do campo
*lista-de-itens*. Portanto, o atributo *showon* para este campo condicional que você está criando precisa ser: `campo36:valor1[OU]campo36:valor2` onde
36 é o ID do campo 'Lista de itens'.

#### Opções de Exibição

- **Classe de Exibição** A classe do contêiner do campo na saída.
- **Classe do Valor** A classe do valor do campo na saída.
- **Rótulo** Mostrar o rótulo quando o campo é renderizado.
- **Classe do Rótulo (Saída)** Classe CSS a ser aplicada ao rótulo do campo quando
  é exibido (mostrando a saída de um campo).
- **Exibição Automática** Joomla oferece alguns eventos de conteúdo que são
  acionados durante o processo de criação de conteúdo. Este é o lugar para
  definir como os campos devem ser integrados ao conteúdo. Você pode
  escolher
  - Após Título
  - Antes do Conteúdo Exibido
  - Após o Conteúdo Exibido
  - Não exibir automaticamente
- **Prefixo** Texto fixo a ser exibido antes de um campo, por exemplo £.
- **Sufixo** Texto fixo a ser exibido após um campo, por exemplo €.
- **Layout** Se houver um layout personalizado, ele será selecionado aqui.
- **Exibir Quando Somente Leitura** Se o campo for somente leitura (talvez o
  usuário não tenha o nível de acesso) o campo deve ser exibido ou
  oculto.

#### Busca Inteligente

- **Índice de Busca** Aviso: Quando *Tornar pesquisável* estiver selecionado, o conteúdo
  do campo é indexado com as permissões de visualização do item de conteúdo.
  Isso pode levar à divulgação inesperada de informações.

*Traduzido por openai.com*


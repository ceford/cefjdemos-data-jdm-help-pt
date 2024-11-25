<!-- Filename: Help4.x:Component:_Edit_Field_Group / Display title: Componente: Editar Grupo de Campos  -->

## Descrição

Grupos de Campos são usados para coletar campos relacionados em uma Aba nomeada em um formulário de entrada de dados. O Componente: Editar Grupo de Campos é similar para todos os componentes que implementam campos, mas o título da página muda dependendo do contexto: Artigos: Editar Grupo de Campos, Contatos: Editar Grupo de Campos ou Usuários: Editar Grupo de Campos.

### Elementos Comuns

Alguns aspectos desta página estão cobertos em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba de Publicação](jdocmanual?article=help/common-elements/edit-publishing).
* [A Aba de Permissões](jdocmanual?article=help/common-elements/edit-permissions).

## Como Acessar

* Selecione **Conteúdo → Grupos de Campos** no menu do Administrador. Ou...
* Selecione **Contato → Grupos de Campos** no menu do Administrador. Ou...
* Selecione **Usuários → Grupos de Campos** no menu do Administrador. Então...
  * selecione o botão **Novo** na Barra de Ferramentas para criar um novo campo. Ou...
  * Selecione um **Título** na lista para editar um campo existente.

**Nota:** Há uma lista suspensa que permite a criação de Campos para uma Categoria e Correio no componente de Contato. Eles exigem alguma experiência em codificação para preparar substituições de modelo adequadas.

## Captura de tela

Este exemplo é uma página de *Artigos: Editar Grupo de Campos*. *Contatos: Editar Grupo de Campos* e *Usuários: Editar Grupo de Campos* são semelhantes.

![artigos editar grupo de campos](../../../pt/images/fields/articles-edit-field-group.png)

## Campos do Formulário

- **Título** O Título para este grupo de campos.

### Geral

#### Painel Esquerdo

- **Descrição** Texto que será exibido como uma dica de ferramenta quando passar o mouse
  sobre a caixa de texto ao criar um artigo ou um contato ou um
  componente de terceiros que suporte campos personalizados. Este texto não é
  traduzível. Você não vê esta descrição no Frontend.

#### Painel Direito

- **Status** O status de publicação deste grupo de campos.
  - *Publicado* O grupo de campos é visível enquanto se edita um artigo ou um
    contato. E é visível no Frontend.
  - *Não Publicado* O grupo de campos não será visível para os usuários enquanto
    se edita um artigo ou um contato.
  - *Arquivado* O grupo de campos não será mais exibido na edição de um artigo
    ou um contato. Você pode abri-lo em Grupos de Campos quando configurar o filtro
    para arquivado.
  - *Na Lixeira* O grupo de campos está deletado, mas ainda no banco de dados. Ele
    pode ser excluído permanentemente do banco de dados em Grupos de Campos com a
    função Esvaziar Lixeira.
- **Acesso** Selecione o nível de acesso para visualização deste grupo de campos. Os
  níveis de acesso dependem do que foi configurado em Usuários: Níveis de Acesso.
- **Idioma** Selecione o idioma para este grupo de campos. Se você não estiver
  usando o recurso multi-idioma do Joomla, mantenha o padrão *Todos*.
- **Nota** Um campo opcional para fazer suas anotações pessoais para o grupo
  de campos.

### Opções

- **Exibir Quando Somente Leitura** Se o grupo de campos for somente leitura (talvez
  o usuário não tenha o nível de acesso) o grupo de campos deve ser
  exibido ou oculto.


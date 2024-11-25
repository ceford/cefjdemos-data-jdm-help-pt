<!-- Filename: Help4.x:Menus / Display title: Menus  -->

## Descrição

Os menus permitem que um usuário navegue pelo site. Um menu é um objeto que contém um ou mais itens de menu. Cada item de menu aponta para uma página lógica no site. Um módulo de menu é necessário para colocar o menu na página. Um menu pode ter mais de um módulo. Por exemplo, um módulo pode mostrar apenas os itens de menu do primeiro nível e um segundo módulo pode mostrar os itens de menu do nível 2.

A página *Menus* fornece uma visão geral dos menus disponíveis em um site Joomla. Isso inclui os detalhes de cada menu individual, como o número de itens publicados, não publicados e excluídos, e os nomes dos módulos vinculados.

O processo para adicionar um menu ao site normalmente é o seguinte:

1. Criar um novo menu (usando esta página).
2. Criar um ou mais novos itens de menu para o menu. Cada item de menu terá um tipo específico de item de menu.
3. Criar um ou mais módulos de menu para exibir o menu no site.
   - Selecionar os itens de menu (páginas) que exibirão o módulo.

### Elementos Comuns

Alguns elementos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de Lista](jdocmanual?article=help/common-elements/list-filters).
* [Cabeçalhos de Colunas de Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordenação de Itens de Lista](jdocmanual?article=help/common-elements/list-ordering).
* [Paginação de Lista](jdocmanual?article=help/common-elements/list-pagination).

## Como Acessar

- Selecione **Menus → Gerenciar** no menu do Administrador.

## Captura de Tela

![lista de menus](../../../pt/images/menus/menus-list.png)

## Cabeçalhos de Coluna

- **Título** O nome do menu.
- **Itens do Menu** Um link para os itens do menu.
- **\# Publicados** Número de itens de menu publicados neste menu.
- **\# Não Publicados** Número de itens de menu não publicados neste menu.
- **\# Excluídos** Número de itens de menu excluídos neste menu.
- **Módulos Vinculados** Uma lista suspensa mostra o nome, nível de acesso e posição do template de quaisquer módulos de menu associados ao menu.

## Dicas
- Os botões numerados levam a uma lista filtrada dos itens do menu para esse menu.
- Um menu deve ter um título descritivo curto, adequado para uso em listas e listas suspensas.
- A *Descrição* é um lembrete útil do propósito para o qual o menu foi criado.
- Se um menu não tiver módulos associados, o botão da coluna *Módulos Vinculados* é um link para um diálogo modal *Adicionar um módulo para este menu*.
- Se você excluir um menu existente, não se esqueça de que todos os itens do menu respectivo também serão excluídos. Há uma mensagem de aviso:

  **Tem certeza de que deseja excluir estes menus? Confirmar excluirá os tipos de menu selecionados, todos os itens de menu e os módulos de menu associados.**
- O Menu Principal tem o item de menu padrão do site. Ele **não deve ser excluído**! O item de menu padrão define a página que é exibida em uma visita ao URL do domínio do site, como `www.exemplo.com`. O site não funcionará se for excluído. Geralmente é o item de menu *Início*, mas pode ser configurado para qualquer item de menu, incluindo um item em um menu oculto. Se o item de menu padrão for alterado, certifique-se de que esse item de menu também não seja excluído!

*Traduzido por openai.com*


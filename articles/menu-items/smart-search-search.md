<!-- Filename: Help4.x:Menu_Item:_Search / Display title: Pesquisa -->

## Descrição

O tipo de item de menu **Pesquisa** é usado para criar uma página para Resultados de Pesquisa Inteligente. Pode ser utilizado em conjunto com um módulo de Pesquisa Inteligente para controlar o layout da Página de Resultados de Pesquisa.

### Elementos Comuns

Alguns aspectos desta página estão cobertos em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba Detalhes](jdocmanual?article=help/menu-items-common/menu-item-details).
* [A Aba Integração](jdocmanual?article=help/menu-items-common/menu-item-integration).
* [A Aba Tipo de Link](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [A Aba Exibição de Página](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [A Aba de Metadados](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [A Aba de Associações](jdocmanual?article=help/common-elements/edit-associations).
* [A Aba de Atribuição de Módulo](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Como Acessar

Para criar um novo item de menu de Pesquisa:

- Selecione **Menus → \[nome do menu\]** no menu do Administrador
  (por exemplo, **Menus → Menu Principal**). Depois...
  - Selecione o botão **Novo** na Barra de Ferramentas. Depois...
  - Selecione o botão de Seleção do Tipo de Item de Menu.
  - Na janela modal, selecione o item Pesquisa Inteligente para abrir
    uma lista e então selecione o item **Pesquisar**.

Para editar um item de menu de Pesquisa existente:

- Selecione seu Título na lista de Itens de Menu.

## Captura de Tela

![Detalhes da guia de Pesquisa Inteligente do Item de Menu](../../../pt/images/menu-items/smart-search-search-details-tab.png)

## Campos do Formulário

Se *Usar Global* for selecionado para qualquer opção, o valor padrão do 
*Pesquisa Inteligente: Opções* será usado.

### Aba Opções

![Aba Opções de Pesquisa do item de menu Pesquisa Inteligente](../../../pt/images/menu-items/smart-search-search-options-tab.png)

- **Filtros de Data** Mostrar ou ocultar os filtros de data de início e término na Pesquisa Avançada.
- **Pesquisa Avançada** Mostrar ou ocultar a Pesquisa Avançada para o elemento.
- **Expandir Pesquisa Avançada** Mostrar ou ocultar a Pesquisa Avançada em estado expandido.
- **Taxonomia do Resultado** ...?
- **Descrição do Resultado** Mostrar ou ocultar uma descrição sob o link nos resultados da pesquisa.
- **Comprimento da Descrição** O número de caracteres da descrição a serem exibidos 
  nos resultados da pesquisa. O padrão é 255.
- **Data do Resultado** ...?
- **URL do Resultado** Mostrar ou ocultar o URL do item de resultado nos resultados de pesquisa. O URL
  está localizado sob a descrição.

### Aba Avançada

![Aba Avançada de Pesquisa do item de menu Pesquisa Inteligente](../../../pt/images/menu-items/smart-search-search-advanced-tab.png)

- **Exibir Seleção** Mostrar ou ocultar o controle Exibir Nº que permite ao usuário 
  selecionar o número de itens a serem exibidos na lista.
- **Paginação** Mostrar ou ocultar o suporte à Paginação. A Paginação fornece
  links de página na parte inferior da página que permitem ao Usuário navegar
  para páginas adicionais. Estes são necessários se os itens listados não couberem
  em uma página.
  As seguintes opções estão disponíveis.
  - *Usar Global* Usar o valor padrão da tela de opções do componente.
  - *Auto* Links de paginação exibidos se necessário.
  - *Mostrar* Links de paginação mostrados se necessário.
  - *Ocultar* Links de paginação não mostrados. Nota: Neste caso, os Usuários não
    poderão navegar para páginas adicionais.
- **Resultados da Paginação** Mostrar ou ocultar o número atual da página e o número total
  de páginas (por exemplo, *Página 1 de 2*) na parte inferior de cada página.
- **Permitir Pesquisa Vazia** Se um filtro for selecionado, permite que uma string de
  pesquisa vazia inicie uma pesquisa com as restrições do filtro.
- **Você quis dizer** Sugestão de termos alternativos de pesquisa quando uma
  pesquisa não produz resultados.
- **Explicação da Consulta** Mostrar ou ocultar uma explicação detalhada da
  pesquisa solicitada.
- **Mostrar Campos de Ordenação** Mostrar ou ocultar campos de ordenação adicionais.
- **Campos de Ordenação Adicionais**: Escolha um ou mais campos nos quais ordenar os
  resultados da pesquisa:
  - *Relevância* Ordenar os resultados por relevância
  - *Título* Ordenar os resultados por título
  - *Data* Ordenar os resultados por data
  - *Preço de lista* Ordenar os resultados por preço de lista
  - *Preço de venda* Ordenar os resultados por preço de venda
- **Direção de Ordenação** Direção para ordenar os resultados da pesquisa.


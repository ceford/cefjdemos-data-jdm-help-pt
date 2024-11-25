<!-- Filename: Help4.x:Site_Modules:_Language_Switcher / Display title: Módulos: Troca de Idioma -->

## Descrição

O tipo de módulo *Language Switcher* permite alternar entre os idiomas de Conteúdo disponíveis. Selecionar um idioma irá levá-lo para a página correspondente desse idioma.

### Elementos Comuns

Alguns elementos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [Os Módulos: Aba de Módulos](jdocmanual?article=help/modules/modules-module-tab).
* [Os Módulos: Aba de Atribuição de Menu](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [Os Módulos: Aba Avançado](jdocmanual?article=help/modules/modules-advanced-tab).
* [A Aba de Permissões](jdocmanual?article=help/common-elements/edit-permissions).

## Como Acessar

- Selecione **Sistema → Gerenciar Painel → Módulos do Site** no menu do
  Administrador. Em seguida...
  - Para criar um novo módulo: selecione o botão **Novo** na Barra de Ferramentas. Em seguida...
    - Selecione o tipo de módulo necessário.
  - Para editar um módulo existente:
    - Encontre o módulo na lista de módulos instalados e selecione o
      link do título na coluna **Título**.

## Captura de Tela

![aba do módulo de troca de idioma](../../../pt/images/modules-site/modules-language-switcher-module-tab.png)

## Campos do Formulário

- **Título** O título do módulo. Este também é o título exibido para o módulo, dependendo do campo de formulário *Mostrar Título*.

### Aba do Módulo

#### Painel Esquerdo

- **Pré-texto** Este é o texto ou HTML que é exibido acima do seletor de idioma.
- **Pós-texto** Este é o texto ou HTML que é exibido abaixo do seletor de idioma.
- **Usar Dropdown** Os três itens seguintes mudam para *Sim* e *Não*:
  - **Não**
    - **Usar Bandeiras com Imagem** Se definido como *Sim*, exibe a escolha de idioma como bandeiras de imagem. Caso contrário, use os nomes nativos dos idiomas do conteúdo. Se definido como *Não*, aparece um campo extra: **Nomes Completos dos Idiomas**, que exibe um código de idioma de duas letras em maiúsculas para cada idioma.
    - **Idioma Ativo** Exibir ou não o idioma ativo. Se exibido, a classe `lang-active` será adicionada ao elemento.
    - **Exibição Horizontal** O padrão é definido como *Sim*, ou seja, para criar uma exibição em lista horizontal. Defina como *Não* para uma lista vertical.
  - **Sim** O item *Idioma Ativo* é mostrado como selecionado.
    - **Usar Bandeiras no Dropdown** Se definido como *Sim*, a bandeira do idioma é colocada antes do nome do idioma na lista suspensa.
    - **Nomes Completos dos Idiomas** Se definido como *Não*, exibe um código de idioma de duas letras em maiúsculas para cada idioma.
    - **Idioma Ativo** Sem efeito na lista suspensa.

*Traduzido por openai.com*


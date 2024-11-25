<!-- Filename: Help4.x:Menu_Item:_Components_Menu_Container / Display title: Item do Menu: Contêiner do Menu de Componentes  -->

## Descrição

O Container do Menu de Componentes é usado para mostrar um container de componentes na interface do Administrador. Um caso de uso pode ser o seguinte:

Suponha que você deseje mostrar links para um subconjunto dos Componentes em seu site apenas para certos usuários. Os Super Usuários verão links para tudo, é claro. Você pode fazer isso da seguinte forma:

- Crie um novo Grupo de Usuários chamado, por exemplo, Filial, com Público como pai.
- Defina as Permissões Globais para esse grupo para Permitir Login de Administrador.
- Crie um novo menu chamado, por exemplo, Menu Filial sem predefinições importadas.
- Crie um Módulo vinculado chamado, por exemplo, Menu Filial com o menu para mostrar como Menu Filial. Defina Verificar Menu como Não e Acesso como Público.
- Crie um item de menu Container de Menu de Componentes para o Menu Filial chamado, por exemplo, Componentes da Filial.
  - Oculte quaisquer componentes que você não deseje que os usuários da Filial vejam.
  - Mostre aqueles aos quais eles devem ter acesso.
- Defina as Permissões de Componente para o Grupo Filial como permitido para todos, exceto Configurar ACL e Configurar Opções.

Para um Super Usuário, o menu do Administrador terá uma duplicação óbvia de links. No entanto, um usuário da Filial verá apenas o menu Componentes da Filial e o Painel Inicial. Você precisará ajustar as permissões de Acesso dos módulos de Ícone Rápido lá também! E você realmente precisa criar um módulo de Painel para quaisquer componentes aos quais os usuários da Filial tenham acesso.

Para usuários que precisam de acesso a Artigos, você pode adicionar mais itens de menu no Menu Filial. Desta forma, você pode construir um menu completamente personalizado para os usuários da Filial.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Guia de Tipo de Link](jdocmanual?article=help/menu-items-common/menu-item-link-type).

## Como Acessar

Para criar um novo Item de Menu de Container de Componente:

- Crie um novo Menu em **Menus → Gerenciar** no menu do Administrador.
  - Selecione **Administrador** no seletor suspenso *Site/Administrador*.
  - Selecione o botão **Novo** na Barra de Ferramentas. Preencha o formulário:
    - **Título** Menu da Filial
    - **Nome Único** menu_filial
    - **Descrição** Menu personalizado para a Filial.
    - **Importar Predefinição** Nenhum
    - **Salvar**
    - **Permissões** Selecione o grupo *Filial* e defina todos para *Permitir*.
    - **Salvar & Fechar**
    - Selecione o botão **Criar um Módulo** e preencha o formulário de diálogo:
    - **Título** Componentes da Filial
    - **Verificar Menu** Não (caso contrário, haverá uma mensagem convidando você a
      *ativar o modo de recuperação do menu*.)
    - **Acesso** Especial
    - **Posição** Menu
- Selecione **Menus → \[nome do menu\]** no menu do Administrador.
- Selecione o botão **Novo** na Barra de Ferramentas para criar um novo item de menu.
- Selecione o botão **Selecionar** do Tipo de Item de Menu.
- Selecione o link **Lista de Container de Componentes** em **Links do Sistema** no diálogo modal do Tipo de Item de Menu.

Para editar um Item de Menu de Container de Componente existente, selecione seu Título na lista de Itens de Menu.

## Captura de tela

![Menu Item Componentes Container de Menu](../../../en/images/menu-items/administrator-components-menu-container.png)

## Campos do Formulário

- **Nome** O nome do item do menu, por exemplo, *Menu da Filial*. Ele aparecerá na parte inferior do menu do Administrador.
- **Alias** O nome interno do item. Normalmente, você pode deixar este campo em branco e o Joomla preencherá um valor padrão: Título em letras minúsculas e com hifens em vez de espaços.

### Aba de Detalhes

#### Painel Esquerdo

- **Tipo de Item de Menu** Neste caso, *Contêiner do Menu de Componentes*.
- **Mostrar ou Ocultar Itens de Menu** Lista de itens de menu com botões para definir o status de visibilidade. Se um item pai estiver configurado para *Ocultar*, todos os itens filhos também ficarão ocultos, mesmo que estejam configurados para *Mostrar*.

#### Painel Direito

- **Menu** Mostra em qual menu o link aparecerá.
- **Pai** O item (categoria, item de menu, etc.) que é o pai do item que está sendo editado.
- **Ordenação** Indica a ordem deste Item de Menu no Menu. A ordem padrão é adicionar o Item de Menu ao final do Menu. Este Item de Menu será movido para a posição de ordem logo após o Item de Menu selecionado na lista suspensa. Observe que a Ordem dos Itens de Menu também pode ser alterada no Gerenciador de Itens de Menu.
- **Status** O status de publicação do item.
- **Nota** Normalmente, é para uso do administrador do site (por exemplo, para documentar informações sobre este item) e não aparece no Frontend do site.

## Dicas

- O item **Componentes da Filial** aparece na parte inferior do menu do Administrador. O acesso ao menu principal do Administrador e a esta seção pode ser personalizado para o grupo Filial.


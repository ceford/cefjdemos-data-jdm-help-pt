<!-- Filename: Help4.x:Templates:_Edit_Style / Display title: Modelos: Editar Estilo -->

## Descrição

A página *Templates: Editar Estilo* é usada para editar estilos de template. Quando um template é instalado pela primeira vez, um estilo padrão é criado para ele. O estilo padrão do template terá o mesmo nome do template com o sufixo *- Padrão*. Para criar uma variação diferente do estilo padrão do template, marque a caixa de seleção do estilo padrão e pressione o ícone *Duplicar* na barra de ferramentas. Em seguida, edite a duplicata.

### Elementos Comuns

Alguns elementos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).

## Como Acessar

- Selecione **Sistema → Painel de Modelos → Estilos de Modelos do Site**
  no menu do Administrador. Ou...
- Selecione **Sistema → Painel de Modelos → Estilos de Modelos do Administrador**
  no menu do Administrador. Em seguida...
  - Selecione o nome do Estilo de Modelo para editar na coluna Estilo.

## Captura de Tela

![modelos cassiopeia editar estilo aba do editor](../../../pt/images/templates/templates-site-edit-style-details-tab.png)

## Campos do Formulário

- **Nome do Estilo** O nome do estilo. Este é o nome que será exibido na coluna de Estilo da tela *Template: Estilos*.

### Aba de Detalhes

- **Informação** O nome do template, indicador de Site ou Administrador e uma breve descrição.

### Aba Avançada

![templates cassiopeia editar aba de editor de estilo](../../../pt/images/templates/templates-site-edit-style-advanced-tab.png)

Esta seção pode não estar presente para todos os estilos. Se um template do qual um estilo é derivado tiver opções configuráveis, elas estarão presentes aqui. São essas opções configuráveis ​​adicionais que permitem que você tenha múltiplos estilos diferentes de templates com variações dessas opções. As opções disponíveis variam com base nas opções que o desenvolvedor do template disponibilizou.

### Configurações de Cor do Atum

O template padrão do Administrador permite que você experimente variações de cor. Salve e veja!

### Configurações de Imagem do Atum

Você pode selecionar uma imagem para substituir o **Logo de Login** no formulário de login do Administrador e o **Logo da Marca** na Barra de Título do Administrador em modo expandido e em modo compacto. Os padrões são os logos da Marca Joomla. Na Barra de Título, a palavra Joomla! está presente na versão **Marca Grande** e omitida na versão **Marca Pequena**. Selecione **Alternar Menu** para ver a mudança.

Se você fornecer sua própria Marca Pequena, também precisará fornecer uma substituição de estilo de largura. Para fazer isso, crie um arquivo user.css na raiz do template e insira o seguinte, mas substitua 3rem por uma largura adequada para sua imagem:

       .header .logo.small {
           width: 3rem;
       }

### Aba de Atribuição de Menu

![templates cassiopeia editar aba de editor de estilo de menu](../../../pt/images/templates/templates-site-edit-style-menu-assignment-tab.png)

Esta seção contém todos os itens de menu configurados no seu site Joomla! Para aplicar o estilo atual à página web correspondente a um item de menu, marque a caixa ao lado do item de menu. Você pode pressionar o botão *Alternar Seleção* para inverter as seleções de itens de menu.

**Nota** Se uma caixa de seleção estiver desativada e não puder ser marcada, isso pode ser porque o item de menu está em uso por outro usuário. Você pode verificar se este é o caso indo à tela do gerenciador de menus para o menu em questão. Se houver um símbolo de cadeado ao lado do item de menu, ele está atualmente em uso por outro usuário.

*Traduzido por openai.com*


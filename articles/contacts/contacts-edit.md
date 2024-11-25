<!-- Filename: Help5.x:Contacts:_Edit / Display title: Contatos: Editar   -->

## Descrição

O *Formulário de Edição de Contatos* é usado para adicionar um novo contato ou editar um contato existente.

**Atenção:** Se um contato tiver um item de menu, então as Configurações do Menu de Contato substituirão algumas configurações disponíveis aqui. Tenha cuidado para não divulgar informações pessoais por engano!

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba de Esquema](jdocmanual?article=help/common-elements/edit-schema).
* [A Aba de Publicação](jdocmanual?article=help/common-elements/edit-publishing).
* [A Aba de Associações](jdocmanual?article=help/common-elements/edit-associations).
* [O Popup de Histórico de Versões](jdocmanual?article=help/common-elements/edit-version-history).

## Como Acessar

- Selecione **Componentes → Contatos → Contatos** no menu do Administrador.
- Para **Adicionar** um novo Contato:
  - Selecione o botão **Novo** na Barra de Ferramentas.
- Para **Editar** um Contato existente:
  - Selecione um título de contato na coluna **Título**.

## Captura de Tela

![Contatos aba editar contato](../../../pt/images/contacts/contacts-edit-contact-tab.png)

## Campos do Formulário

Nesta seção, você pode inserir informações sobre o Contato, como nome, endereço, e-mail, etc. As opções permitem que você controle configurações, como quais informações serão exibidas para cada Contato.

- **Nome** O nome completo do Contato.
- **Apelido** O nome interno do item. Normalmente, você pode deixar isso em branco e o Joomla preencherá um valor padrão com o Título em letras minúsculas e com traços em vez de espaços.

### Aba Editar Contato

Aqui você insere as informações básicas sobre o contato.

- **Usuário Vinculado** Se este Contato estiver vinculado a um usuário, selecione o ícone *Selecionar Usuário* para revelar um formulário pop-up de onde selecionar um dos usuários registrados. Um usuário vinculado pode ser removido com o botão *- Sem Usuário -* no formulário pop-up Selecionar Usuário.
- **Imagem** Imagem a ser exibida para este Contato. Selecione um arquivo de imagem na caixa de lista suspensa. Isso lista as imagens na pasta 'images/stories'. As imagens podem ser carregadas usando o componente Mídia.
- **Posição:** A posição atual do Contato.
- **E-mail** O endereço de e-mail do Contato. Note que endereços de e-mail no Joomla! podem ser protegidos de "spambots" ativando o Plugin "Cloaking de E-mail de Conteúdo". Isso está ativado por padrão.
- **Endereço** O endereço residencial do Contato.
- **Cidade ou Bairro** A cidade ou bairro do Contato.
- **Estado ou Província** O estado ou província do Contato.
- **Código Postal / CEP** O código postal do Contato.
- **País** O país do Contato.
- **Telefone** O número de telefone do Contato.
- **Celular** O número de celular do Contato.
- **Fax** O número de fax do Contato.
- **Website** O endereço do site do Contato.
- **Campos de Ordenação** Para habilitar campos de ordenação para listas de Categoria, vá para a tela **Contatos → Opções** e defina **Layouts de Lista → Ordenar Por** para **Nome de Ordenação**. Então você precisa usar palavras reais para a ordenação. Por exemplo, defina o Primeiro Campo de Ordenação para **Doe**, segundo campo para **John** para o primeiro contato; depois, Primeiro Campo de Ordenação para **Doe**, segundo campo para **Jane** para o segundo contato. O terceiro campo não é utilizado neste caso. Os campos de ordenação são campos de caracteres, então, se você quiser ordenar por idade, precisa inserir 0x para idades abaixo de 10, como 08, por exemplo.
  - **Primeiro Campo de Ordenação** O nome a ser usado como primeiro campo de ordenação.
  - **Segundo Campo de Ordenação** O nome a ser usado como segundo campo de ordenação.
  - **Terceiro Campo de Ordenação** O nome a ser usado como terceiro campo de ordenação.
- **Status**: Status de publicação do item. Os valores possíveis são:
  - *Publicado*: O item está publicado. Este é o único estado que permitirá que usuários regulares do site vejam este item.
  - *Não Publicado*: O item não está publicado.
  - *Arquivado*: O item foi arquivado.
  - *Excluído*: O item foi enviado para a Lixeira.
- **Categoria** A Categoria à qual esse item pertence.
- **Destacado** Indica se o item será exibido na visualização em destaque.
- **Acesso** O Nível de Acesso de visualização para este item.
- **Idioma** Idioma do item.
- **Tags** Insira uma ou mais tags opcionais para este item. Você pode selecionar tags existentes digitando as primeiras letras. Você também pode criar novas tags inserindo-as aqui. As tags permitem ver listas de itens relacionados em tipos de conteúdo (por exemplo, artigos, contatos e categorias).
- **Nota da Versão** Campo opcional para identificar esta versão do item na janela de Histórico de Versões do item.

### Aba Informações Diversas

![Aba editar contato de contatos](../../../pt/images/contacts/contacts-edit-miscellaneous-tab.png)

Outras informações sobre este Contato podem ser inseridas usando o editor.

### Aba Exibição

![Aba editar contato de contatos](../../../pt/images/contacts/contacts-edit-display-tab.png)

- **Mostrar Categoria** Mostrar ou ocultar a categoria do Contato.
- **Mostrar Lista de Contatos** Mostrar ou ocultar a lista de Contatos.
- **Formato de Exibição** Determina o estilo usado para exibir seções do formulário de contato.
- **Tags** Se deve esconder ou mostrar quaisquer tags para este item.
- **Informações de Contato** Mostrar ou esconder as informações do Contato.
- **Informações Diversas** Mostrar ou esconder as informações diversas.
- **vCard** Mostrar ou ocultar o link vCard para este Contato.
- **Mostrar Artigos do Usuário** Se este contato estiver mapeado para um usuário, e isso estiver definido para Mostrar, uma lista de artigos criados por este usuário será mostrada.
- **\# Artigos para Listar** Número de artigos a serem listados.
- **Perfil do Usuário** Se este contato estiver mapeado para um usuário, e isso estiver definido para Mostrar, então o perfil deste usuário será exibido.
- **Mostrar Grupos de Campos Personalizados do Usuário** Mostrar campos personalizados do usuário que pertencem a todos ou apenas os grupos de campos selecionados.
- **Links de Contato** Mostrar ou ocultar os links de contato.
- **Rótulo do Link A** Rótulo para um link adicional para este contato.
- **URL do Link A** O URL do link adicional para este contato.
- **Rótulo do Link B** Rótulo para um link adicional para este contato.
- **URL do Link B** O URL do link adicional para este contato.
- **Rótulo do Link C** Rótulo para um link adicional para este contato.
- **URL do Link C** O URL do link adicional para este contato.
- **Rótulo do Link D** Rótulo para um link adicional para este contato.
- **URL do Link D** O URL do link adicional para este contato.
- **Rótulo do Link E** Rótulo para um link adicional para este contato.
- **URL do Link E** O URL do link adicional para este contato.
- **Layout** Usar um layout diferente do fornecido pela visualização do componente ou substituições nos modelos.

### Aba Formulário

![Aba editar contato de contatos](../../../pt/images/contacts/contacts-edit-form-tab.png)

- **Formulário de Contato** Mostrar ou ocultar o formulário de E-mail. Se Mostrar estiver selecionado, um formulário é exibido permitindo ao usuário enviar um e-mail para o Contato a partir do site.
- **Enviar Cópia ao Remetente** Mostrar ou ocultar a caixa de seleção: *Enviar uma cópia desta mensagem para o seu próprio endereço de e-mail.*
- **Verificação de Sessão** Verificar a existência de um cookie de sessão. Isso significa que usuários sem cookies habilitados não poderão enviar e-mails.
- **Resposta Personalizada** Desativa a resposta automatizada, permitindo que Plugins tratem a integração com outros sistemas.
- **Redirecionamento de Contato** Insira um URL alternativo onde o usuário será redirecionado após o envio do e-mail.

*Traduzido por openai.com*


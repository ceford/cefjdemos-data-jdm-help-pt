<!-- Filename: Help4.x:Edit_Permissions / Display title: Editar Permissões -->

## Propósito

Muitas extensões têm telas de edição com uma aba de Permissões que é usada para mudar as permissões alocadas aos Grupos de Usuários. O número de Grupos de Usuários pode variar, já que grupos personalizados podem ser adicionados para usos especiais. O número de Ações que podem ser alteradas também varia de acordo com a extensão. Este artigo é uma breve descrição das telas de permissões para tais propósitos especiais.

Imagine que há um usuário que cuida da Mídia (imagens e arquivos), mas não tem permissão para outras responsabilidades. Um grupo chamado Oddjob foi criado e atribuído ao nível de acesso Especial. Um usuário também chamado Oddjob foi criado e atribuído ao grupo Oddjob.

Para mais informações detalhadas sobre Grupos de Usuários, Níveis de Acesso e Permissões, existe um tutorial separado sobre [Controle de Acesso](jdocmanual?article=user/users/access-control).

## Permissões de Configuração Global

Neste exemplo, os usuários do grupo Oddjob foram atribuídos à permissão Global
para fazer login na interface do Administrador, mas nada mais.

![Captura de Tela de Permissões](../../../pt/images/common-elements/global-configuration-permissions-tab.png)

## Permissões de Configuração do Componente

Para acessar um componente específico, as permissões devem ser definidas nas opções do componente. Neste exemplo, as opções do componente Media.

![Captura de Tela do Media](../../../pt/images/common-elements/media-options-permissions-tab.png)

Você notará que este componente tem menos Ações disponíveis e o grupo Oddjob tem permissões suficientes apenas para realizar o trabalho.

Para alterar as permissões para este componente:

* Selecione o Grupo clicando no título localizado à esquerda.<br>
  Encontre a Ação desejada.
  * Delete (Excluir). Os usuários podem excluir este artigo.
  * Edit (Editar). Os usuários podem editar este artigo.
  * Edit State (Editar Estado). O usuário pode mudar o estado de publicação e informações relacionadas a este artigo.
* Selecione a permissão desejada para a ação que você deseja alterar.
  * Inherited (Herdado). Herdado para usuários deste Grupo da Configuração Global, Opções de Artigos ou Categoria de Artigos.
  * Allowed (Permitido). Permitido para usuários deste Grupo. Nota: Se esta ação for Negada em um dos níveis superiores, a permissão de Permitido aqui não terá efeito. Uma configuração de Negado não pode ser substituída.
  * Denied (Negado). Negado para usuários deste Grupo.
* Clique em Salvar na Barra de Ferramentas no topo. Quando a tela atualizar, a coluna Configuração Calculada mostrará a permissão efetiva para este Grupo e Ação.

## A Experiência do Usuário

Após o login, um usuário no grupo Oddjob verá quaisquer módulos do Painel Inicial
que tenham o acesso **Especial** configurado e um item de link no Menu para o componente de Mídia.

![Painel Inicial para Oddjob](../../../pt/images/common-elements/home-dashboard-for-oddjob.png)

E a tela de Mídia para o usuário Oddjob é como esperado:

![Tela de Mídia para Oddjob](../../../pt/images/common-elements/media-screen-for-oddjob.png)

*Traduzido por openai.com*  


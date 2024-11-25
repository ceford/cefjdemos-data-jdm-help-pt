<!-- Filename: Help4.x:Users:_Edit_Profile / Display title: Usuários: Novo ou Editar   -->

## Descrição

A página *Usuários: Novo ou Editar* é usada para criar um novo usuário ou editar um usuário existente.

### Elementos Comuns

Alguns elementos desta página são abordados em artigos de ajuda separados:

* [Barras de ferramentas](jdocmanual?article=help/common-elements/toolbars).

## Como acessar

Para editar um usuário existente:

- Selecione **Usuários → Gerenciar** no menu do Administrador. Depois...
  - Procure o usuário desejado e selecione o link do nome na
    coluna **Nome**.

Para criar um novo usuário:

- Selecione **Usuários → Gerenciar** no menu do Administrador. Depois...
  - Selecione o botão **Novo** na Barra de Ferramentas.
- Ou... Selecione **Usuários → Gerenciar → Ícone de Mais** no
  menu do Administrador.
- Ou... Selecione **Usuários → Ícone do Painel** no menu do Administrador. Depois...
  - Selecione o ícone de **Mais** no painel de Usuários.
- Ou... Selecione **Painel Inicial → Painel do Site → Ícone de Mais de Usuários**
  a partir do menu do Administrador.

## Captura de Tela

![editar detalhes do usuário](../../../pt/images/users/users-edit-account-details-tab.png)

## Campos do Formulário

### Detalhes da Conta

- **Nome** Digite o nome do usuário.
- **Nome de Login** Insira o nome de login (Nome de Usuário) do usuário.
- **Senha** Preencha com uma nova senha. Embora este campo não seja 
  obrigatório, o usuário não conseguirá fazer login se nenhuma senha for definida.
- **Confirmar Senha** Preencha novamente a senha do campo acima para 
  verificá-la. Este campo é obrigatório se você preencher o campo Nova 
  Senha.
- **Email** Informe um endereço de email para o usuário.
- **Data de Registro** Data de registro do usuário.
- **Data da Última Visita** Data da última visita do usuário ao site.
- **Data da Última Redefinição** Data e hora da última redefinição de senha.
- **Contagem de Redefinições de Senha** Número de redefinições de senha desde 
  o início da última redefinição.
- **Receber Emails do Sistema** (*Sim*/*Não*) Se configurado como sim, o 
  usuário receberá emails do sistema.
- **Status do Usuário** (*Bloqueado*/*Ativo*) Ativar ou bloquear este usuário.
- **Exigir Redefinição de Senha** (*Sim*/*Não*) Se configurado como sim, o 
  usuário terá que redefinir sua senha na próxima vez que fizer login no site.
- **ID** Número do registro no banco de dados.

### Guia de Grupos de Usuários Atribuídos

![guia de grupo de usuários atribuídos ao editar usuário](../../../pt/images/users/users-edit-assigned-user-groups-tab.png)

O padrão é *Registrado*, mas pode ser alterado na página *Usuário: Opções*.

### Configurações Básicas

![guia de configurações básicas ao editar usuário](../../../pt/images/users/users-edit-basic-settings-tab.png)

- **Estilo do Template do Backend** Selecione um estilo de template para a 
  interface administrativa do Backend. Isso afetará apenas este usuário.
- **Idioma do Backend** Selecione o idioma para a interface administrativa 
  do Backend. Isso afetará apenas este usuário.
- **Idioma do Frontend** Selecione o idioma para a interface do frontend. 
  Isso afetará apenas este usuário.
- **Editor** Selecione um editor para este usuário. O padrão é TinyMCE, 
  a menos que seja alterado na Configuração Global. 
- **Fuso Horário** Há uma longa lista de fusos horários para escolher,
  organizada por continente, com a Europa perto do final. O fuso horário 
  padrão do site é definido na Configuração Global.

### Configurações de Acessibilidade

![guia de configurações de acessibilidade ao editar usuário](../../../pt/images/users/users-edit-accessibility-settings-tab.png)

- **Monocromático** Sim/Não
- **Alto Contraste** Sim/Não
- **Destacar Links** Sim/Não
- **Aumentar Tamanho da Fonte** Sim/Não

### Opções de Log de Ações do Usuário

Esta guia está disponível apenas para Super Usuários!

- **Enviar notificações para Log de Ações do Usuário** Se configurado como 
  sim, o usuário receberá notificações do log de ações do usuário por email.
- **Selecionar eventos para ser notificado** Selecione as notificações do 
  log de ações do usuário a serem enviadas por email.

### Autenticação Web W3C (WebAuthn) Login

Esta guia está presente apenas quando o site é acessado via https. Para 
configurar o login sem senha, é necessário um dispositivo de hardware, 
disponível na Amazon e em lojas semelhantes por cerca de £15, ou um 
dispositivo com reconhecimento de impressão digital ou facial ou software 
biométrico semelhante. Você pode adicionar mais de um autenticador. Uma 
vez configurado, você pode fazer login clicando no botão de Autenticação 
Web no formulário de login e, em seguida, pressionando o botão no 
dispositivo quando solicitado.

Essa guia está presente, mas não pode ser usada no formulário de edição 
de Usuário, pois o login sem senha só pode ser configurado pelo próprio 
usuário através do formulário de Editar Perfil.

### Token da API Joomla

Esta guia é usada para gerenciar os tokens de segurança utilizados para 
autenticar no aplicativo API Joomla (acesso remoto ao seu site). Se você 
não sabe o que isso faz, é provável que não precise e pode ignorar 
estas configurações com segurança.

O token só é visível para a sua própria conta.

### Autenticação Multifator

![guia de autenticação multifator ao editar usuário](../../../pt/images/users/users-edit-multi-factor-authentication-tab.png)

Esta guia permite que você configure um ou mais métodos para permitir 
acesso à sua conta após o login com Nome de Usuário e Senha. Está 
disponível apenas ao editar seu próprio perfil. Existem vários métodos 
disponíveis. Se você perder o acesso a um método por qualquer motivo, 
pode escolher outro método a partir da tela de verificação pós-login. 
Os métodos alternativos devem ter sido configurados com antecedência!

#### Códigos de Backup

Esse método gera um conjunto de números que você pode salvar ou 
imprimir. Cada número pode ser usado apenas uma vez, portanto, lembre-se 
de atualizar sua lista após o uso.

#### Código de Verificação

Um formulário extra para preencher com métodos alternativos de gerar o 
código. Dê uma olhada e clique no botão Cancelar se decidir não prosseguir.

#### Yubi Key

Isto é para outro tipo de chave de hardware que fornece um código em 
um display. Dê uma olhada e selecione Cancelar se decidir não prosseguir.

#### Autenticação Web

Para um dispositivo de hardware com um botão para pressionar. Dê uma 
olhada e selecione Cancelar se decidir não prosseguir. Note que este 
método será ignorado se você usar o método de Login WebAuthn separado.

#### Código por Email

Com este método, um código é enviado para o seu endereço de email. 
Você será solicitado a inserir esse código para obter acesso ao site. 
É um código de uso único. Um novo é enviado para cada login. Dê uma 
olhada e selecione Cancelar se decidir não prosseguir.

## Dicas

- Nome, Nome de Login e Email são obrigatórios.
- Se você não preencheu um idioma específico, editor, site de ajuda e/ou
  fuso horário, as configurações padrão da Configuração Global,
  Gerenciador de Idiomas e/ou Gerenciador de Templates serão usadas.

*Traduzido por openai.com*


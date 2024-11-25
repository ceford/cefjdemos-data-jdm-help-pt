<!-- Filename: Help4.x:Users:_Options / Display title: Usuários: Opções -->

## Descrição

A página *Usuários: Opções* é usada para definir opções globais para todos os usuários, incluindo:

- Captcha,
- registro permitido e tipo de registro,
- grupo de usuários padrão para novos usuários,
- redefinição de senha ou contador de nome de usuário,
- aviso por e-mail de registro de novo usuário para a administração e mais.

## Como Acessar

* Selecione **Site → Usuários** no *Painel Inicial*. Ou...
* Selecione **Usuários → Gerenciar** no menu do Administrador. Em seguida...
* Selecione o botão de ferramentas **Opções**

## Captura de Ecrã

![opções de utilizadores tab de opções do utilizador](../../../pt/images/users/users-options-user-options-tab.png)

## Campos do Formulário

### Aba de Opções de Usuário

- **Permitir Registro de Usuário**
  - *Sim* Os usuários podem se registrar no Frontend do site usando o
    link *Criar uma Conta* fornecido no formulário de Login.
  - *Não* O link *Criar uma Conta* não será exibido.
- **Grupo de Registro de Novo Usuário** O grupo ao qual os usuários são atribuídos por
  padrão quando se registram no site. Padrão é *Registrado*.
- **Grupo de Usuário Convidado** O grupo ao qual convidados são atribuídos (Convidados
  são visitantes do site que não estão logados). É possível
  criar conteúdo no site que é visível para convidados, mas não visível
  para usuários logados.
- **Enviar Senha** Se configurado para *Sim* a primeira senha do usuário será
  enviada por e-mail como parte do e-mail de registro.
- **Ativação de Conta de Novo Usuário**
  - *Nenhuma* Conta de usuário será ativada imediatamente sem qualquer ação necessária.
  - *Própria* O usuário receberá um e-mail com um link de ativação. A
    conta será ativada quando o usuário selecionar o link de ativação.
  - *Administrador* O usuário receberá um e-mail com um link de ativação.
    Quando o usuário selecionar este link, o Administrador do Site será notificado por
    e-mail e solicitado a ativar a conta do usuário.
- **Enviar E-mail para Administradores** Enviar notificação por e-mail para
  administradores com *Ativação de Conta de Novo Usuário* configurada para *Nenhuma* ou *Própria*.
- **Captcha** O plugin Captcha para Registro de Conta de Usuário, Lembrete de Senha
  de Usuário e Lembrete de Nome de Usuário.
- **Parâmetros de Usuário no Frontend**
  - *Mostrar* Os usuários poderão modificar Configurações Básicas do Frontend do site.
  - *Ocultar* O usuário não poderá alterar essas configurações.
- **Idioma do Frontend** Mostrar ou Ocultar o idioma do site. ...
- **Alterar Nome de Usuário** Permitir que o usuário altere o Nome de Usuário.

### Aba de Opções de Domínio de Email

![opções de usuários aba de dominios de email](../../../pt/images/users/users-options-email-domain-options-tab.png)

- **Nome de Domínio** Insira uma lista de domínios de e-mail permitidos e não permitidos.
  Por padrão, todos os domínios são permitidos. Curingas (\*) são suportados. Por exemplo:
  - \* (Asterisco): Permite ou não permite todos os domínios
  - \*.com: Permite ou não permite todos os domínios '.com'
  - \*.joomla.org: Permite ou não permite todos os subdomínios 'joomla.org'.
- **Regra** Selecione se deseja permitir ou não permitir o domínio.

### Aba de Opções de Senha

![opções de usuários aba de opções de senha](../../../pt/images/users/users-options-password-options-tab.png)

- **Contagem Máxima de Reconfiguração** O número máximo de reconfigurações de senha permitidas
  dentro do período de tempo. Zero indica sem limite.
- **Tempo de Reconfiguração** O período de tempo, em horas, para o contador de reconfiguração.
- **Comprimento Mínimo** Defina o comprimento mínimo para uma senha.
- **Mínimo de Números** Defina o número mínimo de números que devem ser
  incluídos em uma senha.
- **Mínimo de Símbolos** Defina o número mínimo de símbolos (como !@#\$)
  necessários em uma senha.
- **Mínimo de Letras Maiúsculas** Defina o número mínimo de caracteres alfabéticos
  maiúsculos necessários para uma senha.
- **Mínimo de Letras Minúsculas** Defina o número mínimo de caracteres alfabéticos
  minúsculos necessários para uma senha.

### Aba de Autenticação Multifatorial

![opções de usuários aba de autenticação multifatorial](../../../pt/images/users/users-options-multi-factor-authentication-tab.png)

- **Posições de módulo permitidas no frontend** Ao exibir a página de
  Autenticação Multifatorial no frontend, todos os módulos serão ocultados, exceto
  aqueles nas posições selecionadas aqui.
- **Mostrar título no frontend** Exibir um título na página de verificação
  de Autenticação Multifatorial do frontend? Observe que o
  título é sempre exibido no backend. Se precisar alterar o
  título, por favor, sobrescreva a chave de idioma `COM_USERS_HEADING_MFA` usando
  Línguas: Sobrescritas.
- **Posições de módulo permitidas no backend** Ao exibir a página de
  Autenticação Multifatorial no backend, todos os módulos serão ocultados, exceto
  aqueles nas posições selecionadas aqui. Observe que os módulos na
  posição `título` são sempre mostrados: isso é necessário para mostrar o
  ícone e título da página do backend.
- **Desativar Autenticação Multifatorial** Qualquer usuário que pertença a *qualquer*
  dos grupos de usuários selecionados estará isento da Autenticação
  Multifatorial. Mesmo que tenham configurado métodos de Autenticação
  Multifatorial, não serão solicitados a usá-los ao fazerem login,
  nem poderão visualizá-los, removê-los ou alterar sua
  configuração.
- **Impor Autenticação Multifatorial** Qualquer usuário que pertença a *qualquer*
  dos grupos de usuários selecionados será obrigado a habilitar a
  Autenticação Multifatorial antes de poder usar o site.
- **Estilo de template do frontend** Escolha o estilo de template do
  frontend para usar na página de Autenticação Multifatorial. Selecione *Usar Padrão*
  para usar o estilo de template padrão do site.
- **Autenticação Multifatorial após login silencioso** O usuário deve
  passar pela Autenticação Multifatorial após um login silencioso do usuário?
  Logins silenciosos são aqueles que não requerem um nome de usuário e
  senha, por exemplo, o recurso Lembrar-me, WebAuthn etc.
- **Tipos de resposta de autenticação de login silencioso (para especialistas)** Para
  especialistas. Uma lista separada por vírgulas de tipos de resposta de
  autenticação do Joomla que são considerados logins silenciosos. O padrão é `cookie` (o
  recurso Lembrar-me) e `passwordless` (WebAuthn).
- **Incorporar novos usuários** Se o usuário ainda não tiver configurado a Autenticação
  Multifatorial e esta opção estiver ativada, será redirecionado para
  a página de configuração de Autenticação Multifatorial ou para a URL personalizada que você configurar
  abaixo. Esta é uma maneira simples de informar seus
  usuários que a Autenticação Multifatorial é uma opção no seu site.
- **URL de redirecionamento personalizada** Se não estiver vazio, redireciona para
  esta URL em vez da página de configuração de Autenticação Multifatorial
  quando a opção acima estiver ativada. Aviso: Deve ser uma URL dentro do seu
  site. Não é possível fazer login em um link externo ou em um subdomínio diferente.

### Aba de Histórico de Notas de Usuário

![opções de usuários aba de histórico de notas de usuário](../../../pt/images/users/users-options-user-notes-history-tab.png)

- **Habilitar Versões** Salvar histórico de versões para Notas de Usuário.
- **Máximo de Versões** O número máximo de versões para armazenar de uma
  Nota de Usuário. Se uma Nota de Usuário for salva e o número máximo de versões
  for atingido, a versão mais antiga será excluída automaticamente. Se
  configurado para 0, as versões nunca serão excluídas automaticamente.

### Aba de Enviar Emails em Massa para Usuários

![opções de usuários aba de enviar emails em massa para usuários](../../../pt/images/users/users-options-mass-mail-users-tab.png)

- **Prefixo do Assunto** Insira texto opcional para ser inserido automaticamente
  antes do assunto do email em massa.
- **Sufixo do Corpo do Email** Insira texto opcional para ser inserido automaticamente
  após o corpo do email (por exemplo, uma assinatura).

### Aba de Integração

![opções de usuários aba de integração](../../../pt/images/users/users-options-integration-tab.png)

- **Habilitar Campos Personalizados** Habilitar a criação de campos personalizados.

## Dicas

Se você é um usuário iniciante, mantenha os valores padrões aqui até aprender mais sobre o uso das opções globais.

*Traduzido por openai.com*  


<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_System_Group / Display title: Grupo do Sistema   -->

## Descrição do Grupo

### Sistema - Recursos Adicionais de Acessibilidade

Esse plugin adiciona uma barra de ferramentas de acessibilidade ao seu site com opções de acessibilidade adicionais.

![Formulário de recursos adicionais de acessibilidade do sistema](../../../en/images/plugins/plugin-group-system-additional-accessibility-features.png)

### Sistema - Depuração

Esse plugin fornece informações de depuração. O relatório é exibido abaixo da tela principal das interfaces de frontend e backend de uma instalação do Joomla!

#### Aba do Plugin

![Formulário de depuração do sistema aba do plugin](../../../en/images/plugins/plugin-group-system-debug-plugin-tab.png)

- **Grupos Permitidos** Grupos de usuários que verão as informações de depuração quando ativado.
- **Mostrar Perfil** Determina se as informações de pontos de referência do perfil serão exibidas.
- **Mostrar Consultas** Determina se o log de consultas SQL será incluído nas informações de depuração.
- **Mostrar Uso de Memória** Determina se os dados de uso de memória serão incluídos nas informações de depuração.

#### Aba de Idioma

![Formulário de depuração do sistema aba de idioma](../../../en/images/plugins/plugin-group-system-debug-language-tab.png)

- **Mostrar erros ao analisar arquivos de idioma** Determina se uma lista de arquivos de idioma com erros é exibida devido à não conformidade com a especificação de arquivo de idioma do Joomla!
- **Mostrar Arquivos de Idioma** Determina se os arquivos de idioma carregados para gerar a página serão exibidos.
- **Mostrar String de Idioma** Determina se strings de idioma indefinidas serão incluídas nas informações de depuração.
- **Remover Primeira Palavra** Determina se sempre será removida a primeira palavra em strings de várias palavras.
- **Remover do Início** Remove as palavras especificadas do início da string de idioma. Para múltiplas palavras, separe cada palavra com o caractere pipe ( | ), como: palavra1|palavra2
- **Remover do Final** Remove as palavras especificadas do final da string de idioma. Para múltiplas palavras, separe cada palavra com o caractere pipe ( | ), como: palavra1|palavra2

#### Aba de Registro

![Formulário de depuração do sistema aba de registro](../../../en/images/plugins/plugin-group-system-debug-logging-tab.png)

### Sistema - Campos

O plugin de campos do sistema é necessário para exibir os campos personalizados.

### Sistema - Cabeçalhos HTTP

Este plugin pode definir Cabeçalhos HTTP de Segurança. Por favor, consulte a documentação de Gerenciamento de Cabeçalhos HTTP para mais detalhes sobre este plugin.

![Formulário de cabeçalhos http do sistema](../../../en/images/plugins/plugin-group-system-http-headers.png)

### Sistema - Destaque

Plugin do sistema para destacar termos especificados.

### Sistema - Agendador de Tarefas

Este plugin procura por tarefas de plugin de trabalho para executar.

![Formulário de agendador de tarefas do sistema](../../../en/images/plugins/plugin-group-system-job-scheduler.png)

- **Frequência (em minutos)** Ajuste para zero para executar em todos os carregamentos de página (para testes).
- **Webcron** Defina como Sim para chamar como um comando CLI. Para mais informações, veja Escrevendo uma Aplicação CLI.
- **Chave de Ativação** A chave a ser passada em um comando Webcron.

### Sistema - Estatísticas do Joomla!

![Formulário de estatísticas do joomla do sistema](../../../en/images/plugins/plugin-group-system-joomla-statistics.png)

- **ID Único** Um identificador que permite ao projeto Joomla! contar instalações únicas do plugin. Isso é enviado juntamente com as estatísticas de volta ao servidor.
- **Intervalo (horas)** As estatísticas serão enviadas a cada X horas. O padrão é 12.
- **Modo** Selecione a forma como deseja que as estatísticas sejam enviadas.

### Sistema - Notificação de Atualização do Joomla!

![Formulário de notificação de atualização do joomla do sistema](../../../en/images/plugins/plugin-group-system-joomla-update-notification.png)

- **Emails de Super Usuários** Uma lista separada por vírgulas dos endereços de email que receberão os emails de notificação de atualização. Os endereços na lista DEVEM pertencer a usuários existentes do seu site que possuem o privilégio de Super Usuário. Se nenhum dos emails listados pertencer a Super Usuários, ou se for deixado em branco, todos os Super Usuários do site receberão o email de notificação de atualização.
- **Idioma do Email** Se você escolher Automático (padrão), o email de notificação de atualização para Super Usuários será no idioma do site no momento em que o plugin for acionado. Ao selecionar um idioma aqui você está forçando os emails de notificação de atualização a serem enviados nesse idioma específico.

### Sistema - Código do Idioma

Fornece a capacidade de alterar o código do idioma no documento HTML gerado para melhorar o SEO. Os campos aparecerão quando o plugin estiver habilitado e salvo. Mais informações em W3.org.

### Sistema - Filtro de Idiomas

![Formulário de filtro de idiomas do sistema](../../../en/images/plugins/plugin-group-system-language-filter.png)

- **Seleção de Idioma para novos Visitantes** Se deve escolher o idioma padrão do site ou detectar automaticamente as configurações do navegador.
- **Mudança Automática de Idioma** Esta opção mudará automaticamente o idioma do conteúdo usado no Frontend quando o idioma do site de um usuário for alterado.
- **Associações** Permite a associação de itens ao mudar de um idioma para outro.
- **Adicionar Meta Tags Alternativas** Adicionar meta tags alternativas para itens de menu com itens de menu associados em outros idiomas.
- **Adicionar Meta Tag x-default** Adicionar a meta tag x-default para melhorar o SEO.
- **Idioma x-default** Escolha o seu idioma x-default.
- **Remover Código de Idioma da URL** Determina se deve remover ou não o Código de Idioma da URL definido (ex. seu_nome_de_dominio/en) do seu Idioma do Conteúdo que corresponde ao idioma padrão do site quando a URL SEF está configurada como *Sim*.
- **Duração do Cookie** Os cookies de idioma podem ser configurados para expirar ao final da *Sessão* ou após um *Ano*.

### Sistema - Rotação de Logs

![Formulário de rotação de logs do sistema](../../../en/images/plugins/plugin-group-system-log-rotation.png)

- **Rotação de Logs (em dias)** Com que frequência os logs devem ser rotacionados.
- **Máximo de Logs** O número máximo de logs antigos para manter.

### Sistema - Logout

O plugin de logout do sistema permite que o Joomla redirecione o usuário para a página inicial se ele escolher fazer logout enquanto estiver em uma página de acesso protegido.

### Sistema - Cache de Página

Este plugin habilita o cache de página. O cache de página permite que o servidor web salve instantâneos de páginas e os utilize ao servir páginas web. Isso melhora o desempenho do seu site e reduz a carga de trabalho do servidor. Este plugin possui as seguintes opções:

![Formulário de cache de página do sistema](../../../en/images/plugins/plugin-group-system-page-cache.png)

- **Usar Cache do Navegador** Determina se o mecanismo para armazenar um cache de página no navegador local será usado ou não. O padrão é *Não*.
- **Excluir Itens de Menu** Selecione quais itens de menu você deseja excluir do cache.

### Sistema - Consentimento de Privacidade

Este plugin permite coletar o consentimento dos seus usuários para a política de privacidade do site e gerenciar a expiração do consentimento.

![Formulário de consentimento de privacidade do sistema](../../../en/images/plugins/plugin-group-system-privacy-consent.png)

- **Política de Privacidade Resumida** Permite que você digite um resumo da sua política de privacidade ou mantenha a existente.
- **Tipo de Privacidade** Escolha entre Artigo e Item de Menu. Dependendo da escolha, um ou outro dos dois campos seguintes estará presente.
- **Artigo de Privacidade** Selecione ou Crie um Artigo para sua política de privacidade para linkar ao formulário do seu usuário.
- **Item de Menu de Privacidade** Selecione ou Crie um Item de Menu vinculado a um Artigo contendo sua política de privacidade.
    - *Nota:* Tenha cuidado extra com sites multilíngues. É melhor garantir que o Artigo ou Item de Menu exista como Associações em todos os idiomas.
- **Mensagem de Redirecionamento** A mensagem que será exibida ao redirecionar Insira sua própria mensagem ou mantenha a existente.

![Formulário de consentimento de privacidade do sistema aba de expiração](../../../en/images/plugins/plugin-group-system-privacy-consent-expiration.png)

- **Habilitar** (Sim/Não) A expiração está desabilitada por padrão. Habilite se você quiser realizar verificações para a expiração de consentimentos de privacidade.
- **Verificação periódica (dias)** (0 a 120 dias) 30 dias por padrão. Se a Expiração estiver habilitada, defina o número de dias para realizar a verificação.
- **Expiração** (180 a 720 dias) 360 dias por padrão. Se a Expiração estiver habilitada, defina o número de dias quando o consentimento de privacidade expira.
- **Lembrete** (0 a 120 dias) 30 dias por padrão. Se a Expiração estiver habilitada, defina o número de dias quando um lembrete deve ser enviado antes da expiração do consentimento de privacidade.

### Sistema - Redirecionamento

![Formulário de redirecionamento do sistema](../../../en/images/plugins/plugin-group-system-redirect.png)

- **Coletar URLs** Essa opção controla a coleta de URLs. Isso é útil para evitar carga desnecessária no banco de dados.
- **Incluir Nome de Domínio em URLs Expirados** Salve a URL expirada como absoluta (incluindo domínio) ou relativa (excluindo domínio).
- **Excluir URLs** Defina expressões regulares ou termos que devem ser excluídos ao salvar.

### Sistema - Lembrar-me

Este plugin fornece a funcionalidade *Lembrar-me*. Isso permite que o site *lembre-se* do seu nome de usuário e senha para que você possa ser automaticamente logado ao retornar ao site. Este plugin não possui opções.

### Sistema - SEF

Este plugin adiciona suporte SEF a links no documento. Funciona diretamente no HTML e não requer uma tag especial. Possui as seguintes opções:

![Formulário sef do sistema](../../../en/images/plugins/plugin-group-system-sef.png)

- **Domínio do Site** Se o seu site puder ser acessado através de mais de um domínio, insira o domínio preferido (às vezes referido como canônico) aqui. Nota: https://example.com e https://www.example.com são domínios diferentes.

### Sistema - Limpeza de Dados de Sessão

![Formulário de limpeza de dados de sessão do sistema](../../../en/images/plugins/plugin-group-system-session-data-purge.png)

- **Habilitar Limpeza de Dados de Sessão** Quando habilitado, este plugin tentará purgar os dados expirados com base na frequência calculada pela probabilidade e divisor.
- **Habilitar Limpeza de Metadados de Sessão** Quando habilitado, este plugin limpará metadados opcionais de sessão do banco de dados. Note que esta operação não será executada quando o manipulador de banco de dados estiver em uso, pois esses dados são limpos como parte da operação de Limpeza de Dados de Sessão.
- **Probabilidade** Em combinação com o campo divisor, esses dois campos são usados para determinar a frequência da operação de limpeza de dados de sessão ser acionada em uma solicitação.
- **Divisor** Em combinação com o campo de probabilidade, esses dois campos são usados para determinar a frequência da operação de limpeza de dados de sessão ser acionada em uma solicitação. A probabilidade é calculada usando probabilidade/divisor, por exemplo, 1/100 significa que há uma chance de 1% de que o processo será executado em cada solicitação.

### Sistema - Pular para Navegação

O plugin cria um menu suspenso que consiste em links para os principais locais de uma página da web. Isso facilita para os usuários de teclado e leitores de tela pularem rapidamente para o local desejado escolhendo-o na lista de opções.

![Formulário pular para navegação do sistema](../../../en/images/plugins/plugin-group-system-skip-to-navigation.png)

### Sistema - Registro de Ações do Usuário

![Formulário de registro de ações do usuário do sistema](../../../en/images/plugins/plugin-group-system-user-actions-log.png)

- **Dias para excluir registros após** Insira quantos dias os registros devem ser mantidos antes de serem excluídos. Insira 0 se você não quiser excluir os registros.

### Sistema - Registro de Usuário

![Formulário de registro de usuário do sistema](../../../en/images/plugins/plugin-group-system-user-log.png)

- **Registrar Nomes de Usuário** Esta opção registrará o nome de usuário utilizado quando uma autenticação falhar.

*Traduzido por openai.com*


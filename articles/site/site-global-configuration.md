<!-- Filename: Help4.x:Site_Global_Configuration / Display title: Configuração Global  -->

## Descrição

A tela de Configuração Global permite que você configure o site Joomla
com suas configurações pessoais. Configurações feitas nesta tela se aplicam a
todo o site.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba de Permissões](jdocmanual?article=help/common-elements/edit-permissions).

## Como acessar

- Selecione **Painel do Sistema → Configuração Global** no Painel de Controle. Ou...
- Selecione **Sistema → Painel de Configuração → Configuração Global** no menu do Administrador.

## Captura de Tela

![guia de configuração global do site](../../../pt/images/site/global-configuration-site-tab.png)

## Campos de Formulário

### Aba Site

#### Painel do Site

- **Nome do Site** Insira o nome do website. Isso será usado em vários locais (por exemplo, na barra de título do navegador do Backend e nas páginas Offline do Site).
- **Site Offline** Selecione se o acesso ao Frontend está disponível.
- **Mensagem Offline**
  - *Ocultar*
  - *Usar Mensagem Personalizada* A mensagem usa o valor definido no campo *Mensagem Personalizada*.
  - *Usar Mensagem Padrão do Idioma do Site* A mensagem usa o valor definido no arquivo ini do idioma do site.
- **Imagem Offline** Selecione uma imagem para ser exibida na página offline. Certifique-se de que a imagem tenha menos de 400px de largura.
- **Edição Frontend** Selecione a edição para módulos e itens de menu.
- **Editor Padrão** Selecione o editor de texto padrão. Os usuários registrados poderão alterar sua preferência em seus dados pessoais.
- **Captcha Padrão** Selecione o captcha padrão para seu site. Pode ser necessário inserir informações requeridas no plugin do captcha.
- **Nível de Acesso Padrão** Selecione o nível de acesso padrão para novos itens.
- **Limite de Lista Padrão** Define o comprimento padrão das listas no Backend para todos os usuários.
- **Limite de Feed Padrão** Selecione o número de itens de conteúdo a serem mostrados nos feeds.
- **Endereço de Email do Feed** Os feeds RSS e Atom incluem o endereço de email do autor.
  - *Email do Autor* Incluir o email do autor do artigo do Perfil de Usuário no feed de notícias.
  - *Email do Site* Incluir o endereço de *Email de* do site para cada artigo.

#### Painel de Metadados

- **Descrição Meta do Site** Insira uma descrição geral do website que será usada pelos motores de busca.
- **Robôs** Instruções para robôs.
  - *indexar, seguir* Indexar esta página e seguir os links nesta página.
  - *não indexar, seguir* Não indexar esta página, mas ainda seguir os links na página. Por exemplo, você pode fazer isso para uma página de mapa do site onde deseja que os links sejam indexados, mas não deseja que esta página apareça nos motores de busca.
  - *indexar, não seguir* Indexar esta página, mas não seguir os links na página. Por exemplo, você pode querer fazer isso para um calendário de eventos onde deseja que a página apareça nos motores de busca, mas não deseja indexar cada evento.
  - *não indexar, não seguir* Não indexar esta página nem seguir os links na página.
- **Direitos de Conteúdo** Descreva quais direitos outros têm para usar este conteúdo. Isso é transmitido para os motores de busca usando a meta tag `rights` no cabeçalho HTML.
- **Meta Tag do Autor** Mostrar a meta tag do autor ao visualizar artigos.
- **Versão do Joomla** Controla se a meta tag `generator` no cabeçalho do documento HTML no Frontend e nos feeds Atom inclui a versão exata do site Joomla. É recomendado ocultá-la por motivos de segurança.

#### Painel de SEO

- **URLs Amigáveis para Motores de Busca** Selecione se os URLs são otimizados para motores de busca.
- **Usar Reescrita de URL**
  - *Apache e Litespeed* Renomeie `htaccess.txt` para `.htaccess`.
  - *IIS* Renomeie `web.config.txt` para `web.config`.
  - *NginX* você deve configurar seu servidor.
  - *Outros* Se estiver em dúvida, consulte sua empresa de hospedagem.
- **Adicionar Sufixo à URL** Se sim, o sistema adicionará um sufixo à URL com base no tipo do documento.
- **Aliases Unicode** Escolha entre transliteração e aliases unicode. A transliteração é o padrão.
- **Nome do Site nos Títulos das Páginas** Começar ou terminar todos os Títulos das Páginas com o nome do site (por exemplo, *Meu Nome de Site - Meu Nome de Artigo*).

#### Painel de Cookies

- **Domínio do Cookie** Domínio a ser usado ao definir cookies de sessão. Preceda o domínio com '.' se o cookie deve ser válido para todos os subdomínios.
- **Caminho do Cookie** Caminho para o qual o cookie deve ser válido.

### Aba Sistema

![imagem da aba de configuração global do sistema](../../../pt/images/site/global-configuration-system-tab.png)

#### Painel de Debug

- **Debug do Sistema** Se habilitado, informações de diagnóstico, traduções de idioma e erros de SQL (se presentes) serão exibidos. As informações serão exibidas ao pé de cada página que você visualizar dentro do Backend e Frontend do Joomla. Não é aconselhável deixar o modo de debug ativado ao operar um site ao vivo.
- **Debug de Idioma** Ative para ver os indicadores de debug `**...**` ou `??...??` na saída da página onde arquivos de Idioma do Joomla são usados para traduzir chaves de cadeia para seus valores traduzidos. O primeiro formato indica que a cadeia foi traduzida com sucesso. O segundo indica que o texto foi inserido em linguagem simples e não pode ser traduzido.
  - **Exibição de Idioma** Selecione se deve exibir a constante de idioma ou o valor do idioma ao depurar as cadeias de idioma.

#### Painel de Cache

- **Cache do Sistema** Ative o cache e defina o nível de cache.
  - *Nível Conservador* cache do sistema menor.
  - *Nível Progressivo* cache do sistema mais rápido e maior, inclui cache dos renderizadores de módulo. Não apropriado para sites extremamente grandes.
  - **Manipulador de Cache**
    - *Arquivo* O mecanismo de cache nativo é baseado em arquivos. Por favor, certifique-se de que as pastas de cache sejam graváveis.
  - **Cache Específico para Plataforma** Habilite quando a saída HTML móvel diferir de outros dispositivos.
  - **Tempo de Cache (minutos)** O tempo máximo que um arquivo de cache pode ser armazenado antes de ser atualizado.
  - **Caminho para a Pasta de Cache** Especifique uma pasta gravável para armazenar arquivos de cache se não desejar usar a pasta padrão.

#### Painel de Sessão

- **Manipulador de Sessão** O mecanismo pelo qual o Joomla identifica um Usuário uma vez conectado ao site usando cookies não persistentes.
  - *Banco de Dados* O manipulador de sessão de banco de dados é o padrão porque é o único que o Joomla pode configurar e controlar completamente por si só.
  - *Sistema de Arquivos* O manipulador de sistema de arquivos será ligeiramente mais eficiente que o manipulador de banco de dados, mas requer que o PHP seja configurado corretamente, caso contrário, pode falhar e o Joomla se tornará totalmente inutilizável.
    - *Caminho para Armazenamento de Sessão* Insira um caminho completo do sistema de arquivos. Assegure-se de que o caminho tenha permissões apropriadas para leitura e gravação de arquivos, e se a `coleta de lixo da sessão` estiver habilitada, para deletar arquivos deste. Se este caminho não estiver configurado, o Joomla dependerá da configuração de `session.save_path INI` do PHP ou usará o diretório temporário do sistema (como definido pela função PHP sys_get_temp_dir()). Se nenhum desses caminhos estiver configurado ou se as permissões estiverem erradas, então acabou. Para se recuperar, edite o arquivo configuration.php e configure `$session_handler = 'database'`.
  - *Outros manipuladores* APCu, Memcached, Redis e WinCache dependem de extensões PHP opcionais e podem estar disponíveis se o seu sistema os suportar. APCu ou WinCache podem não ser melhores do que a opção de sistema de arquivos *plain*. Os manipuladores Memcached e Redis são exagerados para o Joomla em um ambiente típico de hospedagem compartilhada. Esses tipos de manipuladores são bem-sucedidos se você estiver implantando o Joomla em um ambiente balanceado por carga onde vários servidores estão envolvidos e você precisa que os dados da sessão da aplicação estejam disponíveis em todos os servidores.
- **Tempo de Vida da Sessão (minutos)** Deslogar automaticamente um Usuário após ele estar inativo pelo número de minutos inserido. Não defina um valor muito alto.
- **Sessões Compartilhadas** Quando habilitado, a sessão de um usuário é compartilhada entre as seções Frontend e Backend do site. Note que mudar este valor invalidará todas as sessões existentes no site. Isto não está disponível quando a opção [Forçar HTTPS](#forcehttps) está definida como *Apenas Administrador*.
- **Acompanhar Metadados da Sessão**
  - *Sim* Metadados adicionais sobre a  sessão do usuário (incluindo seu nome de usuário, ID do usuário e em qual aplicativo ele está logado) serão registrados na tabela de sessão do banco de dados.
  - *Não* Funcionalidades dependentes desses dados ficarão indisponíveis.

### Aba Servidor

![imagem da aba de configuração global do servidor](../../../pt/images/site/global-configuration-server-tab.png)

#### Painel do Servidor

- **Caminho para a Pasta Temporária** Por favor, especifique uma pasta gravável para armazenar arquivos temporários.
- **Comprimir Página com Gzip**
  - *Sim* Comprimir automaticamente as páginas HTML geradas com Gzip, tornando-as menores e aumentando a pontuação de velocidade do seu site.
  - *Não* Se o seu servidor já faz isso por você ou se isso conflita com extensões de terceiros.
- **Relatório de Erros** Este parâmetro define o nível de relatório de erros a ser utilizado pelo PHP no site Joomla.
  - *Padrão do Sistema* Deixa o nível de relatório de erros para o que foi configurado no servidor.
  - *Nenhum* Desativa o relatório de erros.
  - *Simples* Sobrescreve a configuração do servidor para fornecer um nível básico de relatório.
  - *Máximo* Sobrescreve a configuração do servidor para permitir o relatório de todos os erros. Caso o site Joomla falhe a ponto de não ser possível usar a página do administrador para ativar o relatório de erros, você pode habilitar o relatório de erros completo editando o arquivo `configuration.php`. Definir `$error_reporting = 'maximum'` é o equivalente a configurar *Relatório de Erros* para *Máximo*.
- **Forçar HTTPS** Forçar o acesso ao site nas áreas selecionadas a ocorrer apenas com HTTPS (conexões HTTP criptografadas com o prefixo de protocolo https://) e também forçar o uso de cookies seguros. Observe que você deve ter HTTPS habilitado em seu servidor para utilizar esta opção.

#### Painel de Localização

- **Fuso Horário do Website** Escolha uma cidade na lista para configurar a data e hora para exibição.

#### Painel de Serviços Web

- **Habilitar CORS** O Compartilhamento de Recursos com Origens Diferentes ou [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS) permite que scripts executados em um navegador interajam com recursos de uma origem diferente.
  - **Access-Control-Allow-Origin** Especifica a origem permitida para acessar serviços web neste site, enviada de volta em resposta a uma solicitação preflight. Padrão: `*` (=todos).
  - **Access-Control-Allow-Headers** Especifica o(s) cabeçalho(s) enviado(s) de volta em resposta a uma solicitação preflight. Padrão: `Content-Type,X-Joomla-Token`.
  - **Access-Control-Allow-Methods** Especifica o(s) método(s) de serviço web permitido(s) para acessar neste site, enviado(s) de volta em resposta a uma solicitação preflight. Padrão: todos os métodos disponíveis para a rota solicitada.

#### Painel de Proxy

- **Atrás do Balanceador de Carga** Se o seu site estiver atrás de um balanceador de carga ou proxy reverso, habilite esta configuração para que endereços IP e outras configurações dentro do Joomla levem isso em consideração automaticamente.
- **Habilitar Proxy de Saída** Alguns hosts não permitem qualquer acesso à rede do seu site para o mundo exterior por padrão e exigem que você configure manualmente um proxy de saída.
  - **Host do Proxy de Saída** Nome do host (domínio) ou endereço IP.
  - **Porta do Proxy de Saída**
  - **Nome de Usuário do Proxy de Saída** Deixe em branco se seu proxy de saída não exigir autenticação.
  - **Senha do Proxy de Saída**

#### Painel de Banco de Dados

- **Tipo de Banco de Dados** O tipo de banco de dados em uso, selecionado durante o processo de instalação. Não edite este campo a menos que absolutamente necessário (por exemplo, a transferência do banco de dados para um novo provedor de hospedagem).
- **Host** O nome do host do seu banco de dados inserido durante o processo de instalação. Não edite este campo a menos que absolutamente necessário (por exemplo, a transferência do banco de dados para um novo provedor de hospedagem).
- **Nome de Usuário do Banco de Dados** O nome de usuário para acesso ao seu banco de dados inserido durante o processo de instalação. Não edite este campo a menos que absolutamente necessário (por exemplo, a transferência do banco de dados para um novo provedor de hospedagem).
- **Senha do Banco de Dados** A senha a ser usada para acessar o banco de dados. Não edite este campo a menos que absolutamente necessário (por exemplo, a transferência do banco de dados para um novo provedor de hospedagem).
- **Nome do Banco de Dados** O nome do seu banco de dados inserido durante o processo de instalação. Não edite este campo a menos que absolutamente necessário (por exemplo, a transferência do banco de dados para um novo provedor de hospedagem).
- **Prefixo das Tabelas do Banco de Dados** O prefixo usado para suas tabelas de banco de dados, criado durante o processo de instalação. Não edite este campo a menos que absolutamente necessário (por exemplo, a transferência do banco de dados para um novo provedor de hospedagem).
- **Criptografia de Conexão**
  - Padrão (controlado pelo servidor)
  - Autenticação unidirecional
    - **Verificar Certificado do Servidor**
      - **Caminho para o Arquivo CA** Caminho do sistema de arquivos.
  - Autenticação bidirecional
    - **Caminho para o Arquivo de Chave Privada** Localização no sistema de arquivos.
    - **Caminho para o Arquivo de Certificado** Localização no sistema de arquivos.
    - **Verificar Certificado do Servidor**
      - **Caminho para o Arquivo CA** Caminho do sistema de arquivos.
    - **Suíte de Cifra Suportada (opcional)** Nenhuma entrada necessária (somente recomendada para usuários experientes). Para mais detalhes, consulte a documentação do seu banco de dados.

#### Painel de Email

- **Enviar Email**
  - *Sim* Ativar envio de emails.
  - *Não* Desativar envio de emails. Recomenda-se colocar o site offline ao desabilitar a função de email.
- **Desativar Email em Massa**
  - *Sim* Desabilitar a função de Emails em Massa para Usuários.
  - *Não* Tornar a função de Emails em Massa para Usuários ativa.
- **Email de Remetente** O endereço de e-mail que será usado para enviar emails do site.
- **Nome do Remetente** Texto exibido no campo *De:* do cabeçalho ao enviar um email do site. Geralmente o nome do site.
- **Email de Resposta** O endereço de email que será utilizado para receber a resposta do(s) usuário(s) final(is).
- **Nome de Resposta** Texto exibido no campo *Para:* do cabeçalho quando o(s) usuário(s) final(is) responder(em) ao email recebido.
- **Mecanismo de Envio de Email** Selecione qual mecanismo de envio para a entrega de emails do site.

### Aba de Registro

![imagem da aba de configuração global de registro](../../../pt/images/site/global-configuration-logging-tab.png)

#### Painel de Registro

- **Caminho para a Pasta de Log** O Joomla pode opcionalmente manter um arquivo de log de suas próprias operações e das extensões de terceiros. Forneça o caminho absoluto para uma pasta que seja gravável pelo PHP; se estiver faltando ou não for gravável, o Joomla não será carregado. Por motivos de segurança, você não deve usar uma pasta com acesso em todo o sistema, como `/tmp`.
- **Registrar Quase Tudo** Registra tudo, exceto APIs obsoletas.
- **Registrar API Obsoleta** Registra APIs obsoletas.

#### Painel de Registro Personalizado

- **Prioridades de Registro** Pode ser usado para gerenciar o registro personalizado. Selecione os eventos que deseja ver no arquivo de log. O padrão é *Todos*. Os itens podem ser selecionados ou desmarcados clicando na lista suspensa.
- **Categorias de Registro** Uma lista separada por vírgulas de categorias de log para incluir ou excluir. As categorias de log comuns incluem, mas não estão limitadas a: `database`, `databasequery`, `database-error`, `deprecated` e `jerror`. Se estiver vazia, o registro personalizado estará desativado.
- **Modo de Categoria de Registro** Define o modo para a lista de categorias de log acima.

### Aba Filtros de Texto

![imagem da aba de configuração global de filtros de texto](../../../pt/images/site/global-configuration-text-filters-tab.png)

Essas configurações de filtro de texto serão aplicadas a todos os campos do editor de texto submetidos pelos usuários nos grupos selecionados.

Essas opções de filtragem dão mais controle sobre o HTML enviado por seus provedores de conteúdo. Você pode ser tão rigoroso ou liberal quanto necessário para atender às necessidades do seu site. A filtragem é optativa e as configurações padrão oferecem boa proteção contra marcações comumente associadas a ataques de sites.

## Dicas

- A maioria dessas configurações pode ser definida uma vez e depois deixada inalterada.
- Se for necessário fazer modificações importantes, considere retirar o site do ar para testá-lo e garantir que tudo esteja em ordem.
- As configurações são salvas no arquivo `configuration.php` na raiz do site. As permissões deste arquivo são definidas como somente leitura (444) após fazer alterações na página de Configuração Global e devem ser alteradas para permissão de escrita do proprietário (644) antes de editar com um editor de texto.

*Traduzido por openai.com*


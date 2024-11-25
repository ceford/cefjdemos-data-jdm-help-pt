<!-- Filename: Help4.x:Site_System_Information / Display title: Informações do Sistema  -->

## Descrição

A página de *Informações do Sistema* fornece informações sobre o ambiente do servidor host. Existem cinco painéis de abas diferentes: Informações do Sistema, Configurações do PHP, Arquivo de Configuração, Permissões de Pastas e Informações do PHP. Cada painel fornece informações detalhadas sobre aquele aspecto do site. É útil para solucionar problemas de configuração.

- Note que nenhuma dessas configurações pode ser alterada a partir desses painéis.
  Isso deve ser feito em locais diferentes ao longo da instalação do Joomla!,
  dependendo da configuração específica.
- Algumas configurações podem ser alteradas a partir da página de Configuração Global. Outras
  dependem da configuração do servidor host e não podem ser alteradas de dentro
  do Joomla!.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).

## Como acessar

- Selecione **Sistema → Painel de Informações → Informações do Sistema** no menu do Administrador.

## Captura de Tela

![painel inicial](../../../pt/images/site/system-information-tab.png)

## Abas do Formulário

### Aba de Informações do Sistema

- **PHP Construído em** Fornece detalhes do sistema operacional principal em que o servidor web que executa o Joomla está rodando.
- **Tipo de Banco de Dados** Fornece o tipo de banco de dados sendo usado pela instalação do Joomla.
- **Versão do Banco de Dados** Fornece a versão atual do banco de dados MySQL usada pela instalação do Joomla.
- **Colação do Banco de Dados** Como o banco de dados MySQL está estruturado para as informações usadas pelo Joomla!.
- **Colação da Conexão do Banco de Dados** O conjunto de caracteres e colação do banco de dados.
- **Versão do PHP** Fornece a versão atual do script do servidor PHP que está sendo usado para esta instalação do Joomla.
- **Servidor Web** Fornece o tipo e a versão atuais do servidor web em que a instalação do Joomla! está rodando.
- **Interface do Servidor Web para o PHP** O script que permite a interação entre o servidor web (na maioria dos casos, Apache) e a linguagem de script PHP.
- **Versão do Joomla!** Fornece a versão atual do Joomla!. Recomenda-se que esteja sempre atualizada e utilizando a versão estável atual.
- **Agente do Usuário** Resumo do sistema operacional e informações do navegador da máquina local do usuário atual usadas para criar um ID de sessão único para acesso e funcionalidade dentro do site Joomla!.

### Aba de Configurações do PHP

![painel inicial](../../../pt/images/site/php-settings-tab.png)

Esta tela mostra informações sobre Configurações do PHP. Se alguma delas estiver destacada como incorreta, devem ser corrigidas.

- **Modo Seguro** Configuração recomendada: DESLIGADO
- **Open_basedir** Configuração recomendada: Dependente do site
- **Exibir Erros** Configuração recomendada: DESLIGADO
- **Tags Curtas de Abertura** Configuração recomendada: LIGADO
- **Uploads de Arquivos** Configuração recomendada: LIGADO
- **Citações Mágicas** Configuração recomendada: DESLIGADO
- **Registrar Globais** Configuração recomendada: DESLIGADO
- **Buffer de Saída** Configuração recomendada: DESLIGADO
- **Caminho de Salvamento de Sessão** Configuração recomendada: Dependente do site
- **Início Automático de Sessão** Configuração recomendada: 0
- **XML Habilitado** Configuração recomendada: SIM
- **Zlib Habilitado** Configuração recomendada: SIM
- **ZIP Nativo Habilitado** Configuração recomendada: SIM
- **Funções Desabilitadas** Configuração recomendada: Dependente do site
- **String Multibyte (mbstring) Habilitada** Configuração recomendada: SIM
- **Iconv Disponível** Configuração recomendada: SIM
- **Variáveis de Entrada Máxima** Configuração recomendada: 2500

### Aba de Arquivo de Configuração

![painel inicial](../../../pt/images/site/configuration-file-tab.png)

Esta aba mostra o conteúdo do arquivo *configuration.php* atual do Joomla!, que está armazenado no diretório `path-to-joomla-root`. Este arquivo é criado automaticamente quando você instala o Joomla pela primeira vez e onde a maioria das mudanças da seção de Configuração Global do Joomla! é registrada. Observe que nenhuma das configurações pode ser alterada nesta página. Use a Configuração Global para ver mais informações sobre essas configurações e realizar alterações.

### Aba de Permissões de Pastas

![painel inicial](../../../pt/images/site/folder-permissions-tab.png)

Esta aba mostra uma lista dos diretórios aos quais o servidor web deve ter acesso de escrita. Observe que todos os diretórios listados nesta página devem estar como **Graváveis**. Caso contrário, pode ser necessário alterar as permissões para poder instalar e usar o Joomla! com sucesso. O arquivo configuration.php está incluído e exibido como **Não Gravável**.

### Aba de Informações do PHP

![painel inicial](../../../pt/images/site/php-information-tab.png)

Esta aba exibe as configurações de configuração da linguagem de script do servidor PHP que o Joomla! usa, juntamente com todas as informações de sistema associadas que contribuem para a criação do servidor web. Este é o resultado de um script php.info integrado ao Joomla!.

O PHP é instalado e executado no servidor (daí a expressão "lado do servidor" acima), portanto, todas as configurações são feitas no servidor. O visitante do site não precisa ter nada especial rodando em sua máquina local para visualizar ou usar qualquer funcionalidade extra que o PHP oferece ao site.

Todas as configurações que podem ser necessárias são exibidas aqui. Quaisquer mudanças necessárias seriam feitas dentro do *php.ini* e outros arquivos de configuração no servidor web.

Quanto controle um proprietário de site tem sobre essas informações depende de ele ser dono do servidor ou se o host do servidor é flexível em sua abordagem ao cliente.

É uma boa prática conhecer as limitações de uma instalação de servidor específica. A saída dessa tela é usada para encontrar informações detalhadas sobre como o PHP é implementado no servidor.

Para detalhes completos sobre as informações contidas na aba Info PHP, visite: [http://php.net/phpinfo](http://php.net/phpinfo).

## Dicas

- Se você estiver tendo problemas para instalar extensões, carregar arquivos ou
  alterar opções de configuração, verifique a guia de Permissões de Diretório
  para garantir que você tem permissão para escrever arquivos no seu servidor web.
  O *Status* dos diretórios deve ser *Gravável*. Caso contrário, pode não
  ser possível carregar ou editar arquivos nestes diretórios.
- Quando você estiver buscando ajuda para problemas de configuração, por exemplo, em um
  fórum da web do Joomla!, é muito útil postar informações específicas
  sobre a sua instalação do Joomla!. Esta página é uma forma fácil de encontrar
  todas essas informações em um só lugar. Melhor ainda - use o 
  **Assistente de Postagem no Fórum**, documentado no topo das páginas
  do Fórum Joomla, como o fórum de 
  [Questões Gerais](https://forum.joomla.org/viewforum.php?f=834).

*Traduzido por openai.com*


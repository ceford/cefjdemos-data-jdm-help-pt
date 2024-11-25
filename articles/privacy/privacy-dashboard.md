<!-- Filename: Help4.x:Privacy_Dashboard / Display title: Painel de Privacidade -->

## Descrição

A página do *Painel de Privacidade* lista o Tipo de Solicitação de Privacidade do Usuário, Status e Número de solicitações.

### Tutoriais

- [Esboço de Privacidade - Conteúdo e Fluxo de Trabalho](https://docs.joomla.org/Help4.x:Components_Privacy_Outline/en)
- [O Conjunto de Ferramentas de Privacidade](https://docs.joomla.org/J3.x:Privacy/en)
  (Tutorial Detalhado do Joomla 3)
- [Fluxo de Trabalho de Solicitação de Informação](https://docs.joomla.org/J3.x:Information_Request_Workflow_in_Privacy_Component/en)
  (Tutorial Detalhado do Joomla 3)

## Como acessar

- Selecione **Usuários → Ícone do Painel de Privacidade** no menu do Administrador.

## Captura de Tela

![dashboard de privacidade](../../../pt/images/privacy/privacy-dashboard.png)

## Painéis do Dashboard

### Status de Privacidade

- **Política de Privacidade Publicada** Indica se uma Política de Privacidade está disponível. Navegue até *Plugins → Sistema - Consentimento de Privacidade* e selecione seu Artigo de Privacidade. Uma vez publicado, você pode editar seu artigo de Política de Privacidade a partir desta página.
- **Item de Menu de Formulário de Solicitação Publicado** Indica se o Item de Menu (que permite aos usuários enviar solicitações) está publicado ou não. Para criá-lo, navegue até seu Menu → Adicionar Novo Item de Menu → Tipo de Item de Menu: Criar Solicitação. Uma vez publicado, você pode editar seu item de menu a partir desta tela.
- **Solicitações Urgentes Pendentes** Número de solicitações urgentes que são mais antigas que o número de dias definido nas Opções do Componente (de 10 a 29 dias).
- **Envio de Email Ativado**
- **Criptografia de conexão com o banco de dados**

### Solicitações de Privacidade

- **Tipo de Solicitação** Exibe os dois tipos diferentes de solicitação
  - *Exportar* quando um usuário enviou uma solicitação para exportação de seus dados
  - *Remover* quando um usuário enviou uma solicitação para ser removido.
- **Status** Exibe o status da solicitação
  - *Inválido* um Superusuário invalidou a solicitação
  - *Pendente* quando um usuário enviou uma solicitação, mas ainda não a confirmou. Os usuários têm 2 formas de confirmar: visitando a URL mencionada no e-mail enviado ao usuário ou copiando o token do e-mail e colando-o no formulário na URL fornecida. O token é válido por 24 horas.
  - *Confirmado* o usuário confirmou a solicitação.
  - *Concluído* um Superusuário completou a solicitação
- **\# de solicitações** Exibe o número de solicitações para cada tipo. Este bloco também exibe o número total de solicitações e o número de solicitações ativas.

## Dicas

- Selecione um Tipo de Solicitação para ver a lista de solicitações desse tipo.

*Traduzido por openai.com*


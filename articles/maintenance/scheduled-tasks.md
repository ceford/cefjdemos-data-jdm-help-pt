<!-- Filename: Help5.x:Scheduled_Tasks / Display title: Tarefas agendadas -->

## Descrição

Tarefas Agendadas são usadas para executar tarefas de manutenção de rotina do site como uma alternativa aos cron jobs do servidor. As tarefas são definidas em plugins no grupo de tarefas. Vários plugins de tarefas são fornecidos e podem ser usados como exemplos para criar outras tarefas especializadas.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de Lista](jdocmanual?article=help/common-elements/list-filters).
* [Cabeçalhos de Colunas de Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Paginação da Lista](jdocmanual?article=help/common-elements/list-pagination).

## Como Acessar

Começando pelo menu do Administrador:

- Selecione **Sistema → Painel de gerenciamento → Tarefas programadas**

A lista inicial de Tarefas Agendadas tem três itens.

## Captura de Tela

![scheduled tasks list](../../../pt/images/maintenance/scheduled-tasks-list.png)

## Cabeçalhos de Coluna

Colunas exclusivas para tarefas agendadas:

- **Tipo de Tarefa** As tarefas são criadas a partir de uma lista disponível de tipos.
- **Data da Última Execução** A data e hora da última execução da tarefa.
- **Data da Próxima Execução** A data e hora da próxima execução da tarefa.
- **Testar Tarefa** Um botão para executar a tarefa manualmente.
- **Prioridade da Tarefa** A prioridade pode ser Baixa, Normal ou Alta. Tarefas de maior prioridade podem potencialmente bloquear tarefas de menor prioridade.

## Histórico de Execução

Selecione o botão na Barra de Ferramentas para ver uma lista de execuções de tarefas individuais.

![task execution history list](../../../pt/images/maintenance/scheduled-tasks-logs.png)

## Tarefas Disponíveis

A captura de tela a seguir mostra uma lista de tarefas disponíveis. Algumas são demonstrações, outras são úteis.

![Scheduled Tasks Available](../../../pt/images/maintenance/scheduled-tasks-types.png)

Cada tarefa possui seus próprios parâmetros relacionados à tarefa que devem ser autoexplicativos. Por exemplo, a tarefa **Site Offline** só faz sentido se a **Editar Tarefa → Campos Básicos → Regra de Execução** estiver configurada para **Execução Manual**.

*Traduzido por openai.com*

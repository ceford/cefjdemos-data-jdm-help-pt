<!-- Filename: Help4.x:Components_Version_History / Display title: Editar Histórico de Versões  -->

## Descrição

Um popup de Histórico de Versão mostra versões anteriores do item que está sendo editado. Ele está disponível para Artigos, Banners, Clientes, Contatos, Fontes de Notícias, Notas do Usuário e todas as Categorias.

Cada vez que um item é salvo, uma nova versão é criada automaticamente. O número de versões a manter para cada item é definido nas Opções do componente. Uma ou mais versões podem ser marcadas para serem mantidas para sempre. Tais versões não serão excluídas automaticamente, mesmo que o número máximo de versões definido nas opções seja excedido.

**Nota:** Se o versionamento for usado, os campos personalizados não são armazenados em diferentes versões.

## Como Aceder

Selecione o botão **Versões** na Barra de Ferramentas de uma página de edição de item.

## Captura de Tela

![Popup do histórico de versões](../../../pt/images/common-elements/articles-edit-versions.png)

## Cabeçalhos de Colunas

- **Caixa de Seleção** Marque esta caixa para selecionar um ou mais itens. Para selecionar todos os itens, marque a caixa no cabeçalho da coluna. Após marcar as caixas, selecione um botão da barra de ferramentas para executar uma ação nos itens selecionados.
- **Data** A data e hora em que a versão foi salva. Selecionar este link abre a Pré-visualização daquela versão em uma janela pop-up. Note que uma das datas será seguida por um símbolo de estrela. Isto indica que esta é a versão atualmente salva e em edição.
- **Nota da Versão** Uma Nota da Versão pode ser utilizada para ajudar a identificar a natureza das mudanças de uma versão para a próxima. Uma Nota da Versão inserida antes de salvar um item será exibida nesta coluna.
- **Manter Para Sempre** Esta coluna mostra se a versão foi marcada para Manter Para Sempre. Normalmente, cada versão será retida de acordo com as configurações na página de opções do componente. As configurações padrão são para manter no máximo 10 versões anteriores de um item. Quando um item é salvo que já possui 10 versões salvas, a versão mais antiga é deletada. Se uma versão estiver marcada como Manter Para Sempre, ela não será contada como uma das versões salvas e não será deletada quando o número máximo for alcançado.
  - Para alternar o estado de Manter Para Sempre ligando ou desligando, selecione um botão *Não* ou *Sim*, ou marque a caixa de seleção da versão e, em seguida, selecione o botão Manter Ligado/Desligado na barra de ferramentas.
- **Autor** O usuário que salvou esta versão.
- **Contagem de Caracteres** O total de caracteres salvos nesta versão. Note que isto inclui os nomes das colunas do banco de dados, bem como os caracteres reais digitados.

## Barra de Ferramentas

- **Restaurar** A versão atual do item é marcada com uma estrela à direita da Data. Para restaurar uma das outras versões salvas, marque a caixa de seleção da versão desejada e selecione o botão Restaurar. A versão atual do item será substituída pela versão selecionada, e a tela de edição será recarregada com a versão restaurada carregada no editor.
- **Pré-visualizar** Para pré-visualizar uma versão, selecione a coluna Data para a versão desejada ou selecione a caixa de seleção e depois o botão Pré-visualizar. Uma janela pop-up separada será carregada mostrando a versão selecionada do item.
- **Comparar** Para comparar duas versões e ver o que foi alterado, selecione as caixas de seleção para cada uma das versões e depois o botão Comparar. Uma nova janela do navegador será aberta mostrando uma lista de campos alterados e as alterações feitas nesses campos.
  - A primeira coluna é o nome do campo, a segunda é a versão mais antiga, a terceira é a versão mais recente, e a última coluna destaca as diferenças entre as duas versões.
- **Manter Ligado/Desligado** Este botão alterna entre ligar ou desligar o recurso Manter Para Sempre para uma versão. Normalmente, a versão mais antiga de um item será excluída automaticamente quando o número máximo de versões (definido nas Opções do componente) for excedido. Se você definir a propriedade Manter Para Sempre para uma versão, ela nunca será excluída automaticamente.
- **Excluir** Este botão permite a exclusão manual de uma ou mais versões. Marque a caixa de seleção das versões a serem excluídas e depois selecione o botão Excluir. Observe que isso *não* exclui o item que está sendo editado. Ele apenas exclui o histórico de versões do item.


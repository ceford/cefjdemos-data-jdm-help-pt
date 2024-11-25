<!-- Filename: Help4.x:Templates:_Customise / Display title: Modelos: Personalizar  -->

## Descrição

A página *Modelos: Personalizar* é usada para editar o código-fonte de um modelo. Você pode criar substituições para arquivos PHP e criar arquivos user.css e user.js para adicionar às versões do sistema. Você pode criar modelos filho para permitir a edição dos arquivos principais do modelo de substituição.

## Como Acessar

- Selecione **Sistema → Painel de Modelos → Modelos de Site** no menu do Administrador. Ou...
- Selecione **Sistema → Painel de Modelos → Modelos de Administrador** no menu do Administrador. Então...
  - Selecione um nome de modelo na coluna **Modelo**.

## Captura de Tela

As telas de Administrador e de Modelos de Site usam o mesmo layout. A tela de Modelo de Site está ilustrada aqui.

![templates customize cassiopeia editor tab](../../../pt/images/templates/templates-customise-cassiopeia-editor-tab.png)

## Campos de Formulário

### Aba Editor

- Selecione um arquivo para editar. A área de edição mostra o texto com destaque de sintaxe para a maioria dos tipos de arquivo.

### Aba Criar Substituições

![modelos personalizar cassiopeia criar aba de substituições](../../../pt/images/templates/templates-customise-cassiopeia-create-overrides-tab.png)

- Selecione um item para substituir. Itens marcados com um ícone de arquivo sólido se abrem para revelar uma lista de itens. Itens marcados com ícones de página aberta e preenchida sobrepostos criam uma substituição imediatamente sem solicitar confirmação. A substituição é colocada no local apropriado. Há uma mensagem de confirmação, por exemplo:
  *Substituição criada em /templates/cassiopeia/html/mod_whosonline*.

### Aba de Arquivos Atualizados

![modelos personalizar cassiopeia aba atualizada](../../../pt/images/templates/templates-customise-cassiopeia-updated-files-tab.png)

Se não houver atualizações para o modelo desde que as substituições foram criadas, esta aba conterá uma mensagem simples:

<div class="alert alert-success">
Arquivos substituídos estão atualizados. Nada foi alterado na última atualização da extensão ou do Joomla.
</div>

Se houver atualizações, uma tabela mostrará uma lista de substituições que precisam ser revisadas.

### Aba Descrição do Modelo

![modelos personalizar cassiopeia aba de descrição do modelo](../../../pt/images/templates/templates-customise-cassiopeia-template-description-tab.png)

- **Miniatura e Descrição** Informações sobre este modelo.

## Barra de Ferramentas

Observe que os botões da Barra de Ferramentas mudam quando um arquivo é selecionado para edição.

### Nenhum arquivo selecionado

No topo da página, você verá a barra de ferramentas mostrada na captura de tela acima. As funções são:

- **Criar Modelo Filho** Selecione para criar um novo modelo filho completo. Você será solicitado a dar um novo nome para o modelo filho. Há também a opção de Fechar sem criar um novo modelo filho. Para remover o novo modelo filho: selecione o botão **Fechar**, selecione o botão Estilos na Barra de Ferramentas da lista de Modelos, marque a caixa de seleção do template para o novo modelo filho e selecione Excluir na barra de ferramentas.
- **Visualizar Modelo** Selecione para abrir a visualização padrão do site usando este modelo.
- **Gerenciar Pastas** Selecione para criar uma nova pasta dentro da hierarquia do modelo. Uma janela popup aparece. **Importante:** selecione a pasta na qual a nova pasta deve aparecer antes de criar a nova pasta.
- **Novo Arquivo** Selecione para criar um novo arquivo ou para fazer upload de um arquivo do seu computador para a hierarquia do template Joomla! Uma janela popup aparece. **Importante** Selecione a pasta na qual o novo arquivo deve aparecer antes de criar o novo arquivo.
- **Verificar Sobrescritas** Ativado quando uma Sobrescrita é selecionada na aba *Sobrescritas*. As opções são:
  - Marcar Verificado
  - Marcar Não Verificado
  - Remover Registro
- **Fechar** Fecha a tela atual e retorna à tela anterior sem salvar quaisquer modificações que você possa ter feito. Esse ícone da barra de ferramentas não é mostrado se você estiver criando um novo item.
- **Ajuda** Abre esta tela de ajuda.

### Arquivo selecionado

- **Salvar** Salva o item e permanece na tela atual.
- **Salvar & Fechar** Salva o item e fecha a tela atual.
- **Renomear Arquivo** Selecione um arquivo para editar. Selecione o botão Renomear para solicitar um novo nome.
- **Excluir Arquivo** Você será solicitado a Confirmar ou Cancelar.
- **Verificar Sobrescritas** Ativado quando uma Sobrescrita é selecionada na aba *Sobrescritas*.
- **Fechar Arquivo** Fecha o arquivo aberto e retorna para a Aba do Editor.
- **Ajuda** Abre esta tela de ajuda.

## Dicas

- Antes de editar o arquivo HTML e CSS do modelo, é uma boa ideia fazer um backup do arquivo que você está editando. Além disso, você pode editar esses arquivos fora do Joomla! usando o editor HTML ou CSS de sua escolha.

*Traduzido por openai.com*


<!-- Filename: Help4.x:Templates:_Customise_Source / Display title: Modelos: Personalizar Fonte -->

<div class="alert alert-warning">
Esta página aparece no índice de páginas de Ajuda, mas não é utilizada através de um botão de Ajuda.
Este é um bug que provavelmente será corrigido.
</div>

## Descrição

A página *Modelos: Personalizar Fonte* é onde o código-fonte dos arquivos de modelo é editado. Ela fornece uma interface de texto simples para editar os arquivos de modelo. A sintaxe de programação HTML e PHP é destacada para facilitar a leitura dos arquivos de código-fonte. Na barra de título, a palavra *Fonte* aparece como o nome do modelo, por exemplo *(Cassiopeia)*.

## Como Acessar

- Selecione **Sistema → Painel de Modelos → Modelos do Site** no menu do Administrador. Ou...
- Selecione **Sistema → Painel de Modelos → Modelos do Administrador** no menu do Administrador. Então...
  - Selecione um nome de modelo na coluna **Modelos**. Depois...
    - Selecione um arquivo para editar na guia Editor.

## Captura de Tela

![Modelos personalizados aba do editor cassiopeia](../../../pt/images/templates/templates-customise-cassiopeia-edit-component-editor-tab.png)

## Campos do Formulário

### Aba Editor

- Selecione um arquivo para editar. A área de edição mostra texto com realce de sintaxe para a maioria dos tipos de arquivo.

### Aba Criar Substituições

- Selecione um item para substituir. Se uma pasta for selecionada, ela será expandida para exibir uma lista de arquivos. Se um arquivo for selecionado, ele é imediatamente copiado para a pasta html sem solicitação de confirmação. A substituição é colocada na localização apropriada. Há uma mensagem de confirmação, por exemplo: 
  *Substituição criada em /templates/cassiopeia/html/mod_whosonline*.

### Aba Arquivos Atualizados

Se não houver atualizações no template desde que as substituições foram criadas, esta aba conterá uma mensagem simples:

- **Aviso** Os arquivos substituídos estão atualizados. Nada foi alterado na última atualização da extensão ou do Joomla.

Se houver atualizações, uma tabela mostrará uma lista de substituições que precisam ser revisadas.

### Aba Descrição do Template

- **Miniatura e Descrição** Informações sobre este template.

## Barra de Ferramentas

Os ícones da Barra de Ferramentas mudam conforme a ação sendo realizada. Você pode ver:

- **Salvar** Salva o item e permanece na tela atual.
- **Salvar e Fechar** Salva o item e fecha a tela atual.
- **Copiar Modelo** Copia o modelo atual. Uma caixa de diálogo solicita
  um novo nome.
- **Visualizar Modelo** Selecione para abrir o site em uma nova aba do navegador.
- **Gerenciar Pastas** Permite a criação e exclusão de pastas de modelos
  usando uma caixa de diálogo.
- **Novo Arquivo** Permite o upload de um arquivo do seu computador para a
  hierarquia de arquivos do modelo usando uma caixa de diálogo.
- **Renomear Arquivo** Selecione um arquivo para editar. Selecione o botão Renomear para
  solicitar um novo nome.
- **Excluir Arquivo** Você será solicitado a Confirmar ou Cancelar.
- **Fechar Arquivo** Fecha o arquivo aberto e retorna à Aba do Editor.
- **Ajuda** Abre esta tela de ajuda.

## Dicas

- Importante: Não exclua os arquivos de modelo padrão usando FTP, pois isso gera um erro tanto no frontend quanto no backend.
- Antes de editar o arquivo HTML e CSS do modelo, é uma boa ideia fazer um backup do arquivo que você está editando. Além disso, você pode editar esses arquivos fora do Joomla! usando o editor HTML ou CSS de sua preferência.

*Traduzido por openai.com*


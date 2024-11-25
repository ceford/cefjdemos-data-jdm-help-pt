<!-- Filename: Help4.x:Media:_Options / Display title: Mídia: Opções  -->

## Descrição

A página *Mídia: Opções* é usada para definir os parâmetros globais de mídia.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba de Permissões](jdocmanual?article=help/common-elements/edit-permissions).

## Como Aceder

- Selecione **Conteúdo → Mídia** no menu do Administrador.
- Selecione o botão **Opções** na Barra de Ferramentas.

## Captura de Tela

![Opções de Mídia](../../../pt/images/media/media-options.png)

## Campos de Formulário

### Mídia

- **Tamanho Máximo (em MB)** Use zero para sem limite. Nota: O servidor tem um limite máximo.
- **Caminho para a Pasta de Arquivos** Insira o caminho para a pasta de arquivos relativo à raiz do seu espaço web. Não inicie o caminho com uma barra. Alterar para um caminho diferente do padrão *images* pode quebrar seus links.
- **Caminho para a Pasta de Imagens** Insira o caminho para a pasta de imagens relativa à raiz do seu espaço web. Não inicie o caminho com uma barra.
- **Restringir Uploads** Restrinja uploads para usuários abaixo de gerente a apenas imagens se `Fileinfo` ou `MIME Magic` não estiverem instalados.
  - **Extensões Permitidas** Restrinja uploads para usuários abaixo de gerente a arquivos na lista.
  - **Verificar Tipos MIME** Use `Fileinfo` ou `MIME Magic` para tentar verificar os arquivos. Experimente desativar isso se você receber erros de tipo MIME inválido.
- **Extensões de Imagem Legais (Tipos de Arquivo)** Extensões de imagem (tipos de arquivo) que você tem permissão para fazer upload (separadas por vírgula). Estas são usadas para verificar cabeçalhos de imagem válidos e para selecionar imagens.
- **Extensões de Áudio Legais (Tipos de Arquivo)** Extensões de áudio (tipos de arquivo) que você tem permissão para fazer upload (separadas por vírgula). Estas são usadas para verificar cabeçalhos de áudio válidos e para selecionar arquivos de áudio.
- **Extensões de Vídeo Legais (Tipos de Arquivo)** Extensões de vídeo (tipos de arquivo) que você tem permissão para fazer upload (separadas por vírgula). Estas são usadas para verificar cabeçalhos de vídeo válidos e para selecionar vídeos.
- **Extensões de Documento Legais (Tipos de Arquivo)** Extensões de documento (tipos de arquivo) que você tem permissão para fazer upload (separadas por vírgula). Estas são usadas para verificar cabeçalhos de documento válidos e para selecionar documentos.
- **Extensões Ignoradas** Extensões de arquivo ignoradas para verificação de tipo MIME e uploads restritos.
- **Tipos MIME Legais** Uma lista separada por vírgulas dos tipos MIME legais para upload.

## Dicas

- Se você é um usuário iniciante, pode simplesmente manter os valores padrão aqui até aprender mais sobre o uso de opções globais.
- Se você é um usuário avançado, pode economizar tempo criando bons valores padrão aqui.

*Traduzido por openai.com*  


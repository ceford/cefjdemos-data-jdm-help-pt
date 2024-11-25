<!-- Filename: Help4.x:Banners:_New_or_Edit_Client / Display title: Banners: Editar Cliente -->

## Descrição

O formulário de Edição de Cliente de Banners é usado para inserir ou alterar dados do Cliente de Banner. Pelo menos um Cliente de Banner é necessário antes que um Banner possa ser criado.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [O Pop-up de Histórico de Versões](jdocmanual?article=help/common-elements/edit-version-history).

## Como Acessar

- Selecione **Componentes → Banners → Clientes** no menu do Administrador.
  - Para criar um novo Cliente, selecione o botão **Novo** na Barra de Ferramentas.
  - Para editar um Cliente existente, selecione o **nome** na coluna Cliente.

## Captura de Tela

![Banners editar cliente](../../../pt/images/banners/banners-edit-client-details-tab.png)

## Campos do Formulário

- **Nome** O nome deste cliente.

### Aba Detalhes

- **Nome do Contato** O nome da pessoa de contato para este cliente.
- **E-mail do Contato** O endereço de e-mail do cliente do banner.
- **Tipo de Compra** O tipo de compra do banner. Isto é usado para
  indicar como o cliente do banner comprou o tempo de exibição para o
  banner - mensal, anual, etc.
- **Rastrear Impressões** Indicar se deseja ou não rastrear o número de vezes que o
  banner é exibido para os visitantes do site.
- **Rastrear Cliques** Indicar se deseja ou não rastrear o número de vezes que o
  banner é clicado pelos visitantes do site.
- **Informações Adicionais** Insira qualquer informação extra que você deseja
  salvar para este cliente.
- **Status** Status de publicação do item. Os valores possíveis são:
  - *Publicado*: O item está publicado. Este é o único estado que permitirá
    que usuários regulares do site vejam este item.
  - *Não publicado*: O item não está publicado.
  - *Arquivado*: O item foi arquivado.
  - *Excluído*: O item foi enviado para a Lixeira.
- **Nota de Versão** Campo opcional para identificar esta versão do item
  na janela de Histórico de Versões do item.

### Aba de Metadados

![Aba de metadados de edição de cliente de banners](../../../pt/images/banners/banners-edit-client-metadata-tab.png)

- **Palavras-chave** Entrada opcional para palavras-chave. Devem ser inseridas separadas
  por vírgulas (por exemplo, "gatos, cães, animais de estimação") e podem ser inseridas em
  letras maiúsculas ou minúsculas. (Por exemplo, "GATOS" corresponderá a "gatos" ou
  "Gatos"). Palavras-chave podem ser usadas de várias formas:
  1.  Para ajudar os mecanismos de busca e outros sistemas a classificar o conteúdo do
      Artigo.
  2.  Em combinação com tags de Banner, para exibir Banners específicos com base no
      conteúdo do Artigo. Por exemplo, digamos que você tenha um Banner com um anúncio
      para produtos para cães e outro Banner para produtos para gatos. Você
      pode fazer seu Banner de cães ser exibido quando um Usuário estiver visualizando um
      Artigo relacionado a cães e seu Banner de gatos ser exibido para um Artigo relacionado
      a gatos. Para isso, você faria:
      - Adicionar as palavras-chave "cão" e "gato" aos Artigos apropriados.
      - Adicionar as tags "cão" e "gato" aos Banners apropriados em
        Banners: Editar.
      - Definir o parâmetro do módulo de Banner 'Pesquisar por Tags' como "Sim" na
        lista de Módulos do Site: Banners.
  3.  Apenas para artigos, em combinação com o módulo Artigos - Relacionados,
      para exibir Artigos que compartilhem ao menos uma palavra-chave em comum. Por
      exemplo, se o Artigo atual exibido tiver as palavras-chave "gatos,
      cães, macacos", quaisquer outros Artigos com ao menos uma dessas
      palavras-chave aparecerão no módulo 'Artigos - Relacionados'.
- **Usar Prefixo Próprio** Se deve ou não usar o prefixo do banner ou do
  cliente. Selecione *Não* se quiser usar o prefixo do cliente do banner.
- **Prefixo de Palavra-chave Meta** Ao localizar palavras-chave meta, busque
  apenas palavras-chave meta com estes prefixos opcionais. Isso melhora o desempenho.

*Traduzido por openai.com*


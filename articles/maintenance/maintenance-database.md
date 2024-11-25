<!-- Filename: Help4.x:Information:_Database / Display title: Manutenção: Banco de Dados   -->

## Descrição

Esta página verifica se a estrutura da tabela do banco de dados está atualizada e tenta corrigir quaisquer problemas encontrados. Em uma atualização normal da versão do Joomla, as alterações na estrutura da tabela do banco de dados (também chamada de `schema`) são executadas automaticamente para manter a versão do banco de dados sincronizada com a versão do Joomla. Se uma atualização for realizada manualmente, ou se alguma parte de uma atualização automática falhar, o esquema do banco de dados pode não ser atualizado para corresponder à versão dos arquivos do programa Joomla. Nesse caso, a página listará quaisquer problemas de banco de dados descobertos. Muitas vezes, é possível corrigir quaisquer problemas selecionando o botão *Atualizar Estrutura*.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de Lista](jdocmanual?article=help/common-elements/list-filters).
* [Cabeçalhos de Colunas de Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Paginação de Lista](jdocmanual?article=help/common-elements/list-pagination).

## Como Acessar

- Selecione **Sistema → Painel de Manutenção → Banco de Dados** no menu do Administrador.

## Captura de Tela

![Banco de dados de manutenção](../../../pt/images/maintenance/maintenance-database.png)

## Cabeçalhos de Coluna

- **Problemas** Quaisquer problemas serão mencionados aqui. Um Tooltip ao passar o mouse fornece mais informações.
- **Versão do Banco de Dados** O número da versão do Banco de Dados.
- **Versão do Manifesto** O número da versão do Joomla ou Extensão.
- **Pasta** Se a extensão for um plug-in, o subdiretório do diretório de plugins da instalação do Joomla! onde a extensão está localizada.

## Dicas

- Se ocorrerem problemas durante uma atualização, use esta verificação de Banco de Dados para ver se o banco de dados foi atualizado corretamente.
- Recomenda-se fortemente que o componente de Atualização do Joomla seja usado para atualizar o site, para que as alterações no banco de dados sejam executadas automaticamente.

*Traduzido por openai.com*


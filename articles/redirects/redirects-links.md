<!-- Filename: Help4.x:Redirects:_Links / Display title: Redirecionamentos: Links -->

## Descrição

A página *Redirecionamentos: Links* mostra uma lista dos redirecionamentos atuais do site.

O componente de redirecionamento é usado para redirecionar URLs de páginas da web que não existem mais no seu site para páginas da web que estão funcionando. A URL da qual você deseja redirecionar não deve estar funcionando e efetivamente carregando uma página da web. Pode ser a URL de uma página da web que você desativou.

A *URL Expirada* que você especifica quando cria o redirecionamento deve ser a URL completa, tal como você a digitasse no seu navegador. O componente apenas exibirá a última parte do URL de origem na lista de redirecionamento.

A *Nova URL* que você especifica ao criar um redirecionamento também deve ser a URL completa. Você deve ter a opção *Usar Reescrita de URL* habilitada nas opções de *Configuração Global* da sua instalação Joomla! para que os redirecionamentos que você criar funcionem.

### Elementos Comuns

Alguns elementos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de Lista](jdocmanual?article=help/common-elements/list-filters).
* [Cabeçalhos de Colunas de Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Paginação de Lista](jdocmanual?article=help/common-elements/list-pagination).

## Como acessar

- Selecione **Sistema → Painel de gerenciamento → Redirecionamentos** no menu do Administrador.

## Captura de tela

![Redireciona links](../../../pt/images/redirects/redirects-links.png)

## Cabeçalhos de Colunas

- **URL Expirada** A URL que está sendo redirecionada no seu site. Apenas a parte da página web da URL é exibida nesta listagem.
- **Nova URL** A URL de destino para o redirecionamento.
- **Página de Referência** A página web de referência para o redirecionamento.
- **Data de Criação** Data em que o item (Artigo, Categoria, etc.) foi criado.
- **Acessos 404** Número de acessos 404 que ocorreram nesta URL.
- **Código de Status** O código de status da página.

## Dicas

- Para que seus redirecionamentos funcionem, você deve habilitar a opção **Usar Reescrita de URL** nas opções de **Configuração Global** da sua instalação do Joomla!. Observe também que apenas habilitar a opção *Usar Reescrita de URL* não é suficiente. Você deve dar o passo adicional de renomear o arquivo `htaccess.txt` no diretório do site onde você instalou o Joomla! para `.htaccess` ou para qualquer nome de arquivo que seu servidor web Apache exigir para diretivas de configuração adicionais. No arquivo de configuração do Apache, essa configuração é chamada de `AccessFileName` e, por padrão, está definida como `.htaccess`.

*Traduzido por openai.com*


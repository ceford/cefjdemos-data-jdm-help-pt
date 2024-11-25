<!-- Filename: Help6.x:Modules / Display title: Módulos  -->

## Descrição

Os módulos são extensões leves e flexíveis usadas para renderizar trechos de informações em caixas dispostas ao redor de um componente em uma página. Um exemplo bem conhecido é o módulo de *Login*. Os módulos são atribuídos por item de menu, então você pode decidir mostrar ou ocultar um módulo dependendo de qual página o usuário está visualizando no momento.

Alguns módulos estão vinculados a componentes. Por exemplo, o módulo *Últimas Notícias* está ligado ao componente de conteúdo para exibir links para os artigos mais recentes. Os módulos não precisam estar vinculados a componentes. Eles nem precisam estar vinculados a nada e podem ser apenas HTML ou texto estático.

Pode haver várias instâncias do mesmo módulo. Por exemplo, você pode usar uma instância do módulo *Imagem Aleatória* para algumas páginas e outra instância para outras páginas, cada uma usando uma pasta de imagens diferente para selecionar as imagens.

As listas de *Módulos (Site)* e *Módulos (Administrador)* mostram os módulos atualmente instalados em cada interface e fornecem acesso para adicionar novos módulos ou editar módulos existentes.

### Elementos Comuns

Alguns elementos desta página estão cobertos em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [Filtros de Lista](jdocmanual?article=help/common-elements/list-filters).
* [Cabeçalhos de Colunas de Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordenação de Itens da Lista](jdocmanual?article=help/common-elements/list-ordering).
* [Paginação de Lista](jdocmanual?article=help/common-elements/list-pagination).
* [Processo em Lote de Lista](jdocmanual?article=help/common-elements/list-batch-process).

Para ver listas de módulos instalados e módulos disponíveis, selecione uma das seguintes opções:

* [Módulos do site](jdocmanual?article=help/modules-site/site-modules-site)
* [Módulos do administrador](jdocmanual?article=help/modules-admin/admin-modules-administrator)

## Como acessar

- Selecione **Conteúdo → Módulos do Site** no menu do Administrador. Ou...
- Selecione **Conteúdo → Módulos do Administrador** no menu do Administrador.

## Filtros de Lista

* **Site ou Administrador** Seleciona módulos de Site ou Administrador.

## Cabeçalhos de Coluna

Esta é uma lista curta dos cabeçalhos exclusivos para listas de módulos.

- **Posição** A posição na página onde este módulo é exibido.
- **Tipo** O nome do sistema do Módulo.
- **Páginas** Os Itens de Menu onde este Módulo será exibido. Este item não está presente nas listas de módulos do Administrador.
  - *Todas* Exibido em todas as páginas
  - *Nenhuma* Não exibido em nenhuma página
  - *Selecionadas* Exibido apenas nas páginas selecionadas
  - *Todas exceto selecionadas* Exibido em todas as páginas, exceto aquelas selecionadas
- **Acesso** O nível de Acesso de visualização para este módulo.
- **Idioma** Idioma dos módulos, o padrão é *Todos*. Este item não está presente nas listas de módulos do Administrador.

### Posições de Módulo

Para visualizar posições de módulos em um site ao vivo, vá para **Sistema → Modelos** e selecione o botão **Opções** na Barra de Ferramentas. Defina *Pré-visualizar Posições de Módulo* como ativado e *Salvar*. Esta configuração é válida tanto para modelos de site quanto de administrador. Em seguida, adicione `?tp=1` ao final de uma URL que ainda não contém uma string de consulta ou `&tp=1` ao final de uma URL que já contém uma string de consulta. A página exibirá todas as posições de módulo disponíveis, até mesmo aquelas às quais nenhum módulo foi atribuído. As posições também são mostradas no formulário de edição do Módulo.

## Dicas

- Sites Joomla requerem pelo menos um módulo de Menu.
- Outros tipos de módulo (por exemplo, banners) são opcionais.
- Alguns módulos estão vinculados a componentes. Por exemplo, cada módulo de menu
  está relacionado a um menu.
- Outros módulos (por exemplo, breadcrumbs) não dependem de nenhum outro conteúdo.
- Múltiplas ocorrências de um módulo são permitidas e comuns.

*Traduzido por openai.com*


<!-- Filename: Help5.x:Site_Modules:_Articles / Display title: Módulos: Artigos -->

## Descrição

O módulo **Artigos** exibe uma lista de artigos. Ele é destinado a substituir cinco outros módulos de artigos:

* [Módulos: Artigos - Arquivados](jdocmanual?article=help/modules/site-modules-articles-archived).
* [Módulos: Artigos - Categoria](jdocmanual?article=help/modules/site-modules-articles-category).
* [Módulos: Artigos - Últimos](jdocmanual?article=help/modules/site-modules-articles-latest).
* [Módulos: Artigos - Mais Lidos](jdocmanual?article=help/modules/site-modules-articles-most-read).
* [Módulos: Artigos - Flash de Notícias](jdocmanual?article=help/modules/site-modules-articles-newsflash).

As opções do módulo **Artigos** são configuradas principalmente através de quatro abas:

- A *Aba de Opções de Filtragem* é usada para especificar quais artigos são exibidos.
- A *Aba de Opções de Exibição* especifica como os artigos são exibidos no módulo e quais detalhes estão incluídos.
- A *Aba de Opções de Ordenação* é usada para configurar a precedência dos artigos.
- A *Aba de Opções de Agrupamento* é usada para configurar a precedência dos artigos.

**Importante:** O módulo só aparece quando há um ou mais artigos correspondentes para exibir. Se estiver vazio, o módulo não aparecerá.

### Elementos Comuns

Alguns elementos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [Os Módulos: Aba Módulos](jdocmanual?article=help/modules/modules-module-tab).
* [Os Módulos: Aba de Atribuição de Menu](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [Os Módulos: Aba Avançada](jdocmanual?article=help/modules/modules-advanced-tab).
* [A Aba de Permissões](jdocmanual?article=help/common-elements/edit-permissions).

## Como Acessar

- Selecione **Conteúdo → Módulos do Site** ou **Sistema → Painel de Gestão → Módulos do Site**
  no menu do Administrador ou **Painel do Site → Módulos** no Painel Inicial.
  Então...
  - Para criar um novo módulo: selecione o botão **Novo** na Barra de Ferramentas na
    lista de *Módulos*. Depois...
    - Selecione o módulo **Artigos**.
  - Para editar um módulo existente: encontre o módulo na lista de módulos instalados
    e selecione o link no título na coluna **Título**.

## Captura de Tela

![Módulo de artigos na aba do módulo](../../../en/images/modules-site/modules-articles-module-tab.png)

## Campos do Formulário

### Aba de Módulo

#### Painel Esquerdo

- **Modo**
  - *Modo Normal* configura o módulo para exibir uma lista estática de Artigos.
  - *Modo Dinâmico* configura o módulo para detectar se está usando uma visualização de Categoria e exibirá a lista de artigos dentro dessa Categoria de acordo. Quando o Modo Dinâmico é selecionado, é melhor deixar o módulo configurado para exibir em todas as páginas, pois ele decidirá dinamicamente se deve ou não exibir algo.
- **Artigos para Exibir** O número máximo de artigos a serem exibidos.
- **Tipo de Filtragem de Categoria** Especifica como os artigos são filtrados com base nas categorias fornecidas no campo *Categoria*.
  - *Inclusivo* Apenas artigos com as categorias especificadas são mostrados.
  - *Exclusivo* Artigos com as categorias especificadas são excluídos.
- **Categoria** Mostra ou exclui artigos com as categorias selecionadas. Isso funciona em adição a outros parâmetros de filtragem.
- **Artigos de Subcategoria** Visível apenas quando o parâmetro *Excluir ou Incluir Artigos* está definido como *Incluir*. Inclui ou exclui artigos com categorias que são subcategorias das categorias fornecidas no campo *Categoria*.
- **Profundidade da Categoria** Visível apenas quando o parâmetro *Artigos de Subcategoria* está definido como *Incluir*. Especifica quantos níveis de subcategorias são usados.
- **Excluir ou Incluir Artigos** Inclui ou exclui artigos específicos.
- **Artigos para Incluir** Visível apenas quando o parâmetro *Excluir ou Incluir Artigos* está definido como *Incluir*. Se vazio, todos os artigos são incluídos; caso contrário, apenas os artigos selecionados são incluídos.
- **Excluir Artigo Atual** Visível apenas quando o parâmetro *Excluir ou Incluir Artigos* está definido como *Excluir*. Exclui ou inclui o artigo atual.
- **Artigos para Excluir** Visível apenas quando o parâmetro *Excluir ou Incluir Artigos* está definido como *Excluir*. Especifica artigos a serem excluídos da lista.

### Aba de Opções de Exibição

![Aba do módulo de formulário de artigos](../../../pt/images/modules-site/modules-articles-display-options-tab.png)

- **Somente Títulos (listas)** (*Sim/Não*). Se *Sim*, a lista de artigos consiste apenas nos títulos dos artigos, vinculados ao artigo. Todas as outras opções são ocultadas.
- **Layout**
  - *Vertical* Os artigos aparecem em uma única coluna vertical.
  - *Horizontal* Os artigos aparecem em no máximo 1-4 colunas verticais, dependendo da largura do módulo; a largura do módulo é determinada pela posição do módulo, layout da página, modelo, largura da tela, largura de visualização do navegador e outros fatores.
- **Número Máximo de Colunas** Esta opção aparece apenas quando o Layout está definido como Horizontal. Especifica o número máximo de colunas em um layout horizontal (*2–4*).
- **Título do Artigo** Mostra ou oculta o título do artigo.
- **Nível do Cabeçalho** Esta opção aparece apenas quando o *Título do Artigo* está definido como *Mostrar*. Especifica o nível de cabeçalho HTML do título do artigo (*h1–h5, nenhum*).
- **Link do Título** Esta opção aparece apenas quando o *Título do Artigo* está definido como *Mostrar*.
  - *Sim* O título é um hiperlink para o artigo.
  - *Não* O título não é um hiperlink para o artigo.
- **Autor** Mostra ou oculta o autor do artigo.
- **Categoria** Mostra ou oculta a categoria do artigo.
- **Link da Categoria** Aparece apenas se a *Categoria* for mostrada.
  - *Mostrar* Vincula o título da Categoria à sua página.
  - *Ocultar* Mostra o título da Categoria, mas não o vincula.
- **Data** Mostra ou oculta a data do artigo.
- **Campo de Data** Esta opção aparece apenas quando *Data* está definida como *Mostrar*. Especifica qual data do artigo aparecerá: *Data de Criação/Data de Modificação/Data de Início da Publicação*.
- **Formato de Data** Esta opção aparece apenas quando *Data* está definida como *Mostrar*. Especifica o formato da data, por exemplo, Y-m-d H-i-s. Consulte o [manual do PHP](https://www.php.net/manual/en/datetime.format.php) para informações de formatação.
- **Visualizações** Mostra ou oculta o número de vezes que o artigo foi visualizado.
- **Layout das Informações do Artigo** Aparece apenas se um dos campos de metadados acima (*Autor, Categoria, Data ou Visualizações*) for mostrado. Especifica como os metadados do artigo são exibidos:
  - *Multilinha* Cada parâmetro é exibido em sua própria linha.
  - *Linha Única* Os parâmetros aparecem adjacentes uns aos outros em uma única linha, que pode ser quebrada dependendo de seu tamanho e largura do módulo.
- **Tags** Mostra ou oculta as tags de um artigo.
- **Acionar Eventos de Plugin** Defina como *Sim* para acionar eventos adicionais de plugins para exibir conteúdos adicionais, como campos personalizados ou informações de votação.
- **Texto de Introdução** Mostra ou oculta o texto de introdução do artigo. A quantidade de texto exibida é controlada pelo parâmetro *Limite de Texto de Introdução (caracteres)*.
- **Limite de Texto de Introdução (caracteres)** Esta opção aparece apenas quando *Texto de Introdução* está definido como *Mostrar*. Especifica o número de caracteres introdutórios exibidos. Se definido como 0, o texto do artigo inteiro é exibido.
- **Mostrar Imagens do Artigo** Esta opção aparece apenas quando *Texto de Introdução* está definido como *Mostrar* e o *Limite de Texto de Introdução (caracteres)* está definido como zero (o que exibe o texto completo do artigo). Se definido como *Mostrar*, as imagens do artigo são exibidas com o texto.
- **Mostrar Imagem Intro/Completa** Exibe a imagem de introdução do artigo, a imagem completa ou nenhuma imagem acima do título e detalhes do artigo.
- **Link "Leia Mais"** Mostra ou oculta um link "Leia Mais" abaixo dos detalhes do artigo.
- **"Leia Mais" com Título** Esta opção aparece apenas quando a opção *Leia Mais* está definida como *Mostrar*. Adiciona o título ao link *Leia Mais*.
- **Limite de "Leia Mais" (caracteres)** Esta opção aparece apenas quando a opção *"Leia Mais" com Título* está definida como *Mostrar*. Especifica o número máximo de caracteres no título a aparecer no link *Leia Mais*.

### Aba de Opções de Filtragem

![Aba do módulo de formulário de artigos](../../../pt/images/modules-site/modules-articles-filtering-options-tab.png)

- **Artigos em Destaque**
  - *Mostrar* Permite que artigos em destaque apareçam na lista.
  - *Ocultar* Exclui artigos em destaque da lista.
  - *Somente* Mostra apenas artigos em destaque na lista.
- **Artigos Arquivados** Especifica como os artigos arquivados aparecem na lista.
  - *Nenhum* Exclui artigos arquivados da lista.
  - *Somente* Mostra apenas artigos arquivados na lista.
- **Tags** Se especificado, restringe a lista apenas a artigos que têm uma ou mais das tags especificadas.
- **Tipo de Filtragem de Autor** Filtra a lista por autor.
  - *Inclusivo* Restringe a lista apenas aos artigos dos autores especificados.
  - *Exclusivo* Exclui artigos do autor especificado.
  - *Somente do usuário atual* Exibe apenas artigos do autor pelo usuário atual.
- **Autores** Lista de autores a incluir ou excluir.
- **Tipo de Filtragem de Alias de Autor** Filtra a lista por alias de autor.
  - *Inclusivo* Restringe a lista apenas aos artigos dos aliases de autor especificados.
  - *Exclusivo* Exclui artigos dos aliases de autor especificados.
- **Aliases de Autor** Lista de aliases de autor a incluir ou excluir.
- **Filtragem de Data** Especifica como os artigos são filtrados por data.
  - *Desligado* Sem filtragem de data.
  - *Intervalo de Datas* Restringe a lista a artigos com datas caindo no intervalo de datas especificado.
  - *Data Relativa* Restringe a lista a artigos que caem dentro de um número especificado de dias da data atual.
- **Campo de Intervalo de Datas** Esta opção aparece apenas quando *Filtragem de Data* está definida como *Intervalo de Datas* ou *Data Relativa*. Especifica qual data do artigo usar quando for fazer a filtragem de data (*Data de Criação/Data de Modificação/Data de Início da Publicação*).
- **Intervalo de Data Inicial** Esta opção aparece apenas quando *Filtragem de Data* está definida como *Intervalo de Datas*. Especifica a data e hora inicial do filtro de intervalo de datas.
- **Até a Data** Esta opção aparece apenas quando *Filtragem de Data* está definida como *Intervalo de Datas*. Especifica a data e hora final do filtro de intervalo de datas.
- **Data Relativa** Esta opção aparece apenas quando *Filtragem de Data* está definida como *Data Relativa*. Especifica o número de dias relativo à data atual a incluir na lista de artigos.

### Aba de Opções de Ordenação

![Aba do módulo de formulário de artigos](../../../pt/images/modules-site/modules-articles-ordering-options-tab.png)

- **Campo de Ordenação de Artigos**
  - *Ordem dos Artigos* A ordem na qual os artigos são organizados manualmente na tela *Conteúdo > Artigos* do administrador.
  - *Ordem de Artigos em Destaque* Ordem na qual os artigos em destaque são organizados na tela *Conteúdo > Artigos em Destaque* do administrador.
  - *Visualizações* Ordenado pelo número de visualizações da página (visualizações).
  - *Título* Ordenado pelo título do artigo.
  - *ID* Ordenado pelo número de ID do artigo.
  - *Alias* O alias de navegação do artigo.
  - *Data de Criação/Data de Modificação/Data de Início da Publicação/Data de Término da Publicação* Ordenado pela data do artigo.
  - *Aleatório* Ordenação aleatória cada vez que a página é acessada ou atualizada. *Direção de Ordenação* é ignorada.

### Aba de Opções de Agrupamento

![Aba do módulo de formulário de artigos](../../../pt/images/modules-site/modules-articles-grouping-options-tab.png)

O *Campo de Agrupamento por Data* e *Formato de Exibição de Mês e Ano* são visíveis apenas quando um agrupamento relacionado à data é selecionado.

- **Agrupamento de Artigos**
  - *Nenhum* Sem agrupamento.
  - *Ano* Exibe o ano como cabeçalhos.
  - *Mês e Ano* Exibe o mês e o ano como cabeçalhos.
  - *Autor* Exibe *Alias do Autor* ou *Autor* como cabeçalhos.
  - *Categoria* As categorias aparecem como cabeçalhos.
  - *Tags* Tags aparecem como cabeçalhos. Artigos com várias tags aparecem sob vários cabeçalhos.
- **Campo de Agrupamento por Data** Exibido apenas quando *Ano* ou *Mês e Ano* são selecionados. A data do artigo é usada para agrupamento (*Data de Criação/Data de Modificação/Data de Início da Publicação*).
- **Formato de Exibição de Mês e Ano** Exibido apenas quando *Ano* ou *Mês e Ano* são selecionados. Especifica como exibir o cabeçalho de mês e ano. Consulte o [manual do PHP](https://www.php.net/manual/en/datetime.format.php) para informações de formatação.
- **Direção de Agrupamento** Especifica como ordenar os cabeçalhos do grupo (*Ascendente/Descendente*).

## Captura de Tela do Front End

*Imagens de exemplo do site Front End foram obtidas com o Modelo Cassiopeia.*

Módulo de artigos na barra lateral direita mostrando apenas títulos.

![Captura de tela do site com módulo mostrando apenas títulos de artigos](../../../pt/images/modules-site/modules-articles-site-titles.png)

Módulo de artigos na barra lateral direita mostrando título, autor e data.

![Captura de tela do site com módulo mostrando títulos, autor e data dos artigos](../../../pt/images/modules-site/modules-articles-site-title-author-date.png)

Módulo de artigos na localização principal superior mostrando texto introdutório e imagem, e um botão *Leia Mais*.

![Captura de tela do site do módulo na posição superior com botão leia mais](../../../pt/images/modules-site/modules-articles-site-top-text-image-readmore.png)

Módulo de artigos na localização principal superior configurado para um layout horizontal com texto introdutório e imagem, e um botão *Leia Mais*.

![Captura de tela do site com módulo de introdução de texto, imagem e leia mais](../../../pt/images/modules-site/modules-articles-site-text-image-readmore.png)

## Exemplos de Configuração

O módulo de Artigos exibe uma lista de artigos em uma variedade de formatos e layouts. Ele foi projetado com o objetivo de criar um único módulo altamente configurável, capaz de substituir a funcionalidade limitada de cinco módulos de artigos separados. Esta seção oferece exemplos simples de como configurar o módulo para cada um desses papéis.

## Artigos - Arquivados

O módulo *Artigos - Arquivados* exibe uma lista de cabeçalhos de mês/ano para os meses que contêm artigos arquivados. O cabeçalho é um link para a visão dos artigos arquivados, onde os artigos individuais são exibidos. O módulo *Artigos* pode ser configurado para alcançar um resultado semelhante.

**Configurações de Configuração**

| Aba               | Parâmetro                | Configuração       |
|-------------------|--------------------------|--------------------|
| Opções de Exibição| Somente Título (listas)  | Sim                |
| Opções de Filtragem| Artigos Arquivados      | Somente            |
| Opções de Agrupamento| Agrupamento de Artigos  | Mês e Ano          |
| Opções de Agrupamento| Formato de Exibição de Mês e Ano | F, Y             |

![Comparação de artigos arquivados usando cada método](../../../pt/images/modules-site/modules-articles-config-archived.png)

<big>*Notas*</big>

O módulo *Artigos - Arquivados* exibe um único link para uma página de artigos arquivados que exibe a lista de artigos arquivados junto com a capacidade de ajustar a data do arquivamento. O módulo *Artigos* exibe a lista de artigos diretamente — o agrupamento por mês e ano é opcional. A lista pode ser filtrada de forma precisa usando os muitos controles diferentes fornecidos, e uma ampla gama de opções de exibição está disponível para mostrar detalhes adicionais dos artigos.

## Artigos - Categoria

O módulo *Artigos - Categoria* exibe uma lista de links para artigos dentro de uma categoria especificada.

**Configurações de Configuração**

| Aba             | Parâmetro          | Configuração |
|-----------------|--------------------|--------------|
| Módulo          | Categoria           | [especificar a categoria e subcategorias desejadas] |
| Opções de Exibição | Apenas Título (listas) | Sim |

![Comparação de artigos por categoria usando cada método](../../../pt/images/modules-site/modules-articles-config-category.png)

## Artigos - Recentes

O módulo *Artigos - Recentes* exibe uma lista de links para os artigos mais recentes.

**Configurações de Configuração**

| Aba              | Parâmetro                | Configuração |
|------------------|--------------------------|--------------|
| Opções de Exibição | Somente Título (listas)  | Sim          |
| Opções de Ordenação | Campo do Artigo para Ordenar | Data de Início da Publicação |
| Opções de Ordenação | Direção de Ordenação     | Decrescente  |

![Comparação dos artigos recentes usando cada método](../../../pt/images/modules-site/modules-articles-config-latest.png)

<big>*Notas*</big>

O módulo *Artigos* não oferece a ordem *Tocado* encontrada no módulo *Artigos - Recentes*, mas possui várias opções de ordenação que não estão presentes no módulo *Artigos - Recentes*.

## Artigos - Mais Lidos

O módulo *Artigos - Mais Lidos* exibe uma lista de links para artigos com mais acessos.

**Configurações de Configuração**

| Aba              | Parâmetro               | Configuração |
|------------------|-------------------------|--------------|
| Opções de Exibição | Somente Título (listas) | Sim          |
| Opções de Ordenação | Campo do Artigo para Ordenar | Acessos  |
| Opções de Ordenação | Direção de Ordenação  | Decrescente  |

![Comparação de artigos mais lidos usando cada método](../../../pt/images/modules-site/modules-articles-config-most-read.png)

## Artigos - Notícias Flash

O módulo *Artigos - Notícias Flash* exibe o texto de um ou mais artigos. Por padrão, apenas o texto do artigo é exibido; no entanto, ele pode ser configurado para mostrar o título, imagens, links de ler mais e muito mais. Aqui, ele está configurado para exibir o título e o texto de múltiplos artigos. Neste exemplo, o módulo *Artigos* está configurado para replicar esse comportamento básico.

**Configurações de Configuração**

| Aba              | Parâmetro             | Configuração  |
|------------------|-----------------------|---------------|
| Opções de Ordenação | Campo do Artigo para Ordenar Por | Data de Início de Publicação |
| Opções de Ordenação | Direção da Ordenação | Decrescente |
| Opções de Exibição | Somente Título (listas) | Não |
| Opções de Exibição | Link do Título        | Não |
| Opções de Exibição | Texto de Introdução   | Mostrar |
| Opções de Exibição | Limite de Texto de Introdução (Caracteres) | 0 (para texto ilimitado) |

![Comparação de notícias flash de artigos usando cada método](../../../pt/images/modules-site/modules-articles-config-news-flash.png)

*Traduzido por openai.com*


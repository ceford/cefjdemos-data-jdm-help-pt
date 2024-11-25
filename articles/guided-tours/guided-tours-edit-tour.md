<!-- Filename: Help4.x:Guided_Tours:_New_or_Edit_Tour / Display title: Passeios Guiados: Editar Passeio -->

## Descrição

Esta página é usada para adicionar um novo Tour ou editar um Tour existente. Um tour deve incluir pelo menos um passo. Depois que um tour for criado, vá para a lista de Tours e selecione o botão com o rótulo *0* na coluna Passos. O primeiro passo do tour é automaticamente criado a partir do título e da descrição do tour.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba de Publicação](jdocmanual?article=help/common-elements/edit-publishing).

## Como Acessar

- Selecione **Sistema -> Gerenciar -> Tours Guiadas** no menu do Administrador.
- Selecione o botão da barra de ferramentas **Novo** para adicionar um tour.
- Selecione um **Título** da lista para editar um tour.

## Captura de Tela

![Edição de Tour Guiado](../../../pt/images/guided-tours/guided-tours-edit-tour.png)

## Campos do Formulário

- **Título** O título para este tour. Se o título for uma chave de idioma, um campo adicional é mostrado, representando a tradução dessa chave para o idioma do usuário.
- **Identificador do Tour** Um identificador único para o tour. Ao *Salvar* ou *Salvar como Cópia*, um valor é fornecido por padrão. Um formato sugerido seria *nomedoautor-nomedotour*, *nomedaempresa-nomedotour* ou *domínio-nomedotour*. Esse identificador tem múltiplas finalidades: iniciar um tour de qualquer lugar (não apenas do módulo de Tours Guiados), diferenciar tours vindos de diferentes origens e, em sites multilíngues, ele dita a estrutura dos nomes dos arquivos de idioma.

### Aba Editar Tour

#### Painel Esquerdo

- **URL Relativa** O caminho relativo obrigatório de onde o tour começa. Por exemplo, para iniciar um tour a partir da página do tour, insira `administrator/index.php?option=com_guidedtours&view=tours`.
- **Descrição** Aqui é onde você insere a descrição do tour. A descrição do tour pode ser uma chave de idioma. Quando este for o caso, um campo secundário apresenta a descrição traduzida dessa chave para o idioma do usuário.

#### Painel Direito

- **Seletor de Componente** O tour será visível prioritariamente nas páginas das extensões selecionadas. Use *Todos* para mostrar o tour em todas as páginas. Quando configurado como *Todos*, o tour é colocado por último na lista de tours contextuais no menu suspenso do módulo. Este é um campo obrigatório.
- **Início Automático** Permite que o tour comece automaticamente quando um usuário chegar ao contexto no qual o tour deve ser exibido.

## Dicas

- Existem 2 métodos para inserir uma imagem na descrição do tour usando o
  editor TinyMCE.
  1. A lista suspensa **Conteúdo CMS** oferece acesso à tela **Mídia**,
     que permite navegar por arquivos de imagem e fazer upload de imagens.
  2. A lista suspensa *Inserir* é um formulário simples em que você precisa
     saber a URL da imagem. É usada para imagens externas.
- Existem 2 maneiras de criar tours para ambientes multilíngues:
  1. Criar um tour para cada idioma suportado.
  2. Criar apenas um tour para todos os idiomas e usar chaves de idioma 
     para o título e descrição.
- Use **GUIDEDTOUR** nas chaves de idioma como uma convenção onde quer 
  que chaves de idioma sejam usadas (para título e descrição).


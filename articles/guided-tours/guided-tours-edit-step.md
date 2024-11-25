<!-- Filename: Help4.x:Guided_Tours:_New_or_Edit_Step / Display title: Tours Guiados: Editar Etapa -->

## Descrição

Esta página é usada para adicionar uma nova Etapa ou editar uma Etapa existente de um tour.

### Elementos Comuns

Alguns aspectos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).
* [A Aba de Publicação](jdocmanual?article=help/common-elements/edit-publishing).

## Como Acessar

- Selecione **Sistema -> Gerenciar -> Guias** no menu do Administrador.
- Selecione o botão **Passos** numerado de um guia para abrir a página de passos do guia.
- Selecione o botão de barra de ferramentas **Novo** para adicionar um passo.
- Selecione um **Título** da lista para editar um passo.

## Captura de tela

![Edição de etapa dos tours guiados](../../../pt/images/guided-tours/guided-tours-edit-step.png)

## Campos de Formulário

- **Título** O Título para esta etapa. Geralmente, é um chamado para ação, por
exemplo, `Insira um título` se a etapa exigir interação do usuário. Se o título
for uma chave de idioma, um campo adicional é exibido, representando a tradução
dessa chave para o idioma do usuário.

### Aba de Edição da Etapa

#### Painel Esquerdo

- **Descrição** É aqui que você insere a descrição da etapa, geralmente
  uma explicação detalhada ou ajuda para a etapa.
  A descrição da etapa pode ser uma chave de idioma. Quando este for o caso, um
  campo secundário apresenta a descrição traduzida dessa chave para o idioma do
  usuário.

#### Painel Direito

- **Posição** A posição da etapa em relação à informação para a qual aponta.
  - **Inferior** Etapa mostrada abaixo do alvo.
  - **Central** Etapa mostrada no centro da tela. Quando não há um alvo,
    esta é a posição padrão.
  - **Esquerda** Etapa mostrada à esquerda do alvo.
  - **Direita** Etapa mostrada à direita do alvo.
  - **Topo** Etapa mostrada acima do alvo.
- **Alvo** O elemento da tela para o qual a etapa aponta. Usa sintaxe CSS.

  Por exemplo, *.button-new* irá direcionar para o botão da página com a classe
  *button-new*.

  Se o alvo não for único, o primeiro alvo encontrado será usado. Ao criar
  etapas interativas, assegure-se de que o alvo seja focável para acessibilidade. Você
  pode usar vários seletores separados por vírgulas. O primeiro válido se tornará
  o alvo (um seletor é válido se: encontrado na página, não desativado, não
  somente leitura e não oculto). Se um alvo foi definido mas não é encontrado ou
  é inválido, o tour não falhará, mas mostrará a etapa no centro da tela.
- **Tipo** O tipo de etapa.
  - **Próxima** O usuário que estiver executando o tour passará para a próxima etapa.
  - **Redirecionar** A etapa será redirecionada para outra página.
  - **Interativa** A etapa requer interação do usuário, como inserção de dados.
- **URL** A URL para redirecionar em uma etapa do tipo *Redirecionar*.
  Por exemplo, *administrator/index.php?option=com_users&view=user&layout=edit*
  redirecionará a etapa para a tela de edição de usuário.
- **Tipo Interativo** O tipo de interação para uma etapa interativa.
  - **Enviar Formulário** O alvo é um botão que envia um formulário.
  - **Campo de Texto** O alvo é um campo de entrada de texto. Se o campo for obrigatório,
    a pessoa executando o tour não poderá avançar para a próxima etapa
    até que os dados sejam inseridos.
  - **Botão** O alvo é um botão na tela.
  - **Outro** O alvo é qualquer outro elemento de formulário.

### Aba de Opções

![Guia de edição de opção da etapa em tours guiados](../../../pt/images/guided-tours/guided-tours-edit-step-options-tab.png)


## Dicas

- Use **GUIDEDTOUR** nas chaves de idioma como uma convenção sempre que
  as chaves de idioma forem utilizadas (para título e descrição).

*Traduzido por openai.com*


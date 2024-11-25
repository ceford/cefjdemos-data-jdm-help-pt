<!-- Filename: Help4.x:Redirects:_New_or_Edit / Display title: Redirecionamentos: Novo ou Editar -->

## Descrição

A página *Redirecionamentos: Novo ou Editar* é utilizada para adicionar um novo redirecionamento ou editar um existente. A URL da qual você deseja redirecionar não deve ser uma URL funcional em seu site que realmente carregue uma página da web. Pode ser a URL para uma página da web que você desativou na interface do administrador do Joomla! A URL de Origem que você especifica ao criar o redirecionamento deve ser a URL completa, exatamente como você a digitaria em seu navegador. A URL de Destino que você especifica ao criar um redirecionamento também deve ser a URL completa.

### Elementos Comuns

Alguns elementos desta página são abordados em artigos de ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).

## Como acessar

- Selecione **Sistema → Redirecionamentos** no menu do Administrador. Em seguida...
  - Para criar um novo redirecionamento, clique no botão **Novo** na Barra de Ferramentas. Ou...
  - Para editar um redirecionamento existente, clique em seu link na coluna **URL Expirada**.

## Captura de Tela

![Links de redirecionamento](../../../pt/images/redirects/redirects-edit.png)

## Campos do Formulário

### Aba Editar/Novo Link #1

- **URL Expirada** O URL a ser redirecionado.
- **Novo URL** O URL para onde redirecionar.
- **Status** Estado publicado do item. Valores possíveis são:
  - *Habilitado* O item está habilitado. Este é o único estado que permitirá
    aos usuários regulares do site visualizar este item.
  - *Desabilitado* O item está desabilitado.
  - *Arquivado* O item foi arquivado.
  - *Na Lixeira* O item foi enviado para a Lixeira.
- **Comentário** Um comentário que só pode ser visto por um administrador. É
  destinado principalmente para referência do administrador.
- **ID** Este é um número de identificação único para este item atribuído
  automaticamente pelo Joomla. É utilizado para identificar o item internamente,
  e você não pode alterar este número. Ao criar um novo item, este
  campo exibe "0" até você salvar a nova entrada, momento em que um novo
  ID é atribuído a ele.
- **Data de Criação** Data em que o item (Artigo, Categoria, etc.) foi criado.
- **Data da Última Atualização** Mostra a última data em que o item foi modificado.

## Como Criar um Redirecionamento

1. Primeiro, certifique-se de que você habilitou a opção *Usar Reescrita de URL* nas opções de Configuração Global da sua instalação do Joomla!. Observe que apenas habilitar a opção *Usar Reescrita de URL* não é suficiente. Você também deve dar o passo adicional de renomear o arquivo `htaccess.txt` no diretório do servidor web onde você instalou o Joomla! para `.htaccess` ou para qualquer outro nome de arquivo que seu servidor web Apache exija para diretivas de configuração adicionais. No arquivo de configuração do Apache, esta configuração é nomeada `AccessFileName` e, por padrão, está configurada como `.htaccess`.
2. Em seguida, abra a página *Redirecionamento: Links* e selecione o botão de ferramentas *Novo*.
3. Na página *Redirecionamentos: Novo*, insira as informações do redirecionamento. Ao inserir URLs nos campos *URL Expirado* e *Novo URL*, digite o URL completo como você o digitariam em seu navegador para visualizá-lo. O *URL Expirado* deve ser um URL que não resolve para nenhuma página web válida no seu site. Você pode especificar um URL de origem para uma página do Joomla! que você colocou em estado desativado no back-end do administrador. Certifique-se de que a opção *Estado* está configurada como **Habilitado**.
4. Selecione o botão de ferramentas **Salvar & Fechar** para salvar seu novo redirecionamento e colocá-lo em efeito.

## Dicas

- Ao inserir URLs nos campos *URL Expirada/Fonte* e *Nova/URL de Destino*, insira a URL completa como se fosse digitá-la no seu navegador para visualizar a página da web.

*Traduzido por openai.com*


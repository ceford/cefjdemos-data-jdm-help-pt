<!-- Filename: Help4.x:Extensions:_Install / Display title: Extensões: Instalar -->

## Descrição

Extensões são utilizadas para adicionar funcionalidades ao Joomla! que não existem na instalação padrão. Centenas de extensões estão disponíveis para Joomla!, com mais sendo desenvolvidas o tempo todo.

As extensões são categorizadas em cinco tipos, como segue:

- Um *Componente* é uma miniaplicação que processa o corpo principal da página. Exemplos de Componentes são Contatos, a Página Inicial, e Feeds de Notícias.
- Um *Módulo* é uma Extensão menor tipicamente usada para renderizar um pequeno elemento que aparece em várias páginas. Exemplos de Módulos incluem Menus e Itens Relacionados.
- Um *Plugin* é um trecho de código que é executado quando um evento predefinido ocorre dentro do Joomla!. Por exemplo, editores são Plugins que são executados quando uma sessão de edição é aberta.
- A Extensão de *Idioma* permite que o Front-end e Back-end do Joomla! sejam apresentados em qualquer idioma para o qual exista uma Extensão de idioma. Desta forma, o Joomla! pode ser lançado em um novo idioma sem alterações no programa principal.
- Um *Template* controla como o conteúdo de um site é exibido, incluindo a localização e o layout dos elementos, cores, fontes, e assim por diante. Os templates permitem que a aparência do site seja separada do seu conteúdo.

### Elementos Comuns

Alguns elementos desta página são abordados em artigos de Ajuda separados:

* [Barras de Ferramentas](jdocmanual?article=help/common-elements/toolbars).

## Como Acessar

- Selecione **Sistema → Instalar Painel → Extensões** no menu do
  Administrador.

Existem quatro métodos de instalação disponíveis. Se **Instalar da Web** foi
colocado em primeiro na lista ou foi o último método selecionado, haverá um
pequeno atraso enquanto o Joomla baixa uma seleção inicial de dados de Extensões
do Diretório de Extensões do Joomla.

A ordem normal das Abas para os métodos de instalação é a seguinte:

* Enviar Arquivo do Pacote
* Instalar de uma Pasta
* Instalar de URL
* Instalar da Web

Apenas um método é necessário para instalar uma determinada Extensão. O procedimento normal para instalar uma Extensão do Joomla! é o seguinte:

1. Baixe um ou mais arquivos de arquivo (normalmente no formato ".zip" ou "tar.gz") do site do fornecedor da Extensão para um diretório local em seu computador. Note que algumas Extensões são instaladas como um arquivo (por exemplo, um Componente ou Módulo) enquanto outras Extensões podem ter dois ou mais arquivos (por exemplo, um Componente e um Módulo). Se houver duas ou mais partes, cada uma pode ter seu próprio arquivo de arquivo. Ou as partes podem ser combinadas em um arquivo de pacote.
   
2. Escolha um dos métodos descritos para instalar a extensão.

3. Quando concluído, a tela exibirá uma mensagem de **Sucesso** ou **Falha**.

4. Dependendo da Extensão, pode ser necessário habilitar a Extensão (por exemplo, nas listas de Módulos ou Plugins).

## Aba Enviar Arquivo do Pacote

![Extensão instalar aba de enviar arquivo do pacote](../../../pt/images/extensions/install-upload-package-file.png)

- Arraste e solte ou navegue até o local onde você baixou o arquivo de
  arquivo da extensão.

O upload começa automaticamente. Observe o **Tamanho máximo de upload: 32,00 MB**
definido para sua instalação. Se você não puder aumentar esse valor, pode usar
*Instalar a partir da Pasta*.

## Instalar a partir da Aba de Pasta

![Instalação da extensão a partir da aba de pasta](../../../pt/images/extensions/install-from-folder.png)

1. Crie um diretório temporário no seu disco rígido local e descompacte o arquivo de arquivo da extensão nesse diretório temporário.
2. Usando FTP, faça o upload do conteúdo desse diretório (incluindo arquivos e subdiretórios) para um diretório no seu servidor.
3. No campo *Instalar Diretório*, especifique o diretório do servidor onde você fez o upload dos arquivos e subdiretórios do pacote.
4. Clique no botão *Verificar e Instalar* e o Joomla! instalará o conteúdo do diretório indicado.

Note que é uma prática comum colocar a pasta contendo a sua extensão descompactada na pasta tmp do seu site Joomla.

## Instalar a partir da guia URL

![Instalar extensão a partir da guia URL](../../../pt/images/extensions/install-from-url.png)

Em vez de baixar o arquivo do pacote para o seu computador local, basta especificar o URL do arquivo do pacote alvo. Em seguida, clique no botão "Verificar e Instalar" e o Joomla! fará a instalação automaticamente diretamente desse URL. *Note que, com este método, você não terá uma cópia do arquivo do pacote em seu computador local.*

## Instalar pela Guia da Web

Para instalar uma extensão diretamente do Diretório de Extensões 
do Joomla (JED). Você pode selecionar extensões para listar por Categoria ou 
pode pesquisar por nome parcial.

![Instalação de extensão pela guia da web](../../../pt/images/extensions/install-from-web.png)

## Dicas

- Quatro métodos alternativos de instalação estão disponíveis, conforme indicado acima. O mais comum é o método "Fazer Upload do Arquivo do Pacote".
- Se você deseja instalar um Módulo ou Plugin de terceiros que pertence a um Componente, geralmente precisará instalar o Componente, assim como o Módulo ou Plugin, para poder usá-lo. Normalmente, isso é documentado nas instruções de instalação da Extensão no site do autor.
- Da mesma forma, se você desinstalar um Componente de terceiros que também tem seus próprios Módulos ou Plugins, esses Módulos e Plugins não poderão mais ser usados. Portanto, é normalmente recomendado desinstalar também esses Módulos e Plugins dependentes.
- Alguns Componentes desenvolvidos por desenvolvedores de terceiros podem ter seus próprios Módulos ou Plugins incluídos no instalador. Nesse caso, certifique-se de que os diretórios desses Módulos ou Plugins sejam graváveis. Caso contrário, a Extensão não funcionará corretamente.
- **AVISO DE SEGURANÇA:** Recomenda-se que você use apenas aquelas Extensões de terceiros em seu site que você realmente precisa. Não use seu site ao vivo para fins de teste, pois isso pode comprometer seu site e servidor. Teste novas extensões em um site de teste local antes de implementá-las em seu site ao vivo.
- Não instale Extensões Joomla! baixadas de sites de
  [Warez](https://en.wikipedia.org/wiki/Warez) porque podem estar infectados por um vírus ou malware que cause danos no servidor e pode contaminar o computador dos seus visitantes!
- Instalar a partir de URL remota pode ser perigoso. Por essa razão, geralmente é recomendado que você use as opções "Instalar da Web", "Fazer Upload do Arquivo do Pacote" ou "Instalar a partir da Pasta" ao instalar novas Extensões.

*Traduzido por openai.com*


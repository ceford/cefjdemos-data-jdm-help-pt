<!-- Filename: Help4.x:Extensions:_Install / Display title: Extensões - Instalação do Gestor de Extensões -->

## Descrição

Extensões são *add-ons\<* que expandem a funcionalidade do Joomla!. As
«Extensões» são utilizadas para adicionar funcionalidades ao Joomla! que
não existem no pacote padrão. Estão disponíveis centenas de «Extensões»
para o Joomla!, com mais sempre em desenvolvimento.

As »Extensões» estão categorizadas em cinco tipos, como se segue:

- A *Component* is a mini-application that renders the main body of the
  page. Examples of Components are Contacts, the Front Page, and News
  Feeds.
- A *Module* is a smaller Extension typically used for rendering a small
  element that displays across multiple pages. Examples of Modules
  include Menus and Related Items.
- A *Plugin* is a section of code that runs when a pre-defined event
  happens within Joomla!. For example, editors are Plugins that run when
  an edit session is opened.
- The *Language* Extension allows for the Front-end and Back-end of
  Joomla! to be presented in any language for which a language Extension
  exists. This way, Joomla! can be released in a new language with no
  changes to the core program.
- A *Template* controls the way the content of a web site is displayed,
  including the location and layout of elements, colors, fonts, and so
  on. Templates allow the appearance of the web site to be separated
  from its content.

## Como Aceder

- Select **System → Install Panel → Extensions** from the
  Adminstrator menu.

There will be a brief delay as Joomla downloads an initial selection of
Extension data from the Joomla Extensions Directory.

## Captura de Ecrã

<img
src="https://docs.joomla.org/images/8/86/Help-4x-Extensions-Extension-Manager-Install-screen-en.png"
decoding="async" data-file-width="800" data-file-height="996"
width="800" height="996"
alt="Extensions Extension Manager Install screen" />

## Dos Campos

Joomla! Extensions can be installed using one of four methods, as
indicated below. Only one method is needed to install a given Extension.

The normal procedure for installing a Joomla! Extension is as follows:

1.  Download one or more archive files (normally ".zip" or "tar.gz"
    format) from the Extension provider's web site to a local directory
    on your computer.

Note that some Extensions are installed as one file (for example, one
Component or Module) while other Extensions might have two or more files
(for example, a Component and a Module). If there are two or more parts,
each one will have its own archive file.

1.  Choose one of the methods describe below (**usually Package File**)
1.  When it is finished, the screen will display the message "Install
    Component Success". If the installation is not successful, an error
    message will display.
1.  Depending on the Extension, it may be necessary to enable the
    Extension (for example, in the Modules
    list
    or

### Instalar a partir de um «Separador da Web»

If installed, you will see the Install from Web tab, illustrated in the
Screenshot, to install an extension direct from the Joomla Extension
Directory (JED). You can select extensions to list by Category or you
can search by partial name.

### Enviar Pacote do Separador de Ficheiros

<img
src="https://docs.joomla.org/images/0/06/Help-4x-Extensions-Manager-Install-UploadPackageFilescreen-en.png"
decoding="async" data-file-width="600" data-file-height="325"
width="600" height="325"
alt="Extensions Manager Install UploadPackageFilescreen" />

- Arraste e largue ou explore a localização onde transferiu o ficheiro
  de arquivo da «Extensão».

O envio começa automaticamente..Note que o **Tamanho máximo de envio:
X.00 MB** definido para sua instalação. Se não pode aumentar este valor,
pode utilizar "Instalar da Pasta".

### Instalar a partir de um «Separador de Pasta»

<img
src="https://docs.joomla.org/images/d/d9/Help-4x-Extensions-Manager-Install-InstallfromFolder-screen-en.png"
decoding="async" data-file-width="600" data-file-height="248"
width="600" height="248"
alt="Extensions Manager Install InstallfromFolder screen" />

1.  Create a temporary directory on your local hard drive and unpack the
    Extension's archive file in this temporary directory.
1.  Using FTP, upload the contents of this directory (including files
    and subdirectories) to a directory on your server.
1.  In the *Install Directory* field specify the server directory where
    you uploaded the files and subdirectories of the package.
1.  Click on the *Check and Install* button and Joomla! will install the
    contents of the given directory.

Note that it is common practice to put the folder containing your
unpacked extension in the tmp folder of your Joomla site.

### Instalar a partir de um «Separador de URL»

<img
src="https://docs.joomla.org/images/6/69/Help-4x-Extensions-Manager-Install-InstallfromUrl-screen-en.png"
decoding="async" data-file-width="600" data-file-height="251"
width="600" height="251"
alt="Extensions Manager Install InstallfromUrl screen" />

Instead of downloading the archive file to your local computer, just
specify the URL of the target archive file. Then click the "Check and
Install" button and Joomla! automatically installs it directly from this
URL. *Note that, with this method, you will not have a copy of the
archive file on your local computer.*

## Barra de Ferramentas

No topo da página, irá ver a barra de ferramentas mostrada na [Captura
de Ecrã](#Captura_de_Ecr.C3.A3) acima. As funções são:

- **Opções.** abre a janela das «Opções» onde as definições como os
  parâmetros predefinidos podem ser editados.
- **Ajuda**. Abre este ecrã de ajuda.

## Hiperligações para Outros Ecrãs

- **Instalar.** Interliga ao
- **Atualizar.** Interliga ao
- **Manage.** Links to the
- **Discover.** Links to the
- **Database.** Links to the
- **Warnings.** Links to the
- **Install Languages.** Links to the Install Languages Screen.
- **Update Sites.** Links to the <a
  href="https://docs.joomla.org/index.php?title=Help4.x:Extensions_Extension_Manager_Update_Sites/en&amp;action=edit&amp;redlink=1"
  class="new"
  title="Help4.x:Extensions Extension Manager Update Sites/en (page does not exist)">Update
  Sites Screen</a>.

## Dicas Rápidas

- Four alternate installation methods are available, as indicated above.
  The most common one is the "Upload Package File" method.
- If you want to install a third-party Module or Plugin that belongs to
  a Component, you will generally need to install the Component as well
  as the Module or Plugin in order to use the Module or Plugin. This is
  normally documented in the Extension's installation instructions on
  the author's web site.
- Similarly, if you uninstall a third-party Component that also has its
  own Modules or Plugins, these Modules and Plugins can no longer be
  used. So it is normally recommended to uninstall these dependent
  Modules and Plugins as well.
- Some Components developed by third party developers may have their own
  Modules or Plugins included in the installer. In this case, make sure
  these Module or Plugin directories are writable. Otherwise the
  Extension will not work properly.
- **AVISO DE SEGURANÇA:** É recomendado que utilize apenas essas
  «Extensões» de terceiros no seu *site* que realmente precisa. Não
  utilize o seu *site live* para efeitos de testes porque isso pode
  comprometer o seu *site* e o servidor. Teste as novas extensões num
  *site* da Web local de testes antes de implementar o seu *site live*.
- Não instale as «Extensões» do Joomla! transferidas dos *sites* warez
  porque estas podem estar infetadas com um vírus ou *malware* que
  danificam o servidor e podem contaminar o computador dos seus
  visitantes!
- Instalar a partir de um URL remoto pode ser perigoso. Por este motivo,
  é normalmente recomendado que utilize as opções "Instalar a partir da
  Web", "Enviar Ficheiro do Pacote" ou "Instalar a partir de Pasta"
  quando instalar novas «Extensões».

## Informação Relacionada

- Se instalar uma «Extensão de Componente», esta será listada como um
  novo «Item de Menu» no menu de «Componentes».
- You can assign a Menu Item to an installed Component Extension in the
  Menu Items
  list
  by clicking the *New* toolbar button. The new Component will show in
  the Internal Link list of Menu Item Types.
- If you install a Module Extension, it will be added to the list of the
  Modules in the Modules
  list,
  where you can enable/disable it. You can also customize it's
  parameters in the Module
  Edit
  screen.
- An installed Plugin Extension will be added to the list of the
  Plugins
  list,
  where you can enable/disable it. By clicking the Plugin
  Name,
  you can customize its parameters on the following screen.
- An installed Template Extension will be added to the Site or
  Administrator list of the Template Styles
  list
  where you can assign it to all of the pages or to the selected ones.
  You can also customize its parameters, edit the HTML or CSS source, or
  preview the available Module positions.
- An installed Language Extension will be added to the Site or
  Administrator list of the Languages
  list,
  depending on the client attribute of the Extension. This screen let's
  you assign it as the default language, if desired.

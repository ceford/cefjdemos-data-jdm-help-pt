<!-- Filename: Help4.x:Joomla_Update / Display title: Atualização do Joomla  -->

## Descrição

Esta página permite que o Joomla! seja atualizado usando um pacote de atualização do repositório de código do Joomla! É melhor e mais seguro deixar que o próprio Joomla se atualize usando este método.

## Como Acessar

No **Painel Inicial → Painel de Notificações**, o ícone do Joomla terá uma das duas mensagens:
- **Joomla está atualizado**
- **X.Y.Z Disponível - Atualize agora!**

Selecione o ícone.

Além disso, o **Sistema → Painel de Atualização → Joomla** exibirá um visto, indicando que está atualizado, ou um número de versão, indicando que uma nova versão está disponível.

## Captura de Tela

Se o seu site estiver atualizado, você verá esta tela:

![Carregar & Atualizar atualizado](../../../en/images/joomla-update/upload-update-up-to-date.png)

Se uma atualização estiver disponível, você verá esta tela:

![Carregar & Atualizar atualização disponível](../../../en/images/joomla-update/upload-update-available.png)

Ao atualizar para uma versão principal ou secundária, você verá uma tela de verificação pré-atualização:

![Carregar & Atualizar verificação pré-atualização](../../../en/images/joomla-update/upload-update-pre-update-check.png)

Selecione cada um dos três itens do menu para ver se algo precisa de atenção.

## Iniciar Atualização

Se você não estiver na versão mais recente do Joomla, pode instalar a
atualização mais recente a partir desta página. Para fazer isso, certifique-se de ter feito um backup
e marque a caixa de seleção **Estou ciente...** para indicar que você já fez isso. Em seguida,
selecione o botão **Iniciar Atualização** e o Joomla instalará a versão mais recente.

A tela de atualização mostra uma barra de progresso enquanto a atualização está em andamento.

### Fazer Upload e Atualizar

Você pode usar este botão para atualizar o Joomla se o seu servidor estiver atrás de um
firewall ou de alguma forma incapaz de contatar os servidores de atualização. Primeiro,
baixe o Pacote de Upgrade do Joomla em formato ZIP da página oficial de downloads do Joomla.

Você deve ter o *upload_max_filesize* e o *post_max_size* do seu PHP definidos para 64Mb
e seu limite de memória PHP definido para 256 Mb. Caso contrário, a atualização pode falhar. Uma
boa razão para fazer aquele backup!

![Upload & Update upload and install](../../../en/images/joomla-update/upload-update-upload-install.png)

## Opções de Atualização

O botão Opções da Barra de Ferramentas permite que você selecione o tipo de atualização:

- **Padrão** Este é utilizado para sites configurados para permanecer com a versão instalada.
- **Joomla Próximo** Este é utilizado para sites que normalmente avançam para a próxima versão principal assim que uma versão estável é lançada.
- **URL Personalizado** Para desenvolvedores selecionarem uma fonte de atualização.

*Traduzido por openai.com*

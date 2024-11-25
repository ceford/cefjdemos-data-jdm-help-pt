<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_Authentication_Group / Display title: Grupo de Autenticação -->

## Descrição do Grupo

Os plugins deste grupo são usados para login padrão de usuários nas interfaces do Site ou do Administrador. O padrão é Joomla Authentication. O método *Cookie* é usado em conjunto com a função *Lembrar-me* apenas para login no Site. O cookie é definido após o primeiro login com um dos outros métodos.

## Autenticação - Cookie

![plugin de autenticação por cookie](../../../en/images/plugins/plugin-group-authentication-cookie.png)

- **Tempo de Vida do Cookie** O número de dias até que o cookie de autenticação expire. Outros fatores podem causar sua expiração antes disso. Durações mais longas são menos seguras.
- **Comprimento da Chave** O comprimento da chave usada para criptografar o cookie. Comprimentos mais longos são mais seguros, mas podem reduzir o desempenho.

## Autenticação - Joomla

Este plugin processa o método padrão de Autenticação de Usuário no Joomla. Não possui opções.

## Autenticação - LDAP

Este plugin processa a autenticação de usuários contra um servidor LDAP.

![plugin de autenticação ldap](../../../en/images/plugins/plugin-group-authentication-ldap.png)

- **Host** A URL do host. Por exemplo, `openldap.mycompany.org`.
- **Porta** O número da porta. O padrão é 389.
- **LDAP V3** Se este host usa ou não a versão 3 do LDAP. O padrão é LDAP v2.
- **Negociar TLS** Se deve ou não usar criptografia TLS com este host. Se definido como *Sim*, todo o tráfego de e para este servidor deve ser criptografado.
- **Seguir Referências** Se deve definir o flag LDAP_OPT_REFERRALS como Sim ou Não. Para hosts Windows 2003, isso deve ser definido como Não.
- **Método de Autorização** *Conectar Diretamente como Usuário* ou *Conectar e Pesquisar*.
- **Base DN** O Base DN do seu servidor LDAP.
- **String de Pesquisa** Uma string de consulta usada para pesquisar um determinado Usuário. A palavra-chave `[search]` é substituída pelo login digitado pelo Usuário. Por exemplo: `uid=[search]`. Mais de uma String de Pesquisa pode ser inserida. Separe cada uma por um ponto e vírgula `;`. Isso é usado somente durante a pesquisa.
- **DN do Usuário** A palavra-chave [username] é substituída dinamicamente pelo nome de usuário digitado pelo Usuário. Um exemplo de string é: `uid=[username], dc=[meu-dominio], dc=[com]`. Mais de uma string pode ser inserida. Separe cada uma com um ponto e vírgula `;`. Isso é usado somente se o Método de Autorização acima estiver definido para *Conectar Diretamente como Usuário*.
- **Nome de Usuário de Conexão e Senha de Conexão** Estas definem parâmetros de conexão para a fase de consulta ao DN. Para consulta anônima, deixe ambos os campos em branco. Para uma Conexão Administrativa, o *Nome de Usuário de Conexão* é o nome de usuário de uma conta administrativa (por exemplo, *Administrador*). Neste caso, a *Senha de Conexão* é a senha real desta conta administrativa.
- **Mapear: Nome Completo** O atributo LDAP que contém o nome completo do Usuário.
- **Mapear: Email** O atributo LDAP que contém o endereço de email do Usuário.
- **Mapear: ID de Usuário** O atributo LDAP que contém o ID de login do Usuário. Para Active Directory, é `sAMAccountName`.
- **Depurar** Ativa a depuração codificada em nível 7.

*Traduzido por openai.com*


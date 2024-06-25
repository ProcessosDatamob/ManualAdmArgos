# Configurações Gerais - Android - Work Profile

Profile é um modo de gerenciamento exclusivo para dispositivos pessoais, ele permite que um usuário com o seu dispositivo pessoal possa criar um ambiente seguro para utilizar aplicativos de trabalho, garantindo segurança necessária para as informações da empresa e a privacidade do usuário, uma vez que o dispositivo é pessoal.

Para isso, o usuário precisa realizar o download do aplicativo **Android Device Policy** na loja de aplicativos e ler o QR CODE da política com o modo gerenciamento “**Android - Work Profile**”. Ao final do provisionamento, o dispositivo apresentará aplicativos de trabalho com o ícone do perfil de trabalho (maleta azul) e os aplicativos particulares sem ícones.

{% hint style="warning" %}
**IMPORTANTE**

* Não é necessário realizar o Factory reset no dispositivo para realizar o provisionamento, basta realizar o download do aplicativo “ **Android Device Policy**” e seguir os passos de provisionamento.
* Ao realizar o comando “**Remover Dispositivo**” no menu agrupado da tela “**Lista de Dispositivos**”, o perfil de trabalho no dispositivo e os aplicativos de trabalho serão removidos. Não será realizado o reset do dispositivo.
* O usuário possui autonomia para remover o perfil de trabalho através do dispositivo, sem que seja necessário autorização do Administrador.
* O Android Go oferece suporte a cenários de implantação totalmente gerenciados e dedicados. No entanto, o perfil de trabalho (BYOD) é opcional e, portanto, ausente na maioria dos dispositivos Go.
{% endhint %}

As configurações gerais são agrupadas nos tipos:

* [Restrições de Senha - Dispositivo](configuracoes-gerais-android-work-profile.md#restricoes-de-senha-dispositivo)
* [Restrições de Senha - Perfil de Trabalho](configuracoes-gerais-android-work-profile.md#restricoes-de-senha-perfil-de-trabalho)
* <mark style="color:red;">Tela</mark>
* [Trabalho](configuracoes-gerais-android-work-profile.md#trabalho)

<figure><img src="../../../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

### **Restrições de Senha - Dispositivo**

<figure><img src="../../../.gitbook/assets/image (83).png" alt=""><figcaption></figcaption></figure>

<table data-header-hidden><thead><tr><th width="307.8854625550661"></th><th></th></tr></thead><tbody><tr><td><strong>Configuração</strong></td><td><strong>Descrição</strong></td></tr><tr><td>Qualidade da senha</td><td><p>Nesta configuração, temos as seguintes opções disponíveis:</p><p>- Nenhuma</p><p>- Biometria</p><p>- Alguma</p><p>- Numérica</p><p>- Numérica Complexa</p><p>- Alfabética</p><p>- Alfanumérica</p><p>- Complexa</p></td></tr><tr><td>Comprimento de histórico de senhas</td><td>Define o número de senhas já usadas que não podem ser reutilizadas</td></tr><tr><td>Máximo de senhas incorretas antes de executar wipe</td><td>Define o máximo de tentativas incorretas antes de executar o Wipe</td></tr><tr><td>Tempo limite de expiração da senha (dias)</td><td>Define quantos dias a senha vai levar para expirar</td></tr><tr><td>Exigir desbloqueio de senha</td><td>Nesta configuração temos as opções: Padrão do dispositivo, ou seja, definida conforme configurado no dispositivo ou todo dia, neste caso a senha será solicitada todo dia</td></tr></tbody></table>

### **Restrições de Senha - Perfil de Trabalho**

<mark style="color:red;background-color:orange;">NOVA IMAGEM</mark>

<figure><img src="../../../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

Se a chave estiver habilitada permite ao usuário manter a mesma senha definida para o “**Dispositivo**” no “**Perfil de Trabalho**”.

Quando a opção estiver desativada, obriga ao usuário criar uma senha diferente da senha pessoal, para acessar o perfil de trabalho. São exibidas as mesmas configurações descritas na tabela acima para definição de senha.

<table data-header-hidden><thead><tr><th width="307.8854625550661"></th><th></th></tr></thead><tbody><tr><td><strong>Configuração</strong></td><td><strong>Descrição</strong></td></tr><tr><td>Qualidade da senha</td><td><p>Nesta configuração, temos as seguintes opções disponíveis:</p><p>- Biometria</p><p><mark style="color:red;background-color:orange;">- Alguma</mark></p><p>- Numérica</p><p>- Numérica Complexa</p><p>- Alfabética</p><p>- Alfanumérica</p><p>- Complexa</p></td></tr><tr><td>Comprimento de histórico de senhas</td><td>Define o número de senhas já usadas que não podem ser reutilizadas</td></tr><tr><td>Máximo de senhas incorretas antes de executar wipe</td><td>Define o máximo de tentativas incorretas antes de executar o Wipe</td></tr><tr><td>Tempo limite de expiração da senha (dias)</td><td>Define quantos dias a senha vai levar para expirar</td></tr><tr><td>Exigir desbloqueio de senha</td><td>Nesta configuração temos as opções: Padrão do dispositivo, ou seja, definida conforme configurado no dispositivo ou todo dia, neste caso a senha será solicitada todo dia</td></tr></tbody></table>

### Tela

<mark style="color:red;">Estando na guia de "</mark><mark style="color:red;">**Configurações**</mark><mark style="color:red;">" da tela de "</mark><mark style="color:red;">**Edição de Políticas**</mark><mark style="color:red;">", clique sobre a opção "</mark><mark style="color:red;">**Tela**</mark><mark style="color:red;">" para visualizar as opções de configuração de papel de parede e rotação de tela.</mark>&#x20;

<figure><img src="../../../.gitbook/assets/image (218).png" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">Na tabela a seguir, as configurações são descritas:</mark>

<table><thead><tr><th width="274">Configuração</th><th>Descrição</th></tr></thead><tbody><tr><td>Desabilitar mudança de papel de parede</td><td><mark style="color:red;">Permite que o usuário administrador desabilite a função de mudança de papel de parede do dispositivo. Estando habilitada, a alteração do plano de fundo está desativada.</mark></td></tr><tr><td>Definir Papel de Parede</td><td><mark style="color:red;">Permite realizar o upload de uma imagem de papel de parede que será enviada para o dispositivo.</mark></td></tr></tbody></table>

{% hint style="info" %}
<mark style="color:red;">**OBSERVAÇÃO**</mark>

<mark style="color:red;">Quando um dispositivo for registrado na política com a configuração de papel de parede, será ajustado o papel de parede conforme a imagem recebida, tanto no modo quiosque quanto fora dele, mantendo o funcionamento atual.</mark>
{% endhint %}

### Trabalho

Essa funcionalidade permite ao usuário administrador configurar um bloqueio total do dispositivo fora de um período de tempo específico. Assim, permitindo que seja realizado o bloqueio do dispositivo quando o usuário não estiver no horário de trabalho.

Estando na aba "**Configurações**" da tela "**Editar Políticas**", clique em "**Trabalho**" para ver as opções de configuração.

<figure><img src="../../../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>

Para realizar o bloqueio de dispositivos fora do horário de trabalho, siga os passos a seguir:

1. Ative a opção "Bloquear dispositivo fora do horário de trabalho".
2. Preencha o campo "Dias de trabalho", com os dias trabalhados na semana dia de início e dia fim.
3. Preencha o campo "Horário de trabalho", com horário de trabalho inicial e final.

<figure><img src="../../../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Observação:**

Ao deixar os campos em branco o sistema considera o período inteiro do dia."
{% endhint %}

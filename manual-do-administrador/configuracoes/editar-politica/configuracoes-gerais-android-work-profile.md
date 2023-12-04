# Configurações Gerais - Android - Work Profile

Work Profile é um modo de gerenciamento exclusivo para dispositivos pessoais, ele permite que um usuário com o seu dispositivo pessoal possa criar um ambiente seguro para utilizar aplicativos de trabalho, garantindo segurança necessária para as informações da empresa e a privacidade do usuário, uma vez que o dispositivo é pessoal.

Para isso, o usuário precisa realizar o download do aplicativo **Android DPC** na loja de aplicativos e ler o QR CODE da política com o modo gerenciamento “**Android - Work Profile**”. Ao final do provisionamento, o dispositivo apresentará aplicativos de trabalho com o ícone do perfil de trabalho (maleta azul) e os aplicativos particulares sem ícones.

{% hint style="warning" %}
**IMPORTANTE**

* Não é necessário realizar o Factory reset no dispositivo para realizar o provisionamento, basta realizar o download do aplicativo “**Android - DPC**” e seguir os passos de provisionamento.
* Ao realizar o comando “**Remover Dispositivo**” no menu agrupado da tela “**Lista de Dispositivos**”, o perfil de trabalho no dispositivo e os aplicativos de trabalho serão removidos. Não será realizado o reset do dispositivo.
* O usuário possui autonomia para remover o perfil de trabalho através do dispositivo, sem que seja necessário autorização do Administrador.
* O Android Go oferece suporte a cenários de implantação totalmente gerenciados e dedicados. No entanto, o perfil de trabalho (BYOD) é opcional e, portanto, ausente na maioria dos dispositivos Go.
{% endhint %}

As configurações gerais são agrupadas nos tipos:

* Restrições de Senha - Dispositivo
* Restrições de Senha - Perfil de Trabalho

<figure><img src="../../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

## **Restrições de Senha - Dispositivo**

<figure><img src="../../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

<table data-header-hidden><thead><tr><th width="254"></th><th></th></tr></thead><tbody><tr><td><strong>Configuração</strong></td><td><strong>Descrição</strong></td></tr><tr><td>Qualidade da senha</td><td><p>Nesta configuração, temos as seguintes opções disponíveis:</p><p>- Nenhuma</p><p>- Biométrica</p><p>- Alguma Numérica</p><p>- Numérica Complexa</p><p>- Alfabética</p><p>- Alfanumérica</p><p>- Complexa</p></td></tr><tr><td>Comprimento de histórico de senhas</td><td>Define o número de senhas já usadas que não podem ser reutilizadas</td></tr><tr><td>Máximo de senhas incorretas antes de executar wipe</td><td>Define o máximo de tentativas incorretas antes de executar o Wipe</td></tr><tr><td>Tempo limite de expiração da senha (dias)</td><td>Define quantos dias a senha vai levar para expirar</td></tr><tr><td>Exigir desbloqueio de senha</td><td>Nesta configuração temos as opções: Padrão do dispositivo, ou seja, definida conforme configurado no dispositivo ou todo dia, neste caso a senha será solicitada todo dia;</td></tr></tbody></table>

## **Restrições de Senha - Perfil de Trabalho**

<figure><img src="../../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

Se a chave estiver habilitada permite ao usuário manter a mesma senha definida para o “**Dispositivo**” no “**Perfil de Trabalho**”.

Quando a opção estiver desativada, obriga ao usuário criar uma senha diferente da senha pessoal, para acessar o perfil de trabalho. São exibidas as mesmas configurações descritas na tabela acima para definição de senha.

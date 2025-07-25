# Instalação Remota de Aplicativos

Esta funcionalidade permite a instalação de aplicativos remotamente sem que esses aplicativos estejam disponíveis na Play Store. Isso elimina a necessidade de publicação na Play Store, simplificando o processo de distribuição de aplicativos específicos para os dispositivos gerenciados pela empresa. Com essa funcionalidade, os administradores podem instalar diretamente os aplicativos necessários, garantindo uma distribuição mais rápida e eficiente de soluções empresariais personalizadas.&#x20;

É importante que a configuração Política de aplicativos não confiáveis (veja mais informações na Sessão [Segurança](../configuracoes/gerenciar-politicas/editar-politica-android/configuracoes-gerais/seguranca.md)) esteja selecionada para Permitir Instalações de Aplicativos Não Confiáveis, pois caso contrário, o aplicativo não poderá ser instalado.

Para que isso seja possível, o aplicativo deve estar em um servidor com acesso público a uma URL e em um ambiente HTTPS. Se o arquivo não estiver nessas condições, o download do aplicativo não será realizado.

Para gerenciar e enviar a instalação remota de aplicativos para os dispositivos, clique no menu “**Gerenciamento de Aplicativos**” e na opção "**Instalação Remota de Aplicativos**".

<figure><img src="../../../.gitbook/assets/Captura de tela 2024-04-29 140640 (1).png" alt="" width="209"><figcaption></figcaption></figure>

O sistema exibirá uma lista com os aplicativos instalados nos dispositivos da empresa. A tela de exibição dos aplicativos é apresentada a seguir.

<figure><img src="../../../.gitbook/assets/Captura de tela 2024-04-29 141809.png" alt=""><figcaption></figcaption></figure>

1. O sistema exibirá um filtro de período por data.
2. No campo de pesquisa é possível buscar por uma informação específica.
3. Para exportar o relatório dos aplicativos, clique no botão “Excel”.
4. Para copiar as informações dos aplicativos, clique no botão “Copiar”.
5. No campo "Nova Instalação" é possível enviar a instalação remota de um aplicativo para os dispositivos. Para mais detalhes acesse "[Instalar Aplicativo](instalacao-remota-de-aplicativos.md#instalar-aplicativo)" nesta mesma página.
6. A lista de informações dos aplicativos exibe os seguintes detalhes:  Data do Envio, Nome do App, Nome do pacote e URL para download.
7. Ordene a listagem de aplicativos pelas colunas nas setas "↑↓".
8. Ao clicar nos três pontinhos "...",  e clicar em  “Visualizar instalação", é possível acessar a tela “Detalhes de Envio do Aplicativo".

<figure><img src="../../../.gitbook/assets/image (5) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

## Instalar Aplicativo

Para instalar um aplicativo remotamente siga os passos a seguir:

1. Selecione a política ou os usuários de dispositivos vinculados a políticas dos seguintes modos de gerenciamento: Android, Android - Block SIM e Android - Work Profile.  Para enviar para 1 usuário ou mais, selecione os usuários que deseja, ao selecionar a política,  será realizado o envio para todos os usuários vinculados a política, ou ainda se desejar enviar para usuários específicos e para uma política, pode selecionar ambos os campos.
2. Preencha os campos obrigatórios:
   * Nome: este campo deve conter o nome do aplicativo ou serviço
   *   Nome do pacote: deve incluir o identificador único do pacote do aplicativo. Esse nome é utilizado pelo sistema Android para reconhecer o app e deve estar exatamente igual ao nome interno declarado no APK (ex: `com.empresa.nomeapp`).

       > **Importante:** esse nome não é o mesmo que o título do aplicativo exibido no dispositivo.\
       > Para obter o nome do pacote solicite diretamente ao desenvolvedor responsável pelo APK. Inserir um nome de pacote incorreto pode impedir a instalação, fazer com que o aplicativo seja removido automaticamente ou causar falhas na gestão via sistema.


   *   URL para download: é o campo onde deve-se inserir o endereço web (link HTTPS) que aponta diretamente para o arquivo de instalação do aplicativo (ex: `.apk`).

       > Não são aceitos links de compartilhamento, como Google Drive, OneDrive ou Dropbox. \
       > O campo "URL para download" deve conter um link direto (HTTPS) que aponte exatamente para o arquivo de instalação do aplicativo, permitindo que ele seja baixado automaticamente, sem necessidade de interação do usuário.
       >
       > > Exemplo válido: `https://exemplo.com/app/nome-do-app.apk`\
       > > Exemplos inválidos: links como `https://drive.google.com/...` ou `https://dropbox.com/s/...`


3. Clique em "Enviar".&#x20;
4. O Aplicativo de Gestão fara download do app recebido.
5. E solicitará a confirmação do usuário para realizar instalação do app baixado.
6.  E exibirá uma notificação informando que possui um app disponível para a instalação:

    _**Você possui uma instalação pendente! Clique aqui para iniciar**_
7. Após clicar na notificação, a instalação será solicitada novamente.

{% hint style="info" %}
**Observação**

Ao confirmar o envio, o sistema exibirá uma mensagem de sucesso, enviará um push de instalação do app para todos os dispositivos da política e usuários selecionados, solicitando a autorização do usuário e adicionará o pacote do app na política de todos os dispositivos selecionados "Disponível". Ou seja, a instalação não é silenciosa.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (177).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**NOTA**

1. O aplicativo enviado através da instalação remota, é enviado com o tipo de instalação "Disponível", sendo assim, caso o usuário desinstalar o aplicativo, para instalar novamente, o administrador, precisara enviar novamente o comando de instalar aplicativo via portal para o dispositivo.
2. Caso o pacote inserido pelo usuário esteja diferente do pacote do app disponível no link de download:
   * _A Notificação ficará fixa no dispositivo até que o mesmo seja reiniciado_
   * _O App será removido do dispositivo automaticamente pela Google_
{% endhint %}

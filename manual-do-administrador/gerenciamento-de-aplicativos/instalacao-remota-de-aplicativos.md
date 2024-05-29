# Instalação Remota de Aplicativos

Esta tela do sistema tem como objetivo, possibilitar a instalação, desinstalação e atualização remota de aplicativos nos dispositivos da empresa, sem que o aplicativo esteja na Play Store. Para que isso seja possível, o aplicativo deve estar em um servidor com acesso público a uma URL e em um ambiente HTTPS. Se o arquivo não estiver nessas condições, o download do aplicativo não será realizado.

Para gerenciar e enviar a instalação remota de aplicativos para os dispositivos, clique no menu “**Gerenciamento de Aplicativos**” e na opção "**Instalação Remota de Aplicativos**".

<figure><img src="../../.gitbook/assets/Captura de tela 2024-04-29 140640 (1).png" alt=""><figcaption></figcaption></figure>

O sistema exibirá uma lista com os aplicativos instalados nos dispositivos da empresa. A tela de exibição dos aplicativos é apresentada a seguir.

<figure><img src="../../.gitbook/assets/Captura de tela 2024-04-29 141809.png" alt=""><figcaption></figcaption></figure>

1. O sistema exibirá um filtro de período por data.
2. No campo de pesquisa é possível buscar por uma informação específica.
3. Para exportar o relatório dos aplicativos, clique no botão “Excel”.
4. Para copiar as informações dos aplicativos, clique no botão “Copiar”.
5. No campo "Nova Instalação" é possível enviar a instalação remota de um aplicativo para os dispositivos. Para mais detalhes acesse "[Instalar Aplicativo](instalacao-remota-de-aplicativos.md#instalar-aplicativo)" nesta mesma página.
6. A lista de informações dos aplicativos exibe os seguintes detalhes:  Data do Envio, Nome do App, Nome do pacote e URL para download.
7. Ordene a listagem de aplicativos pelas colunas nas setas "↑↓".
8. Ao clicar nos três pontinhos "...",  e clicar em  “Visualizar instalação", é possível acessar a tela “Detalhes de Envio do Aplicativo".

<figure><img src="../../.gitbook/assets/image (176).png" alt=""><figcaption></figcaption></figure>

#### Instalar Aplicativo

Para instalar um aplicativo remotamente siga os passos a seguir:

1. Selecione a política e usuários de dispositivos vinculados a políticas dos seguintes modos de gerenciamento: Android, Android - Block SIM e Android - Work Profile.
2. Preencha os campos obrigatórios: Nome, Nome do pacote e URL para download.
3. Clique em "Enviar".&#x20;
4. O Companion fara download do app recebido.
5. E solicitará a confirmação do usuário para realizar instalação do app baixado.
6.  E exibirá uma notificação informando que possui um app disponível para a instalação:

    _**Você possui uma instalação pendente! Clique aqui para iniciar**_
7. Após clicar na notificação, a instalação será solicitada novamente.

{% hint style="info" %}
**Observação**

Ao confirmar o envio, o sistema exibirá uma mensagem de sucesso, enviará um push de instalação do app para todos os dispositivos da política e usuários selecionados, solicitando a autorização do usuário e adicionará o pacote do app na política de todos os dispositivos selecionados "Disponível". Ou seja, a instalação não é silenciosa.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (177).png" alt=""><figcaption></figcaption></figure>

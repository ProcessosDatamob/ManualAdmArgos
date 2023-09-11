# Informações gerais

O <mark style="background-color:orange;">\<Nome\_Produto></mark>  é uma solução de Gerenciamento de Mobilidade Corporativa composta por:

* **Portal de Administração** <mark style="background-color:orange;">\<Nome\_Produto></mark> - sistema web que realiza toda a gestão dos dispositivos móveis da empresa.
* **Aplicativo** <mark style="background-color:orange;">\<Nome\_Produto></mark> - aplicativo Android que coleta todas as informações de uso e consumos do dispositivo móvel. Este aplicativo é instalado por padrão estando presente em todos os dispositivos que registrados no sistema.
* **Aplicativo Security Browser** - Aplicativo Android de navegação web responsável por realizar os bloqueios de sites, bem como monitorar a navegação do usuário do dispositivo.
* **Aplicação Block SIM -** é responsável pelo bloqueio do chip SIM, impedindo a sua utilização noutro dispositivo.

{% hint style="warning" %}
**IMPORTANTE**

* O aplicativo Security Browser está disponível na Play Store e deve ser incluído na política de registro dos dispositivos. Passo a passo para inclusão e configuração do aplicativo [Security Browser](../bloqueio-de-sites-security-browser.md).
* Para utilizar o bloqueio do chip, ao criar uma nova política deverá ser selecionado o modo de gerenciamento"Android - Block SIM", deste modo o sistema adiciona automaticamente a aplicação Block SIM, restringindo as alterações da senha do dispositivo e garantindo a ligação do chip ao dispositivo. No momento do registro do dispositivo, o usuário deverá seguir as etapas da instalação e conceder as licenças solicitadas. Para mais detalhes sobre o processo de bloqueio do chip use o "Manual de Instalação - Block sim".
{% endhint %}

A partir do <mark style="background-color:orange;">\<Nome\_Produto></mark> é possível acessar as informações sobre o consumo e o uso dos dispositivos alocados aos funcionários de uma empresa. Também é possível definir políticas de bloqueios para restringir o uso indevido dos dispositivos, possibilitando ao administrador avaliar e aumentar a produtividade dos funcionários, através da análise e da gestão dos recursos de telecomunicação da empresa.

**Fluxo dos Dados**

Todas as informações coletadas pelo aplicativo <mark style="background-color:orange;">\<Nome\_Produto></mark> são enviadas periodicamente para os servidores do sistema. As informações são compiladas e consolidadas em 1 hora para serem visualizadas no portal de administração.&#x20;

Os dados de consumo coletados pelo aplicativo são enviados de acordo com o tempo configurado no portal, na opção "Sincronizar cada", que varia de 30 minutos a 24 horas.

**Armazenamento dos Dados**

Todos os dados do Portal permanecem armazenados durante 6 meses, após esse período as informações serão eliminadas dos servidores.

Caso ocorra alguma indisponibilidade nos servidores, o aplicativo manterá as informações até que a comunicação com os servidores seja restabelecida.&#x20;

Todos os dados enviados pelo portal e recebidos pelo dispositivo permanecem armazenados, garantindo que as políticas permaneçam ativas, mesmo quando não possuir acesso à Internet e independente da disponibilidade dos servidores. A conexão será necessária apenas para receber novas políticas ou mensagens e para enviar os dados para o Portal.

**Nível de Acesso ao Portal**

O Portal de Administração possui dois níveis de acesso:

* **Administrador do portal**: esse nível dá acesso total às informações e permite definir políticas de bloqueio para os dispositivos;
* **Administrador de grupo**: este nível dá acesso aos dados do seu grupo e permite enviar mensagens ao grupo;

Para saber como criar um administrador de portal ou grupo, leia a seção “[**Configurações Iniciais e Níveis**](configuracoes-iniciais-e-niveis.md)**'**'.

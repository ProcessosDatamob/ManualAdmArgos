# Aplicativos

A guia de configurações de aplicativos permite gerenciar configurações, permissões, definir o modo de instalação, bem como, incluir e excluir aplicativos.

A tela "Editar política" posicionada na guia "Aplicativos" é apresentada na sequência.

<figure><img src="../../../.gitbook/assets/image (1) (1) (1).png" alt="" width="563"><figcaption></figcaption></figure>

As telas apresentam as seguintes partes, conforme numeração na figura:

1. Modo de seleção dos aplicativos na Play Store - permite controlar como os aplicativos serão exibidos nos dispositivos registrados nesta política. No modo "Restrito", os usuários só podem visualizar e instalar da Google Play Store os aplicativos listados abaixo. Os outros aplicativos serão removidos e não estarão disponíveis nos dispositivos.

{% hint style="info" %}
**NOTA**

Ao selecionar a opção “Aberta” os aplicativos adicionados na política apresentarão o tipo de instalação: Instalação Forçada, pois entende que todos os aplicativos já estão disponíveis.
{% endhint %}

2. Use a caixa de pesquisa para localizar aplicativos dentro da lista exibida.
3. Listagem de aplicativos incluídos.
4. Tipo de instalação - Escolha o tipo de instalação de cada dispositivo. Os tipos de instalação são: disponível, pré-instalado, instalação forçada ou bloqueado.

{% hint style="info" %}
**NOTA**

Importante ressaltar que o tipo de instalação “Pré-Instalado” de um aplicativo, acontece uma única vez no dispositivo. Ou seja: quando um aplicativo é pré-instalado é deletado pelo usuário, ao alterar a política que tenha o mesmo aplicativo com o tipo de instalação “pré-instalado” o aplicativo não será apresentado no dispositivo pois ele já foi removido anteriormente.

Para que o aplicativo seja apresentado no dispositivo com o tipo de instalação “pré-instalado” é necessário realizar o comando “Remover Dispositivo (WIPE)” no portal ou factory reset através do dispositivo”.
{% endhint %}

5. Mais ações ("...") que podem ser realizadas com o aplicativo: Configurações Gerenciadas, Permissões, Configurações Avançadas e Remover Aplicativo.
6. Adicionar Aplicativos - permite adicionar aplicativos para gerenciamento.

{% hint style="warning" %}
**IMPORTANTE**

Os aplicativos precisam ser primeiramente adicionados usando a Google Play Gerenciada. Clique no botão "Adicionar Aplicativos" e a tela a seguir será exibida.
{% endhint %}

![](<../../../.gitbook/assets/7 (3).png>)

Estando a janela "Adicionar aplicativos" aberta, conforme figura anterior, para adicionar aplicativos na política, siga os seguintes passos:

7. Selecione um ou mais aplicativos clicando no checkbox;
8. Clique no botão "Adicionar selecionados".

**Configurações Gerenciadas**

Para acessar as configurações gerenciadas de um aplicativo é necessário estar na tela "Editar Política" com a guia "Aplicativos" selecionada. Siga os seguintes passos:

1. Localize o aplicativo desejado e clique nos três pontinhos, localizados no final da linha, para exibir o menu com mais opções;
2. Clique sobre "Configurações Gerenciadas".

{% hint style="warning" %}
**IMPORTANTE**

O aplicativo Security Browser é o navegador web padrão do sistema <mark style="background-color:orange;">\<NomeProduto></mark> e com ele é possível gerenciar bloqueios de sites por URL e categoria, bem como monitorar a navegação do usuário. Consulte a seção 16, para informações detalhadas sobre a instalação e configuração do aplicativo Security Browser.
{% endhint %}

Após o passo 2 a tela a seguir será exibida. Nesta tela temos os seguintes itens:

3. Identificação do aplicativo selecionado e a tela de configuração que foi escolhida ("Configurações Gerenciadas");
4. Lista de configurações gerenciadas disponíveis para o aplicativo selecionado. Clicando sobre cada linha as configurações são exibidas;
5. Link para voltar para a lista de aplicativos.

![](<../../../.gitbook/assets/9 (2).png>)

**Permissões**

Para acessar as configurações de permissões de um aplicativo é necessário estar na tela "Editar Política" com a guia "Aplicativos" selecionada. Siga os seguintes passos:

1. Localize o aplicativo desejado e clique nos três pontinhos, localizados no final da linha, para exibir o menu com mais opções;
2. Clique sobre "Permissões".

![](<../../../.gitbook/assets/10 (2).png>)

Após o passo 2 a tela a seguir será exibida. A lista de permissões, que podem ser configuradas no aplicativo selecionado, é exibida nesta tela.

![](<../../../.gitbook/assets/11 (1).png>)

As permissões podem ser configuradas como: Solicitar ao usuário, Ativada ou Negada.

**Configurações Avançadas**

Para acessar as configurações avançadas de um aplicativo é necessário estar na tela "Editar Política" com a guia "Aplicativos" selecionada. Siga os seguintes passos:

1. Localize o aplicativo desejado e clique nos três pontinhos, localizados no final da linha, para exibir o menu com mais opções;
2. Clique sobre "Configurações Avançadas".

![](<../../../.gitbook/assets/12 (1).png>)

Após o passo 2 a tela a seguir será exibida. Nesta tela temos os seguintes itens:

* **Prioridade de Atualização** - Defina a prioridade de atualização do aplicativo como pré-definida, postergada ou prioritária.
* **Versão mínima -** permite definir uma versão mínima do aplicativo.

![](<../../../.gitbook/assets/13 (1).png>)

**Remover Aplicativo**

Para excluir um aplicativo da política é necessário estar na tela "Editar Política" com a guia "Aplicativos" selecionada. Siga os seguintes passos:

1. Localize o aplicativo desejado e clique nos três pontinhos, localizados no final da linha, para exibir o menu com mais opções;
2. Clique sobre "Remover Aplicativo".

![](<../../../.gitbook/assets/14 (1).png>)

Após o passo 2 a tela a seguir será exibida para confirmação da exclusão. Clique no botão "Remover" para remover o aplicativo da lista.

![](<../../../.gitbook/assets/15 (1).png>)

{% hint style="info" %}
**OBSERVAÇÃO**

O aplicativo será removido da listagem de aplicativos da política que está sendo editada, porém ele permanecerá nos Aplicativos Gerenciados, pode ser incluído novamente na política e pode fazer parte das configurações de outras políticas.
{% endhint %}

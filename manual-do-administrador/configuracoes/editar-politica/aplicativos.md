# Aplicativos

A guia de configurações de aplicativos permite gerenciar configurações, permissões, definir o modo de instalação, bem como, incluir e excluir aplicativos.

A tela "**Editar política**" posicionada na guia "**Aplicativos**" é apresentada na sequência.

<figure><img src="../../../.gitbook/assets/Captura de tela 2024-02-29 160922.png" alt=""><figcaption></figcaption></figure>

As telas apresentam as seguintes partes, conforme numeração na figura:

1. **Modo de seleção dos aplicativos na Play Store -** permite controlar como os aplicativos serão exibidos nos dispositivos registrados nesta política. No modo "Restrito", os usuários só podem visualizar e instalar da Google Play Store os aplicativos listados abaixo. Os outros aplicativos serão removidos e não estarão disponíveis nos dispositivos.

{% hint style="info" %}
**NOTA**

Ao selecionar a opção “**Aberta**” os aplicativos adicionados na política apresentarão o tipo de instalação: **Instalação Forçada**, pois entende que todos os aplicativos já estão disponíveis.
{% endhint %}

2. Use a caixa de pesquisa para localizar aplicativos dentro da lista exibida.
3. Listagem de aplicativos incluídos.
4. **Tipo de instalação -** Escolha o tipo de instalação de cada dispositivo. Os tipos de instalação são: disponível, pré-instalado, instalação forçada ou bloqueado.

{% hint style="info" %}
**NOTA**

Importante ressaltar que o tipo de instalação “Pré-Instalado” de um aplicativo, acontece uma única vez no dispositivo. Ou seja: quando um aplicativo é pré-instalado é deletado pelo usuário, ao alterar a política que tenha o mesmo aplicativo com o tipo de instalação “pré-instalado” o aplicativo não será apresentado no dispositivo pois ele já foi removido anteriormente.

Para que o aplicativo seja apresentado no dispositivo com o tipo de instalação “pré-instalado” é necessário realizar o comando “Remover Dispositivo (WIPE)” no portal ou factory reset através do dispositivo”.
{% endhint %}

5. Mais ações ("...") que podem ser realizadas com o aplicativo: [Configurações Gerenciadas](aplicativos.md#configuracoes-gerenciadas), [Permissões](aplicativos.md#permissoes), [Configurações Avançadas](aplicativos.md#configuracoes-avancadas) e [Remover Aplicativo](aplicativos.md#remover-aplicativo).
6. **Adicionar Aplicativos -** permite adicionar aplicativos para gerenciamento, para mais informações acessar o conteúdo [Adicionar Aplicativos](aplicativos.md#adicionar-aplicativos) nesta página.
7. **Restrições de funcionamento -**permite criar restrições de acesso aos apps por horário, para que seja possível definir os horários em que os apps não poderão ser acessados. Para mais informações acessar o conteúdo [Restrições de Funcionamento](aplicativos.md#restricoes-de-funcionamento) nesta página.

### **Configurações Gerenciadas**

<mark style="color:red;">Para acessar as configurações gerenciadas de um aplicativo é necessário estar na tela "</mark><mark style="color:red;">**Editar Política**</mark><mark style="color:red;">" com a guia "</mark><mark style="color:red;">**Aplicativos**</mark><mark style="color:red;">" selecionada. Siga os seguintes passos:</mark>

1. <mark style="color:red;">Localize o aplicativo desejado e clique nos três pontinhos "...", localizados no final da linha e clique na opção "</mark><mark style="color:red;">**Configurações Gerenciadas**</mark><mark style="color:red;">".</mark>

<figure><img src="../../../.gitbook/assets/Captura de tela 2024-04-29 150335.png" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">A tela a seguir será exibida:</mark>

<figure><img src="../../../.gitbook/assets/Captura de tela 2024-04-29 150749.png" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">Nesta tela é possível ver a identificação do aplicativo selecionado e a tela de configuração que foi escolhida ("Configurações Gerenciadas");</mark>

2. <mark style="color:red;">Clique no menu “Permissões Opcionais" para acessar a lista de configurações gerenciadas disponíveis para o aplicativo selecionado. Nesse menu é possível ativar e desativar cada uma das configurações.</mark>

<figure><img src="../../../.gitbook/assets/image (109).png" alt=""><figcaption></figcaption></figure>

3. <mark style="color:red;">Ao clicar em "Salvar"</mark> <mark style="color:red;">o sistema</mark> <mark style="color:red;">enviará as configurações selecionadas para os dispositivos.</mark>

### **Permissões**

Para acessar as configurações de permissões de um aplicativo é necessário estar na tela "**Editar Política**" com a guia "**Aplicativos**" selecionada. Siga os seguintes passos:

1. Localize o aplicativo desejado e clique nos três pontinhos, localizados no final da linha, para exibir o menu com mais opções;
2. Clique sobre "**Permissões**".

![](<../../../.gitbook/assets/10 (2).png>)

Após o passo 2 a tela a seguir será exibida. A lista de permissões, que podem ser configuradas no aplicativo selecionado, é exibida nesta tela.

![](<../../../.gitbook/assets/11 (1).png>)

As permissões podem ser configuradas como: Solicitar ao usuário, Ativada ou Negada.

{% hint style="info" %}
<mark style="color:red;">**Observação**</mark>

<mark style="color:red;">Se a opção “Permissões" aparecer desabilitada no sistema, é para evitar que o usuário acesse configurações que não são relevantes para sua função. Visando garantir que o usuário não se confunda ou tente ajustar configurações que não estão dentro de suas atribuições ou necessidades específicas dentro do sistema.</mark>

![](<../../../.gitbook/assets/image (112).png>)
{% endhint %}

### **Configurações Avançadas**

Para acessar as configurações avançadas de um aplicativo é necessário estar na tela "**Editar Política**" com a guia "**Aplicativos**" selecionada. Siga os seguintes passos:

1. Localize o aplicativo desejado e clique nos três pontinhos, localizados no final da linha, para exibir o menu com mais opções;
2. Clique sobre "**Configurações Avançadas**".

![](<../../../.gitbook/assets/12 (1).png>)

Após o passo 2 a tela a seguir será exibida. Nesta tela temos os seguintes itens:

* **Prioridade de Atualização** - Defina a prioridade de atualização do aplicativo como pré-definida, postergada ou prioritária.
* **Versão mínima -** permite definir uma versão mínima do aplicativo.

![](<../../../.gitbook/assets/13 (1).png>)

### **Remover Aplicativo**

Para excluir um aplicativo da política é necessário estar na tela "**Editar Política**" com a guia "**Aplicativos**" selecionada. Siga os seguintes passos:

1. Localize o aplicativo desejado e clique nos três pontinhos, localizados no final da linha, para exibir o menu com mais opções;
2. Clique sobre "**Remover Aplicativo**".

![](<../../../.gitbook/assets/14 (1).png>)

Após o passo 2 a tela a seguir será exibida para confirmação da exclusão. Clique no botão "Remover" para **remover** o aplicativo da lista.

![](<../../../.gitbook/assets/15 (1).png>)

{% hint style="info" %}
**OBSERVAÇÃO**

O aplicativo será removido da listagem de aplicativos da política que está sendo editada, porém ele permanecerá nos Aplicativos Gerenciados, pode ser incluído novamente na política e pode fazer parte das configurações de outras políticas.
{% endhint %}

### **Adicionar Aplicativos**

A opção Adicionar aplicativos terá comportamentos diferentes quando o Modo Quiosque estiver ativado ou desativado.

* **Modo Quiosque Desativado:** Ao clicar no botão "**Adicionar Aplicativos**", caso seja uma política com **Modo Quiosque Desativado**, será exibida a listagem de aplicativos que foram  na adicionados usando a [**Google Play Gerenciada**](../../gerenciamento-de-aplicativos/google-play-gerenciada.md).&#x20;
* **Modo Quiosque Ativado:** Caso a política que estiver sendo editada for uma política com o **Modo Quiosque** **Ativado**, ao clicar no botão **Adicionar aplicativos**, aparecerão 3 opções para adicionar os aplicativos.

<figure><img src="../../../.gitbook/assets/image (69).png" alt=""><figcaption></figcaption></figure>

* **Sistema**

1. Clique na opção “**Sistema"**, e abrirá a tela “**Aplicativos do sistema**"
2. Selecione a Fabricante e o Dispositivo
3. Selecione um ou mais aplicativos clicando no checkbox
4. Clique no botão "**Adicionar selecionados**"

<figure><img src="../../../.gitbook/assets/image (70).png" alt=""><figcaption></figcaption></figure>

* **Playstore**&#x20;

1. Clique na opção “**Playstore**", e abrirá a tela “**Adicionar Aplicativos**"
2. Selecione um ou mais aplicativos clicando no checkbox
3. Clique no botão "**Adicionar selecionados**"

<figure><img src="../../../.gitbook/assets/image (71).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
**IMPORTANTE**

Os aplicativos precisam ser primeiramente adicionados usando a **Google Play Gerenciada**.&#x20;
{% endhint %}

* **Manual**

1. Clique na opção “**Manual**", e abrirá a tela “**Adicionar Aplicativos Manualmente**"
2. Preencha os campos: Nome do App (opcional), Nome do Pacote e clicar em "**Adicionar**"

<figure><img src="../../../.gitbook/assets/image (72).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**OBSERVAÇÃO**

Ao criar uma política com modo de gerenciamento Android Block SIM, automaticamente na aba APLICATIVOS, já estará adicionado o aplicativo Block SIM com modo de instalação Forçada, ou seja, quando o usuário realizar a ativação do Vivo Gestão Dispositivo utilizando esta política, já será instalado automaticamente o Block SIM, sem que ele precise baixar na Play Store.
{% endhint %}

### Restrições de Funcionamento

Para definir restrições de funcionamento de aplicativos por dias e horários, é necessário clicar no icone de restrições de funcionamento na linha referente ao aplicativo desejado. A imagem a seguir destaca:&#x20;

1. Ícones para acessar a opção "Restrições de Funcionamento";&#x20;
2. Botão seletor para ativar restrições.

A opção de "Restrições de Funcionamento" está disponível para todos os aplicativos, exceto: aplicativo do sistema \<nome\_produto>, Kiosk Launcher, Block Sim e Remote View.  Quando o aplicativo já possui restrição de funcionamento, o seu ícone de restrição de funcionamento mudará para ![](<../../../.gitbook/assets/image (79).png>).

<figure><img src="../../../.gitbook/assets/Captura de pantalla 2024-03-07 a la(s) 15.51.55.png" alt=""><figcaption></figcaption></figure>

Para ativar as restrições:

1. Selecione o campo “Ativar restrições".
2. Informe o horário de inicio e fim do período para cada dia, ou selecione o campo "Restringir"  para bloquear o funcionamento o dia inteiro.
3. Clique em "Confirmar" para salvar as alterações. A política enviará as informações de restrições do aplicativo para os dispositivos vinculados<mark style="color:purple;">.</mark>

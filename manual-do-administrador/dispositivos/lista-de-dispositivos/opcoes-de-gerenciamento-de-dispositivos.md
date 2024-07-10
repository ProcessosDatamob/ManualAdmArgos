---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Opções de gerenciamento de dispositivos

Na tela de "**Dispositivos**" dentro de "**Lista de Dispositivos**" é possível ter acesso as informações do dispositivo, clicando no botão de **Mais informações**:

<figure><img src="../../../.gitbook/assets/Captura de tela 2024-06-24 114339.png" alt=""><figcaption></figcaption></figure>

Após clicar no ícone acima, será exibida a seguinte tela, onde teremos acesso as Informações do dispositivo:

<figure><img src="../../../.gitbook/assets/image (4) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Detalhes

* **Usuário -** nome do usuário cadastrado no portal;
* **Identificação -** Identificação cadastrada para o dispositivo;
* **Grupo -** grupo cadastrado para o dispositivo**;**
* **Departamento** - É um campo de texto livre, ou seja, o administrador pode digitar o que desejar. Indica a unidade ou departamento da organização ao qual o dispositivo está atribuído;
* **Telefone do Usuário** - É um campo de texto livre, ou seja, o administrador pode digitar o que desejar. Indica o número de telefone associado ao usuário do dispositivo;
* **IMEI -** número interno e único em cada dispositivo. No Android 10 já não é possível capturar esta informação do dispositivo porque utilizamos outro método para receber esta informação com o Enriquecimento de URL;
* **ICCID -** número do chip SIM;
* **Número de série -** número de série do dispositivo;
* <mark style="color:blue;">**L**</mark>**icença -** número da Licença;
* **Modelo -** modelo do dispositivo;
* **Fabricante** - nome do fabricante do dispositivo;
* **Sistema Operacional -** sistema operacional do dispositivo;
* **Versão do Android** - versão do Android do dispositivo;
* **Senha de Acesso Temporário** - Esta senha temporária, é gerada ao ativar a Configuração ["Acesso Temporário ao Dispositivo"](../../configuracoes/editar-politica/modo-quiosque.md) no Modo Quiosque. A senha deverá ser fornecida ao usuário do dispositivo e será atualizada no portal a cada 5 minutos,  com opção de copiar e exibição do tempo restante até a senha expirar. Sendo assim, caso foi definido o tempo de 10 minutos para o usuários acessar o dispositivo, caso ultrapasse esses 10 minutos, ele não conseguirá utilizar a mesma senha, pois ela já terá atualizado. No dispositivo, com a senha em mãos, o usuário deverá acessar as **Configurações Iniciais**, clicar na opção **Acesso Temporário** e digitar a senha no campo **"Código"**.

<figure><img src="../../../.gitbook/assets/image (196).png" alt=""><figcaption></figcaption></figure>

### Instalação

* **Status Aplicado -** status do registro do dispositivo, se o dispositivo está totalmente registrado, o status será "Ativo";
* **Data de Registro -** data de registro dos dispositivos;
* **Modo de gerenciamento -** exibe o modo de gerenciamento utilizado;
* **Versão do app -** versão do companion instalado no dispositivo;
* **Nome da Política no Portal** **-** nome da política atribuída ao dispositivo;
* **Nome da Política no Dispositivo -** nome da política atribuída no dispositivo;
* **Versão da política Aplicada -** versão da política;
* **Data de sincronização da Política -** exibirá a data da sincronização da política;
* **Em conformidade -** é a aderência do dispositivo a todas as configurações de políticas atribuídas a ele. Se alguma configuração não foi aplicada, o valor desta opção será "Não".&#x20;
* **Data da Última Comunicação -** exibirá a data em que o dispositivo se comunicou a última vez com o portal;

### Hardware

* **Armazenamento Interno -** quanto de armazenamento interno possui;
* **Bateria -** Quantos % de bateria está no momento;

### Permissões

* **Acesso ao Dados de Uso -** status sim ou não, caso o usuário não ative esta permissão, o aplicativo não irá capturar as consumos de dados e tempo de uso dos aplicativos.
* **Ignorar Otimização de Bateria -** status sim ou não, caso o usuário não ative esta permissão, o aplicativo poderá ser afetado pelas configurações de otimização de bateria, parar de capturar as localizações do dispositivos e parar de enviar as informações para o Portal.
* **Escrita de Configurações do Sistema -** status sim ou não, caso o usuário não ative esta permissão, o aplicativo Kiosk Launcher Manage**r** não permitirá que o usuário alterar algumas configurações do sistema quando estiver no modo Quiosque.
* **Leitura de SMS -** status sim ou não, caso o usuário não ative esta permissão, o aplicativo não irá capturar as informações dos SMS enviados.

### Conectividade

* <mark style="color:blue;">**T**</mark>**ipo da rede conectada (Wi-Fi/Móvel)** - indica se o dispositivo está conectado via Wi-Fi ou rede móvel.
* **Largura de Banda (Móvel)** - a largura de banda disponível para a rede móvel.
* **Largura de Banda (WiFi)** - a largura de banda disponível para a rede Wi-Fi.
* **Latência -** o tempo que leva para um pacote de dados viajar de sua origem até seu destino e voltar.
* **Configuração de Banda** - configuração específica da banda de frequência utilizada.
* **Rede WiFi conectada** - nome da rede Wi-Fi à qual o dispositivo está conectado.
* **Força de sinal** - a intensidade do sinal da rede conectada.
* **WiFi Roaming -** é a capacidade do dispositivo de se conectar automaticamente a diferentes pontos de acesso Wi-Fi dentro da mesma rede sem perder a conexão.
* **Frequência da banda WiFi** - frequência utilizada pela rede Wi-Fi (por exemplo, 2.4 GHz ou 5 GHz).
* **Velocidade do Link WiFi** - velocidade de conexão com a rede Wi-Fi.
* **Endereço MAC WiFi** - endereço MAC do adaptador Wi-Fi do dispositivo.
* **IP (Wi-Fi Network)** - endereço IP atribuído ao dispositivo na rede Wi-Fi.
* **IPv6 (Wi-Fi Network)** - endereço IPv6 atribuído ao dispositivo na rede Wi-Fi.
* **Rede BSSID** - identificador único da rede Wi-Fi.
* **Operadora da Rede Conectada** - nome da operadora da rede móvel conectada.
* **Roaming Dados Móveis** - indica se o dispositivo está em roaming de dados móveis.
* **IP (Rede móvel)** - endereço IP atribuído ao dispositivo na rede móvel.
* **IPv6 (Rede móvel)** - endereço IPv6 atribuído ao dispositivo na rede móvel.
* **SIM Conectado** - indica qual SIM está ativo e conectado.
* **Operadora do SIM 1** - nome da operadora do primeiro SIM.
* **Número de Telefone SIM 1** - número de telefone associado ao primeiro SIM.
* **ICCID SIM 1** - identificador exclusivo do cartão SIM 1.
* **IMEI SIM 1** - número de Identificação Internacional de Equipamento Móvel do SIM 1.
* **Número do Assinante SIM 1** - número do assinante associado ao SIM 1.
* **MCC do SIM 1** - código do país móvel do SIM 1.
* **MNC do SIM 1** - código da rede móvel do SIM 1.
* **Operadora do SIM 2** - nome da operadora do segundo SIM.
* **Número de Telefone SIM 2** - número de telefone associado ao segundo SIM.
* **ICCID SIM 2** - identificador exclusivo do cartão SIM 2.
* **IMEI SIM 2** - número de Identificação Internacional de Equipamento Móvel do SIM 2.
* **Número do Assinante SIM 2** - número do assinante associado ao SIM 2.
* **MCC do SIM 2** - código do país móvel do SIM 2.
* **MNC do SIM 2** - código da rede móvel do SIM 2.
* **DBM (RSRP - Potencia da Antena)** - medida da potência do sinal da antena.
* **Cell ID** - identificação da célula à qual o dispositivo está conectado.
* **LAC** - código de Área Local.
* **Tecnologia da Antena** - tipo de tecnologia de antena utilizada.

E clicando nos três pontinhos "**...**" à direita na listagem dos dispositivos, aparecem as opções de consulta e configurações do dispositivo, como ilustrado na imagem abaixo:

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

As opções disponíveis variam de acordo com o Modo de Gerenciamento da política na qual o dispositivo estiver vinculado e estão em destaque na imagem a seguir:

<table><thead><tr><th width="272.28506787330315">Modo de Gerenciamento</th><th>Opções disponíveis</th></tr></thead><tbody><tr><td><strong>Android</strong></td><td>Relatório de Não Conformidade<br>Alterar Política<br>Ativar/ Desativar Dispositivo<br>Desligar Tela<br>Reiniciar Dispositivo<br>Gerar Nova Senha do Dispositivo<br>Remover Dispositivo (WIPE)<br>Gerenciar Informações</td></tr><tr><td><strong>Android Block SIM</strong></td><td><p>Relatório de Não Conformidade<br>Alterar Política<br>Ativar/Desativar Dispositivo<br>Desligar Tela<br>Reiniciar Dispositivo</p><p>Gerar Nova Senha do Bloqueio de Tela<br>Remover Bloqueio de Tela</p><p>Remover Bloqueio de Chip<br>Remover Dispositivo (WIPE)<br>Gerenciar </p></td></tr><tr><td><strong>Android Work Profile</strong></td><td>Relatório de Não Conformidade<br>Alterar Política<br>Remover Dispositivo (WIPE)<br>Gerenciar </td></tr></tbody></table>

As opções que estão em destaque na figura são detalhadas nas próximas subseções:

### **Relatório de Não Conformidade**

Para exibir as inconsistências em configurações atribuídas ao dispositivo utilize a opção "**Relatório de Não conformidade**".

<figure><img src="../../../.gitbook/assets/image (4) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

No “Relatório de Não Conformidade" é possível "Exportar" e "Copiar", permitindo exportar as informações do relatório para um arquivo Excel ou copiar as informações para uma área de transferência.

### **Alterar Política**

Ao escolher a opção **Alterar Política**, aparecerá no centro da tela uma caixa de diálogo para a escolha da política a ser atribuída ao dispositivo. Escolha a política entre as políticas listadas e clique em atualizar para mudar a política do dispositivo.

A política define configurações, incluindo critérios de hardware, software, sistema operacional, segurança etc. Para saber mais sobre Políticas, leia a seção de configurações deste manual.

<figure><img src="../../../.gitbook/assets/image (110).png" alt=""><figcaption></figcaption></figure>

### **Desativar Dispositivo**

Ao enviar o comando **Desativar Dispositivo**, todos os aplicativos que não são Google serão desativados, serão permitidas chamadas telefônicas e o status do dispositivo muda para desativado. Para desativar um dispositivo utilize a opção "**Desativar Dispositivo**" no menu de opções do dispositivo. Esta opção aparece somente para dispositivos que estão no status "**Ativo**". Uma tela de confirmação será exibida conforme apresentado abaixo.

<figure><img src="../../../.gitbook/assets/image (111).png" alt=""><figcaption></figcaption></figure>

Clique no botão "**Desativar**" para confirmar a operação.

### **Ativar Dispositivo**

Esta opção aparece somente para dispositivos que estão no status "**Desabilitado**". Para ativar um dispositivo desabilitado clique em "**Ativar Dispositivo**" nas opções de gerenciamento do dispositivo.

Confirme a atualização clicando em "**Ativar**" na caixa de diálogo, conforme apresentado na sequência.

### **Desligar Tela do dispositivo**

A opção "**Desligar Tela**" envia um comando para desligar a tela do dispositivo. Ao clicar na opção "**Desligar Tela**" o comando é executado diretamente e uma mensagem aparecerá na tela para informar que o comando foi enviado ao dispositivo.

### **Reiniciar Dispositivo**

Esta operação envia um comando para reiniciar o dispositivo. Escolha a opção "**Reiniciar Dispositivo**". Uma mensagem é exibida na tela do portal para confirmar o envio do comando. A mensagem exibida é mostrada abaixo.

<figure><img src="../../../.gitbook/assets/image (112).png" alt=""><figcaption></figcaption></figure>

### **Gerar nova senha do Bloqueio de Tela**

<mark style="color:blue;">Esta opção permite ao administrador configurar a senha do bloqueio de tela do Block SIM para permitir a alteração remota da senha. Na Lista de Dispositivos, clique na opção “Gerar Nova Senha do Bloqueio de Tela", preencha e confirme a nova senha do Bloqueio de Tela, utilizando letras, números e símbolos. Confirme a alteração da senha, e ao confirmar, o comando será enviado via push ao Companion para aplicação no dispositivo.</mark>

### **Remover Bloqueio de Tela**

Esta operação envia um comando para remover o bloqueio de tela do dispositivo. Escolha a opção "**Remover Bloqueio de Tela**". Uma mensagem é exibida na tela do portal para confirmar o envio do comando.

{% hint style="info" %}
**OBSERVAÇÃO**

Esta opção só ficará disponível para dispositivos ativados com política em modo de gerenciamento Android Block SIM.
{% endhint %}

### **Remover Bloqueio de Chip**

Esta opção permite que o administrador envie um comando para remover o bloqueio de chip (SIM) de um dispositivo, liberando o acesso do usuário ao dispositivo.&#x20;

Na tela "Lista de Dispositivos", selecione a política “Android - Block SIM” e a opção "Remover Bloqueio de Chip", o sistema exibirá uma mensagem de confirmação para o envio da remoção do bloqueio de chip, permitindo confirmar ou cancelar. Após enviar o comando de remoção, o dispositivo receberá um push com o comando, o aplicativo Companion capturará o comando e enviará para o Block SIM, completando a remoção do bloqueio.

### **Gerar nova senha do dispositivo**

O sistema permite que seja gerada uma nova senha para o dispositivo. Para realizar esta operação, escolha a opção "**Gerar Nova Senha do Dispositivo**" conforme mostrado na imagem apresentada na sequência.

Preencha os campos "**Nova Senha**" e "**Confirmar nova senha**" com valores iguais para que o botão "**Confirmar**" esteja habilitado. Opcionalmente, e conforme a necessidade, poderão ser marcadas as opções:

* Não pedir credenciais de usuário na inicialização do dispositivo;
* Bloquear o dispositivo após a redefinição da senha.

A tela para gerar nova senha do dispositivo é mostrada a seguir.

<figure><img src="../../../.gitbook/assets/image (113).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**OBSERVAÇÃO**

Ao selecionar a opção "Não pedir credenciais de usuário na inicialização do dispositivo", a senha não será solicitada durante o processo de inicialização. A senha será necessária apenas para desbloquear a tela do dispositivo.

**Inicialização Segura (Secure Boot)**: a senha solicitada na inicialização é uma medida de segurança implementada pelo Secure Boot. Esta funcionalidade protege o processo de inicialização contra ataques de segurança provenientes de códigos mal-intencionados, como malware e ransomware.
{% endhint %}

### **Remover Dispositivo (WIPE)**

Esta operação permite excluir um dispositivo, ela limpa os dados e configurações do dispositivo. Os dispositivos excluídos não aparecem na lista de dispositivos da empresa. A opção "Remover Dispositivo" aparece na lista de opções do dispositivo na tela de listagem de dispositivos (menu "Dispositivos", opção "Listar Dispositivos").

{% hint style="info" %}
**NOTA**

Uma mensagem é exibida na tela para informação e advertência. A operação não pode ser desfeita, portanto, confirme somente quando tiver certeza de que deseja eliminar o dispositivo.
{% endhint %}

## **Gerenciar**

Ao clicar na opção **Gerenciar**, será exibida a tela "**Gerenciar Dispositivo**", onde teremos 4 abas com opções para edição e informações do dispositivo, são elas: **Detalhes, Aplicativos, Bateria e Armazenamento Livre.**&#x20;

## **Detalhes**

Ao abrir a tela acima, a primeira aba "**Detalhes**" vira Pré selecionada, nesta tela, é possível editar dados do dispositivo, como: Usuário, Identificação, Grupo, Departamento e Telefone do Usuário.

<figure><img src="../../../.gitbook/assets/image (205).png" alt=""><figcaption></figcaption></figure>

Além de poder editar os dados, são exibidos mais abaixo duas listas com as informações de Software, Hardware e Conectividade relacionados ao dispositivo gerenciado.

<figure><img src="../../../.gitbook/assets/Captura de tela 2024-06-26 120244 (3).png" alt=""><figcaption></figcaption></figure>

#### **Informações de Software**

* **Modo de gerenciamento -** exibe o modo de gerenciamento utilizado
* **Versão do app -** versão do companion instalado no dispositivo
* **Número de Série -** número de série do dispositivo;
* **Em Conformidade -** é a aderência do dispositivo a todas as configurações de políticas atribuídas a ele. Se alguma configuração não foi aplicada, o valor desta opção será "Não".&#x20;
* **Status Aplicado -** status do registro do dispositivo, se o dispositivo está totalmente registrado, o status será "Ativo";
* **Data da última atualização -** data e hora em que as informações do dispositivo foram sincronizadas com o portal. Esta data vem da AMAPI (API da Google), ou seja, são as informações coletadas pela API da Google no dispositivo;
* **Data de Sincronização da Política -**exibirá a data da sincronização da política;
* **Versão do Android -** versão do Android do dispositivo;
* **Versão da Política Aplicada** - versão da política;
* **Nome da Política no Portal** - nome da política atribuída ao dispositivo;
* **Nome da Política no Dispositivo -** nome da política atribuída no dispositivo;

#### **Informações de Hardware**

* **Armazenamento Interno -** quanto de armazenamento interno possui;
* **Bateria -** Quantos % de bateria está no momento;

#### Conectividade

As informações de conectividade já foram detalhadas acima , na sessão "Informações do Dispositivo"

## **Aplicativos**

Na aba "**Aplicativos**", é possível acessar a lista de todos os aplicativos instalados no dispositivo, contendo as seguintes informações: ícone, nome, consumo e tempo de uso. Os dados de consumo e tempo de uso são registrados dentro do ciclo. É possível pesquisar um aplicativo específico utilizando o campo de pesquisa, exportar relatórios completos ou da página, além de copiar as informações da lista. A aba também permite visualizar o gráfico de "Histórico de Consumo" do aplicativo durante o ciclo.

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

## **Bateria**

Na aba "**Bateria**", é possível selecionar uma data para visualizar as informações desejadas. Ao escolher a data, o sistema buscará e exibirá os dados da bateria em formato de gráfico.

<figure><img src="../../../.gitbook/assets/image (206).png" alt=""><figcaption></figcaption></figure>

## **Armazenamento Livre**

Na aba "**Armazenamento Livre**" é possível visualizar a memória livre no armazenamento interno do dispositivo ao selecionar uma data para visualizar as informações desejadas. Ao escolher a data, o sistema buscará e exibirá os dados de armazenamento em formato de gráfico.

<figure><img src="../../../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

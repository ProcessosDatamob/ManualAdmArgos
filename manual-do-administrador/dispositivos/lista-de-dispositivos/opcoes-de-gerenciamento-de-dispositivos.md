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

<mark style="color:red;background-color:orange;">NOVA IMAGEM</mark>

<figure><img src="../../../.gitbook/assets/Captura de tela 2024-06-24 114339.png" alt=""><figcaption></figcaption></figure>

Após clicar no ícone acima, será exibida a seguinte tela, onde teremos acesso as Informações do dispositivo:

<figure><img src="../../../.gitbook/assets/image (4) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Detalhes

* **Usuário -** nome do usuário cadastrado no portal;
* **Identificação -** Identificação cadastrada para o dispositivo;
* **Grupo -** grupo cadastrado para o dispositivo**;**
* **Departamento** - É um campo de texto livre, ou seja, o administrador pode digitar o que desejar. Indica a unidade ou departamento da organização ao qual o dispositivo está atribuído;
* **Telefone do Usuário** - É um campo de texto livre, ou seja, o administrador pode digitar o que desejar. Indica o número de telefone associado ao usuário do dispositivo;
* **IMEI -** número interno e único em cada dispositivo. No Android 10 já não é possível capturar esta informação do dispositivo porque utilizamos outro método para receber esta informação com o Enriquecimento de URL;
* **ICCID -** número do chip SIM;
* **Número de série -** número de série do dispositivo;
* **Telefone -** número de telefone;
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

E clicando nos três pontinhos "**...**" à direita na listagem dos dispositivos, aparecem as opções de consulta e configurações do dispositivo, como ilustrado na imagem abaixo:

<figure><img src="../../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

As opções disponíveis variam de acordo com o Modo de Gerenciamento da política na qual o dispositivo estiver vinculado e estão em destaque na imagem a seguir:

<mark style="color:red;">HISTORICO DE ARMAZENAMENTO REMOVIDO DA TABELA</mark>

<mark style="color:red;">HISTORICO E BATERIA REMOVIDO DA TABELA</mark>

<table><thead><tr><th width="272.28506787330315">Modo de Gerenciamento</th><th>Opções disponíveis</th></tr></thead><tbody><tr><td>Android</td><td>Relatório de Não Conformidade<br>Alterar Política<br>Ativar/ Desativar Dispositivo<br>Desligar Tela<br>Reiniciar Dispositivo<br>Gerar Nova Senha do Dispositivo<br>Remover Dispositivo (WIPE)<br>Gerenciar Informações</td></tr><tr><td>Android Block SIM</td><td><p></p><p>Relatório de Não Conformidade<br>Alterar Política<br>Ativar/Desativar Dispositivo<br>Desligar Tela<br>Reiniciar Dispositivo<br>Remover Bloqueio de Tela<br>Remover Dispositivo (WIPE)<br>Gerenciar </p></td></tr><tr><td>Android Work Profile</td><td>Relatório de Não Conformidade<br>Alterar Política<br>Remover Dispositivo (WIPE)<br>Gerenciar </td></tr></tbody></table>

As opções que estão em destaque na figura são detalhadas nas próximas subseções:

<mark style="color:red;">CONTEUDO HISTÓRICO DE BATERIA REMOVIDO</mark>

<mark style="color:red;">CONTEUDO HISTÓRICO DE  ARMAZENAMENTO REMOVIDO</mark>

### **Relatório de Não Conformidade**

Para exibir as inconsistências em configurações atribuídas ao dispositivo utilize a opção "**Relatório de Não conformidade**".

<figure><img src="../../../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

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

### **Remover Bloqueio de Tela**

Esta operação envia um comando para remover o bloqueio de tela do dispositivo. Escolha a opção "**Remover Bloqueio de Tela**". Uma mensagem é exibida na tela do portal para confirmar o envio do comando.

{% hint style="info" %}
**OBSERVAÇÃO**

Esta opção só ficará disponível para dispositivos ativados com política em modo de gerenciamento Android Block SIM.
{% endhint %}

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

### **Gerenciar**

<mark style="color:red;">Ao entrar na tela o sistema exibira a tela diretamente na aba "Detalhes", onde é possível</mark> editar dados do dispositivo, como: Usuário, Identificação, Grupo, Departamento e Telefone do Usuário.

<figure><img src="../../../.gitbook/assets/image (205).png" alt=""><figcaption></figcaption></figure>

Além de poder editar os dados, são exibidos mais abaixo duas listas com as informações de Software e Hardware relacionados ao dispositivo gerenciado.

<figure><img src="../../../.gitbook/assets/image (191).png" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">Na aba "</mark><mark style="color:red;">**Aplicativos**</mark><mark style="color:red;">", é possível acessar a lista de todos os aplicativos instalados no dispositivo, contendo as seguintes informações: ícone, nome, consumo e tempo de uso. Os dados de consumo e tempo de uso são registrados dentro do ciclo. É possível pesquisar um aplicativo específico utilizando o campo de pesquisa, exportar relatórios completos ou da página, além de copiar as informações da lista. A aba também permite visualizar o gráfico de "Histórico de Consumo" do aplicativo durante o ciclo.</mark>

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">Na aba "</mark><mark style="color:red;">**Bateria**</mark><mark style="color:red;">", é possível selecionar uma data para visualizar as informações desejadas. Ao escolher a data, o sistema buscará e exibirá os dados da bateria em formato de gráfico.</mark>

<figure><img src="../../../.gitbook/assets/image (206).png" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">Na aba "</mark><mark style="color:red;">**Armazenamento Livre**</mark><mark style="color:red;">" é possível visualizar a memória livre no armazenamento interno do dispositivo ao selecionar uma data para visualizar as informações desejadas. Ao escolher a data, o sistema buscará e exibirá os dados de armazenamento em formato de gráfico.</mark>

<figure><img src="../../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

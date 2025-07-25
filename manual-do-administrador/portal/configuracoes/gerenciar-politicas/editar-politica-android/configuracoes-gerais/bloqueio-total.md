# Bloqueios

Essa funcionalidade permite ao usuário administrador configurar um bloqueio por velocidade, bloqueio total do dispositivo fora de um período de tempo específico, ao atingir o limite de dados móveis ou bloquear o dispositivo quando ele estiver fora de uma localização configurada. Assim, permitindo que seja realizado o bloqueio do dispositivo quando o usuário não estiver no horário de trabalho e quando o limite de dados móveis definido para o ciclo atual é atingido.

Estando na aba "**Configurações**" da tela "**Editar Políticas**", clique em "**Bloqueios**" para ver as opções de configuração.

<figure><img src="../../../../../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

### Bloqueio de Aplicativos por Velocidade

Essa funcionalidade permite bloquear o uso de determinados aplicativos com base na velocidade em que o dispositivo está se deslocando. O objetivo é aumentar a segurança, impedindo o uso de aplicativos enquanto o dispositivo estiver em movimento (por exemplo, durante a condução de um veículo).

#### **Como Configurar no Portal**

1. Acesse a edição de uma política Android ou Android - Block SIM.
2. Vá até a aba "Configurações" e abra o opção "Bloqueios".
3. Ative a opção "Ativar bloqueio por velocidade".

{% hint style="info" %}
**IMPORTANTE**

* Para funcionar corretamente, a política deve ter a **configuração de localização ativada**.
* O uso contínuo da localização pode aumentar o consumo de bateria, sendo recomendável manter o dispositivo **conectado ao carregador**.
{% endhint %}

4. Defina os seguintes parâmetros:

* **Velocidade de início do bloqueio**: valor em que o bloqueio será ativado (padrão: 20 km/h).
* **Unidade de Medida**: km/h, mph (milhas por hora) ou m/s.
* **Tempo de espera**: intervalo, em minutos (1 a 10), para verificar se a velocidade se mantém antes de aplicar ou remover o bloqueio.

5. Salve a política para enviar as configurações ao dispositivo.

#### **Selecionando os Aplicativos a Serem Bloqueados**

1. Acesse a aba **"Aplicativos"** da política.
2. Será exibida a coluna **"Bloqueio por Velocidade"** na lista de apps.
3. Ative o bloqueio individualmente para os aplicativos desejados.\
   **Observação:** Não é possível ativar para os apps: **Argos+, Kiosk Launcher e Block SIM**.

#### **Como Funciona no Dispositivo**

* **Quando a velocidade atinge ou ultrapassa o limite configurado:**
  * O sistema inicia a contagem do tempo de espera.
  * Se a velocidade continuar acima após esse tempo:
    * O aplicativo bloqueado será ocultado.
      * O usuário não poderá utilizá-lo de nenhuma forma.
* **Quando a velocidade cai abaixo do limite:**
  * O sistema novamente inicia o tempo de espera.
  * Se a velocidade continuar abaixo após esse tempo:
    * O aplicativo será exibido novamente.
      * O uso será liberado conforme a política.

### Bloqueio fora do Horário de Trabalho

Para realizar o bloqueio de dispositivos fora do horário de trabalho, siga os passos a seguir:

{% hint style="warning" %}
**IMPORTANTE**

Ao ativar o bloqueio fora do horário de trabalho para um aplicativo com o tipo de instalação “Instalação Forçada” a funcionalidade poderá gerar um consumo adicional de dados no dispositivo, pois causa um conflito de políticas, forçando o download do aplicativo sempre que o mesmo for desbloqueado. Por essa razão, antes de ativar o bloqueio fora do horário de trabalho é recomendável alterar o tipo de instalação dos aplicativos de “Instalação Forçada” para "Disponível" ou "Pré-instalado”, evitando esse consumo adicional.
{% endhint %}

1. Ative a opção "Bloquear dispositivo fora do horário de trabalho".
2. Preencha o campo "Dias de trabalho", com os dias trabalhados na semana dia de início e dia fim.
3. Preencha o campo "Horário de trabalho", com horário de trabalho inicial e final.

<figure><img src="../../../../../../.gitbook/assets/image (317) (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**OBSERVAÇÃO**

Ao deixar os campos em branco o sistema considera o período inteiro do dia.
{% endhint %}

Quando o dispositivo estiver fora horário de trabalho configurado, o Argos+ ocultará todos aplicativos do dispositivo, exceto o "_**Telefone**_", o “_**Argos+**_" e a _“**Play Store**"._

Os aplicativos instalados no dispositivo serão apenas ocultados e exibirá uma notificação fixa no dispositivo com a seguinte mensagem: “Acesso aos apps bloqueado pelo administrador“

Sendo assim, quando o dispositivo estiver fora do horário de trabalho configurado, não será permitido acessar os aplicativos ocultados, porém, permitirá acessar as configurações do dispositivo e será permitido desligar ou reiniciar o dispositivo.

Quando o dispositivo estiver dentro do horário de trabalho configurado, todos os aplicativos voltam a ser exibidos, sem a necessidade de instalar novamente.

### Bloqueio Limite de Dados

Para ativar o bloqueio do dispositivo por limite de uso dos dados móveis, habilite a opção "Bloquear dispositivo por limite de uso dos dados móveis".

Quando o dispositivo atingir o limite de uso dos dados móveis configurados para o ciclo atual, o Argos+ ocultará todos os aplicativos do dispositivo, exceto o "Telefone", o "Aplicativo de Gestão" e a "Play Store".

O dispositivo exibirá uma notificação fixa com a mensagem: "_Acesso aos apps bloqueado pelo administrador_". Esta notificação informará ao usuário sobre o bloqueio.

Sendo assim, quando o dispositivo estiver bloqueado por limite de uso de dados, os aplicativos ocultados não poderão ser acessados, porém continuarão instalados, o usuário ainda poderá acessar as configurações do dispositivo e será possível desligar ou reiniciar o dispositivo.

Além disto, ao realizar a instalação de um app via Play Store ou remotamente, o aplicativo será ocultado.

Caso o uso de dados móveis estiver abaixo do limite ou se o administrador desativar a configuração "Bloquear dispositivo por limite de uso dos dados móveis" na política, então o Argos+ exibirá corretamente todos aplicativos do dispositivo conforme política provisionada.

Se o dispositivo estiver em qualquer uma das condições que requerem a ativação de um Bloqueio Total (fora do horário de trabalho ou atingindo o limite de dados móveis). A configuração e ativação de um Bloqueio Total não anula ou interfere com a configuração e ativação do outro. Ambos os bloqueios podem coexistir e serem aplicados conforme suas respectivas condições.

### Bloquear dispositivo fora da localidade

Para ativar o bloqueio total do dispositivo ao sair de uma localidade específica, habilite a opção **"Bloquear dispositivo fora da localidade"** na política configurada.

Quando o dispositivo estiver fora do raio da localidade definida, o sistema ocultará todos os aplicativos, widgets e atalhos, exceto os seguintes: Telefone, Argos+ e Play Store.

O dispositivo exibirá uma notificação fixa com a mensagem: **"Acesso aos apps bloqueado pelo administrador"**, informando ao usuário sobre o bloqueio. Mesmo bloqueado, será possível acessar as configurações do dispositivo, desligá-lo ou reiniciá-lo. Os aplicativos permanecerão instalados, mas inacessíveis.

**Desbloqueio Automático: o** dispositivo será desbloqueado automaticamente quando:

* Retornar ao raio da localidade configurada.
* A configuração **"Bloquear dispositivo fora da localidade"** for desativada na política.
* Não houver mais localidade configurada para o dispositivo.

Ao desbloquear, todos os aplicativos e funcionalidades serão restaurados conforme as políticas provisionadas.

**Pré-requisitos: p**ara o funcionamento correto dessa funcionalidade, é necessário que os serviços de localização estejam ativados no dispositivo, incluindo:

* **Precisão de Local**
* **Precisão Alta**

# Token de Registro

Conforme visto na seção anterior é possível acessar o token de registro de dispositivos no menu "**Configurações**" na opção "**Gerenciar Políticas**". A tela do token de registro é mostrada a seguir.

<figure><img src="../../../.gitbook/assets/Captura de tela 2024-04-30 103515.png" alt=""><figcaption></figcaption></figure>

Os itens disponíveis nesta tela são descritos abaixo:&#x20;

1. O Token de Registro da política pode ser copiado e enviado.
2. A configuração Zero Touch da política pode ser copiada para ser inserida no painel Zero Touch.&#x20;
3. O sistema apresentará um campo para a seleção da 'Rede Wi-Fi'. Nessa tela, será possível escolher uma das redes Wi-Fi previamente configuradas na seção '[Gerenciar Redes Wi-Fi](../gerenciar-redes-wi-fi.md)'. Ao selecionar, será incluso no QR Code todas as configurações possíveis com os seguintes tipos de segurança:
   * WPA/WPA 2
   * WEP
   * Nenhuma

Ao realizar o registro utilizando o QR Code, o dispositivo será conectado automaticamente à rede configurada.

4. A opção “Habilitar Aplicativos de Sistema" permite habilitar todos os aplicativos de sistema nativos do dispositivo.  Quando esta opção é ativada, o sistema atualizará a imagem do QRCode incluindo a informação para habilitar os aplicativos de sistema.
5. Ao ativar o campo "Pular Criptografia", será inclusa a seguinte informação no QRCode: "_android.app.extra.PROVISIONING\_SKIP\_ENCRYPTION_". O sistema também atualizará a imagem do QRCode com a nova configuração e atualizará a configuração do Zero Touch. Após realizar o enroll com o QRCode, o dispositivo ignorará a criptografia do sistema.
6. Ao ativar a opção "Usar Dados Móveis" do sistema operacional (SO), será incluída a seguinte informação no QRCode: “_android.app.extra.PROVISIONING\_USE\_MOBILE\_DATA_". E o sistema atualizará a imagem do QRCode com a nova configuração.  Após realizar o enroll com o QRCode, o dispositivo utilizará os dados móveis durante o processo de configuração.
7. Ao concluir as configurações, o sistema permitirá salvar ou cancelar o salvamento das configurações, armazenando-as ao finalizar o processo de salvamento.
8. O QR Code da política pode ser lido na tela para o processo de registro de dispositivos ou pode ser copiado e enviado para os usuários dos dispositivos.

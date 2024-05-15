# Novas Configurações no QRCode

Na tela de "Token de Registro" de uma política foram adicionados novos campos para facilitar o enroll do dispositivo, são eles:

* **Gerenciar Redes Wi-F**i - é possível selecionar uma das redes Wi-Fi configuradas na tela "Gerenciar Redes Wi-fi". Ao selecionar uma rede, o sistema incluirá todas as configurações possíveis no QRCode, abrangendo os seguintes tipos de segurança: WPA/WPA 2, WEP e nenhuma segurança. Ao realizar o enroll com o QRCode, o dispositivo se conectará automaticamente à rede configurada, simplificando o processo de configuração inicial do dispositivo.
* **Pular Criptografia -** Ao ativar essa opção, o sistema incluirá a seguinte informação no QRCode: "android.app.extra.PROVISIONING\_SKIP\_ENCRYPTION": (true/false - padrão “false"). Ao realizar o enroll com o QRCode, o dispositivo irá ignorar a criptografia do dispositivo durante o processo de configuração inicial.
* **Usar Dados Móveis** - Ao ativar essa opção, o sistema incluirá a seguinte informação no QRCode: _“android.app.extra.PROVISIONING\_USE\_MOBILE\_DATA": (true/false - padrão “false"). A_o realizar o enroll com o QRCode, o dispositivo irá utilizar os dados móveis durante o processo de configuração inicial.

<figure><img src="../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

[**Voltar ao menu inicial**](./)

# Modo Quiosque

Esta configuração tem como objetivo possibilitar a criação de um ambiente em que o usuário do dispositivo possa acessar somente os aplicativos previamente liberados pelo administrador, ou seja, apenas os ícones dos aplicativos selecionados serão exibidos na tela do dispositivo.

Para acessar as configurações de "**Modo Quiosque**" siga os seguintes passos:

1. Na tela "**Editar política**", selecione a guia "**Modo Quiosque**".
2. Ative o modo quiosque clicando sobre o botão de ativação.

<figure><img src="../../../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

3. Será exibida na tela uma mensagem para confirmação. Confirme clicando no botão "**Ativar**".

<figure><img src="../../../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

4. Ao ativar o Modo Quiosque na política e provisionar um dispositivo com esta política, o aplicativo **Kiosk Launcher Manager** será instalado automaticamente no dispositivo.

<figure><img src="../../../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

5. Quando o dispositivo instalar o aplicativo Kiosk, o aplicativo capturará a lista de todos os aplicativos instalados no dispositivo enviará esta lista para o Portal. Além disto enviará as seguintes configurações gerenciadas para o portal:
6. Papel de parede;
7. Orientação de Tela;
8. Lista de aplicativos exibidos;

E alterará a launcher do Dispositivo para a launcher do aplicativo Kiosk, não permitirá que o usuário altere a launcher no dispositivo e manterá a configuração de Modo Quiosque recebida na politica.

* **Papel de parede -** pode ser realizado o upload de uma imagem de papel de parede na política e definido a orientação de tela , que serão enviados para o aplicativo.

<figure><img src="../../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

Os aplicativos que serão exibidos no dispositivo, serão definidos na política, ou seja, somente os aplicativos liberados na política serão exibidos na laucher.

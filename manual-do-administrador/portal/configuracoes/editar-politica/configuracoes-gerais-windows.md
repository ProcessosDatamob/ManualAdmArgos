# Configurações Gerais - Windows

O modo de gerenciamento Windows, permite gerenciar dispositivos Windows de forma centralizada, aplicando configurações como restrições, instalação de aplicativos, atualizações e políticas de segurança. Inclui controle de aplicativos, configuração remota e monitoramento, garantindo conformidade com as normas corporativas.

#### **Configurações Intel® AMT**

A funcionalidade de Configuração de Política Intel AMT no Windows oferece ao administrador a capacidade de configurar e gerenciar dispositivos equipados com Intel® Active Management Technology (Intel® AMT). Isso possibilita um controle aprimorado sobre os dispositivos Windows através de um portal administrativo.

**Opções de Configuração do Intel AMT**

* Nenhuma: Selecione esta opção se o Intel AMT não for necessário para o gerenciamento remoto ou se a configuração for realizada externamente ao sistema.
* Desativar: Utilize esta opção para desabilitar o recurso de gerenciamento remoto Intel AMT, garantindo que não seja utilizado sem necessidade.
* Modo de Controle de Cliente Simples (CCM): Esta opção ativa o gerenciamento remoto básico do dispositivo, adequada para cenários onde permissões avançadas não são necessárias. Pré-requisitos: Para a ativação do CCM, é necessário que o dispositivo possua um chipset compatível com Intel AMT e que não haja exigência de autenticação de dois fatores ou criptografia adicional.
* Modo de Controle de Administrador Simples (ACM): Ideal para situações que exigem gerenciamento remoto avançado, com maior acesso e controle sobre os dispositivos. Pré-requisitos:
  * Hardware Compatível: O dispositivo deve ser compatível com a versão mais recente do Intel AMT.
  * Certificado do Servidor: É necessário um certificado de segurança SSL/TLS para autenticar a comunicação entre o dispositivo e o servidor.
  * Servidor DHCP: Um servidor DHCP configurado para atribuir IPs automaticamente aos dispositivos na rede.
  * Certificado de CA Raiz: Certificado de uma Autoridade Certificadora Raiz para validar a identidade do servidor e dos dispositivos gerenciados.

**Envio e Atualização de Configurações**

As configurações são enviadas automaticamente ao salvar as alterações na política, assegurando que os dispositivos associados sejam atualizados com os parâmetros definidos pelo administrador. Isso inclui a atualização automática de firmware e software, conforme necessário, garantindo a conformidade e a segurança dos dispositivos gerenciados.

<figure><img src="../../../../.gitbook/assets/image (324).png" alt=""><figcaption></figcaption></figure>

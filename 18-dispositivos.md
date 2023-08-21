# 18 DISPOSITIVOS&#x20;

**18 DISPOSITIVOS**

Esta tela do sistema tem como objetivo, possibilitar ao usuário gerenciar as informações e executar algumas ações nos dispositivos ativos da empresa.

Para saber como gerenciar os dispositivos ativos da empresa, siga os passos descritos abaixo.

1. Clique no menu “**Dispositivos**” opção "**Lista de Dispositivos**" para acessar a tela.

![](<.gitbook/assets/0 (15).png>)

1. Na parte superior da tela o sistema exibe a distribuição dos dispositivos, separados por fabricantes.
2. A lista de dispositivos é mostrada na parte inferior da tela.
3. Para localizar um dispositivo específico, digite o nome do usuário, IMEI ou ICCID do dispositivo no campo “Pesquisar”.
4. Para exportar o relatório dos dispositivos, clique no botão “Excel”.
5. Para copiar as informações dos dispositivos, clique no botão “Copiar”.
6. Use os filtros fabricante, modelo, telefone, grupo e sistema operacional para encontrar os dispositivos de deseja listar.
7. Ordene a listagem de dispositivos pelas colunas nas setas "↑↓".
8. Clique no ">" para visualizar todas as informações do dispositivo.
9. Use os três pontinhos "..." para exibir o menu de ações e aplicar a ação desejada ao dispositivo.

![](<.gitbook/assets/1 (14).png>)

**18.1.1 Informações do Dispositivo**

As informações do dispositivo exibidas na lista são:

* **Usuário -** nome do usuário cadastrado no portal;
* **Identificação -** Identificação cadastrada para o dispositivo;
* **Telefone -** número de telefone;
* **IMEI -** número interno e único em cada dispositivo. No Android 10 já não é possível capturar esta informação do dispositivo porque utilizamos outro método para receber esta informação com o Enriquecimento de URL;
* **ICCID -** número do chip SIM;
* **Modelo -** modelo do dispositivo;

Clicando no sinal ">" ao lado do usuário o sistema exibe mais informações conforme pode ser visto na imagem abaixo.

![](<.gitbook/assets/2 (8).png>)

* **Política** - nome da política atribuída ao dispositivo;
* **Fabricante -** nome do fabricante do dispositivo;
* **Sistema** **operacional** - versão do Android ou iOS;
* **Data** **de** **registro** - data e hora do registro do dispositivo;
* **Grupo** - grupo ao qual o dispositivo está associado;
* **Status** - informa status do dispositivo. Os status que um dispositivo pode ter estão na tabela a seguir.

| **Status**    | **Descrição**                                                                                                                   |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| Ativo         | O dispositivo está ativo.                                                                                                       |
| Desabilitado  | O dispositivo está desativado.                                                                                                  |
| Deletado      | O dispositivo foi excluído. Esse estado é usado no relatório de status final quando o dispositivo confirma a exclusão.          |
| Provisionando | O dispositivo está sendo provisionado. Os dispositivos recém-registrados ficam nesse estado até que uma política seja aplicada. |

**18.1.2 Opções de gerenciamento de dispositivos**

Na tela de "**Dispositivos**" é possível ter acesso a opções de consulta e configurações do dispositivo usando os três pontinhos "**...**" que aparecem à direita na listagem dos dispositivos. As opções disponíveis estão em destaque na imagem a seguir.

![](<.gitbook/assets/3 (5).png>)

As opções que estão em destaque na figura são detalhadas nas próximas subseções.

* **Histórico de Bateria**

Para visualizar o histórico da bateria do dispositivo, clique em “**Histórico de bateria**”.

O sistema exibirá a tela do histórico da bateria do dispositivo.

1. Selecione uma data, para visualizar os dados do histórico.
2. Passe o mouse sobre o gráfico para visualizar os valores em horário específico.

![](<.gitbook/assets/4 (5).png>)

* **Histórico de Armazenamento**

Para visualizar o histórico de memória livre no armazenamento interno do dispositivo, clique em “**Histórico de armazenamento**”.

![](<.gitbook/assets/5 (4).png>)

O sistema exibirá a tela do "**Histórico de Armazenamento**" com o histórico de memória livre do dispositivo.

1. Selecione uma data, para visualizar os dados do histórico.
2. Passe o mouse sobre o gráfico para visualizar os valores em horário específico.

* **Relatório de Não Conformidade**

Para exibir as inconsistências em configurações atribuídas ao dispositivo utilize a opção "Relatório de Não conformidade".

![](<.gitbook/assets/6 (4).png>)

* **Alterar Política**

Ao escolher a opção Alterar Política, aparecerá no centro da tela uma caixa de diálogo para a escolha da política a ser atribuída ao dispositivo. Escolha a política entre as políticas listadas e clique em atualizar para mudar a política do dispositivo.

A política define configurações, incluindo critérios de hardware, software, sistema operacional, segurança etc. Para saber mais sobre Políticas, leia a seção de configurações deste manual.

![](<.gitbook/assets/7 (5).png>)

* **Desativar Dispositivo**

Ao enviar o comando Desativar Dispositivos, todos os aplicativos que não são Google serão desativados, serão permitidas chamadas telefônicas e o status do dispositivo muda para desativado. Para desativar um dispositivo utilize a opção **"Desativar Dispositivo"** no menu de opções do dispositivo. Esta opção aparece somente para dispositivos que estão no status "Ativo". Uma tela de confirmação será exibida conforme apresentado abaixo.

![](<.gitbook/assets/8 (5).png>)

Clique no botão "**Desativar**" para confirmar a operação.

* **Ativar Dispositivo**

Esta opção aparece somente para dispositivos que estão no status "Desabilitado". Para ativar um dispositivo desabilitado clique em "**Ativar Dispositivo**" nas opções de gerenciamento do dispositivo.

![Interface gráfica do usuário, Aplicativo, Teams

Descrição gerada automaticamente](<.gitbook/assets/9 (4).png>)

Confirme a atualização clicando em "**Ativar**" na caixa de diálogo, conforme apresentado na sequência.

![Interface gráfica do usuário, Aplicativo, Site, Teams

Descrição gerada automaticamente](<.gitbook/assets/10 (4).png>)

* **Desligar Tela do dispositivo**

A opção "**Desligar Tela**" envia um comando para desligar a tela do dispositivo. Ao clicar na opção "**Desligar Tela**" o comando é executado diretamente e uma mensagem aparecerá na tela para informar que o comando foi enviado ao dispositivo.

* **Reiniciar Dispositivo**

Esta operação envia um comando para reiniciar o dispositivo. Escolha a opção **"Reiniciar Dispositivo"**. Uma mensagem é exibida na tela do portal para confirmar o envio do comando. A mensagem exibida é mostrada abaixo.

![](<.gitbook/assets/11 (3).png>)

![](<.gitbook/assets/12 (3).png>)

### Remover Bloqueio de Tela <a href="#_m1k0bxtzeff5" id="_m1k0bxtzeff5"></a>

Esta operação envia um comando para remover o bloqueio de tela do dispositivo. Escolha a opção "**Remover Bloqueio de Tela**". Uma mensagem é exibida na tela do portal para confirmar o envio do comando. A mensagem exibida é mostrada abaixo.

**Observação:** Esta opção só ficará disponível para dispositivos ativados com política em modo de gerenciamento Android Block SIM.

![](<.gitbook/assets/13 (3).png>)

* **Gerar nova senha do dispositivo**

O sistema permite que seja gerada uma nova senha para o dispositivo. Para realizar esta operação, escolha a opção "**Gerar Nova Senha do Dispositivo**" conforme mostrado na imagem apresentada na sequência.

Preencha os campos "**Nova Senha**" e "**Confirmar nova senha**" com valores iguais para que o botão "**Confirmar**" esteja habilitado. Opcionalmente, e conforme a necessidade, poderão ser marcadas as opções:

* Não permitir que outros administradores alterem a senha novamente até que o usuário a insira no dispositivo;
* Não pedir credenciais de usuário na inicialização do dispositivo;
* Bloquear o dispositivo após a redefinição da senha.

A tela para gerar nova senha do dispositivo é mostrada a seguir.

![](<.gitbook/assets/14 (3).png>)

* **Remover Dispositivo (WIPE)**

Esta operação permite excluir um dispositivo. Ela limpa os dados e configurações do dispositivo. Os dispositivos excluídos não aparecem na lista de dispositivos da empresa. A opção "**Remover Dispositivo**" aparece na lista de opções do dispositivo na tela de listagem de dispositivos (menu "**Dispositivos**", opção "**Listar Dispositivos**").

Conforme pode ser visto na imagem apresentada a seguir, uma mensagem é exibida na tela para informação e advertência. A operação não pode ser desfeita, portanto, confirme somente quando tiver certeza de que deseja eliminar o dispositivo.

![](<.gitbook/assets/15 (2).png>)

* **Gerenciar Informações**

Esta opção permite acessar a tela para editar dados do dispositivo, como: Usuário, identificação e Grupo.

![](<.gitbook/assets/16 (2).png>)

Além de poder editar os dados, são exibidos mais abaixo duas listas com as informações de Software e Hardware relacionados ao dispositivo gerenciado:

![](<.gitbook/assets/17 (2).png>)

**Informações de Software**

* **Sistema** **operacional** - Android;
* **Número** **de** **Série** - número de série do dispositivo;
* **Em conformidade** - é a aderência do dispositivo a todas as configurações de políticas atribuídas a ele. Se alguma configuração não foi aplicada, o valor desta opção será "Não". É possível acessar o "Relatório de Não Conformidade" nos três pontinhos no final da linha do dispositivo;
* **Status Aplicado -** status atribuído ao dispositivo;
* **Data da última atualização -** data e hora em que as informações do dispositivo foram sincronizadas com o portal;
* **Data da sincronização da política -** data e hora da última sincronização de Política;
* Armazenamento interno - espaço de armazenamento do dispositivo;
* **Versão do Android -** Versão do Android;
* **Versão da Política Aplicada -** versão da política que está aplicada no dispositivo;
* **Nome da Política no Portal** - nome da política atribuída ao dispositivo;
* **Nome da Política no Dispositivo -** nome da política que está aplicada no dispositivo;

**Informações de Hardware**

* **Armazenamento Interno -** quanto de armazenamento interno possui;
* **Bateria -** Quantos % de bateria está no momento;

**18.2 Informações dos Aplicativos**

O submenu Informações dos aplicativos mostra as informações dos aplicativos do dispositivo.

1. Clique no menu "**Dispositivos**" opção "**Informações dos aplicativos**" para acessar a tela.

![](<.gitbook/assets/18 (2).png>)

1. Na parte superior, pode ser filtrado por Grupo ou Usuários, de modo que a lista de aplicações é mostrada abaixo de acordo com o filtro selecionado;
2. A lista de dispositivos é exibida na parte inferior da tela;
3. Para buscar um aplicativo específico, escreva o nome do aplicativo no campo de Busca;
4. Para exportar o relatório dos dispositivos, clique no botão "Excel";
5. Para copiar as informações dos dispositivos, clique no botão "Copiar";
6. Ordene a lista de aplicativos nas colunas clicando nas flechas “ ![](<.gitbook/assets/19 (2).png>)”
7. Utilize os três pontos "..." para mostrar o menu de ações e ver os detalhes dos aplicativos;

![](<.gitbook/assets/20 (2).png>)

**18.2.1 Histórico de Consumo**

Para acessar esta tela, use os três pontos no final da linha do aplicativo. Nesta tela pode-se visualizar o gráfico de evolução do consumo de dados da aplicação dos dispositivos.

**18.2.2 Usuários com Aplicativos**

Para acessar esta tela, use os três pontos no final da linha do aplicativo. Nesta tela, você pode ver todos os dispositivos que possuem o aplicativo instalado.

# Lista de dispositivos

Para saber como gerenciar os dispositivos ativos da empresa, siga os passos descritos abaixo.

1. Clique no menu “**Dispositivos**” opção "**Lista de Dispositivos**" para acessar a tela

<figure><img src="../../../.gitbook/assets/image (35).png" alt=""><figcaption></figcaption></figure>

2. Na parte superior da tela o sistema exibe a distribuição dos dispositivos, separados por fabricantes
3. A lista de dispositivos é mostrada na parte inferior da tela
4. Para localizar um dispositivo específico, digite o nome do usuário, IMEI ou ICCID do dispositivo no campo “Pesquisar”
5. Para exportar o relatório dos dispositivos, clique no botão “Excel”
6. Para copiar as informações dos dispositivos, clique no botão “Copiar”
7. Use os filtros Grupo, Política, Modelo e Fabricante para encontrar os dispositivos se deseja listar ou utilize os Filtros Avançados para buscar Modo de Gerenciamento e Data Inicial de Registro e Data Final de Registro (filtrará pela data de registro dos dispositivos que estão no período especificado) para acessar as informações desejadas

<figure><img src="../../../.gitbook/assets/image (73).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**NOTA**

Para realizar a pesquisa pelo número do telefone utilizar o campo de pesquisa livre.
{% endhint %}

8. Ordene a listagem de dispositivos pelas colunas nas setas "↑↓"
9. Clique no ">" para visualizar todas as informações do dispositivo

<figure><img src="../../../.gitbook/assets/image (74).png" alt=""><figcaption></figcaption></figure>

8. Use os três pontinhos "..." para exibir o menu de ações e aplicar a ação desejada ao dispositivo

### **Informações do Dispositivo**

As informações do dispositivo exibidas na lista são:

* **Usuário -** nome do usuário cadastrado no portal;
* **Identificação -** Identificação cadastrada para o dispositivo;
* **Telefone -** número de telefone;
* **IMEI -** número interno e único em cada dispositivo. No Android 10 já não é possível capturar esta informação do dispositivo porque utilizamos outro método para receber esta informação com o Enriquecimento de URL;
* **Modelo -** modelo do dispositivo;

Clicando no sinal ">" ao lado do usuário, o sistema exibe mais informações conforme pode ser visto na imagem abaixo.

<figure><img src="../../../.gitbook/assets/image (74).png" alt=""><figcaption></figcaption></figure>

* **Política** - nome da política atribuída ao dispositivo;
* **Modo de Gerenciamento** - modo de gerenciamento atribuído ao dispositivo;
* **Versão do app \<NomeProduto> -** versão do companion instalado no dispositivo;
* **ICCID -** número do chip SIM;
* **Fabricante** - nome do fabricante do dispositivo;
* **Sistema** **operacional** - versão do Android;
* **Data** **de** **registro** - data e hora do registro do dispositivo;
* **Grupo** - grupo ao qual o dispositivo está associado;
* **Data da última comunicação** - última comunicação do dispositivo;
* **Status** - informa status do dispositivo. Os status que um dispositivo pode ter estão na tabela a seguir:

<table data-header-hidden><thead><tr><th width="164.98324022346367"></th><th></th></tr></thead><tbody><tr><td><strong>Status</strong></td><td><strong>Descrição</strong></td></tr><tr><td>Ativo</td><td>O dispositivo está ativo.</td></tr><tr><td>Desabilitado</td><td>O dispositivo está desativado.</td></tr><tr><td>Deletado</td><td>O dispositivo foi excluído. Esse estado é usado no relatório de status final quando o dispositivo confirma a exclusão.</td></tr><tr><td>Provisionando</td><td>O dispositivo está sendo provisionado. Os dispositivos recém registrados ficam nesse estado até que uma política seja aplicada.</td></tr></tbody></table>

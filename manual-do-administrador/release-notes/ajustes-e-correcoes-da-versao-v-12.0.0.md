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

# Ajustes e Correções da Versão

Nesta versão, foram realizadas correções dos bugs listados abaixo:

1. **Remoção indevida de Bloqueio de Tela -** Ao enviar comando de Remoção de bloqueio de chip, onde o bloqueio de tela também era removido indevidamente;
2. **Aparelhos Bloqueados com senha de Bloqueio de Tela e senha não funciona -** Ao enviar o comando “Remover Bloqueio de Tela” para o dispositivo, mesmo assim seguia pedindo a senha e não aceitava a senha anterior e nem mesmo informar nenhuma;
3. **Edição de Política - Aplicativos mostrando contador incorreto -** O contador do rodapé da página de aplicativos da política estava incorreto;
4. **Gerenciar Redes Wi-fi -** Não era possível salvar rede WPA-EAP sem informar senha - no menu Configurações → Gerenciar Redes Wi-fi ao selecionar selecionando o Tipo de Segurança WPA-EAP estava solicitando uma senha que não é necessária e não permitia salvar a configuração sem o preenchimento da senha;

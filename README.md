# BridgeMaster Public

**BridgeMaster** é um software que atua como uma **ponte de comunicação entre dispositivos**, permitindo integração eficiente entre múltiplos endpoints, com suporte a licenças e validação online/offline.

---

## Sobre o Software

Este software permite criar uma arquitetura baseada em **sources** e **targets**:

- Dispositivos podem ser agrupados como **sources** ou **targets**.
- Dados enviados por um **source** são automaticamente distribuídos para todos os **targets** configurados.
- Mensagens recebidas de um **target** são encaminhadas para todos os **sources**.
- Suporta envio de mensagens em formatos:
  - Texto
  - Hexadecimal
  - Byte array
- Mensagens podem ser enviadas para:
  - Todos os dispositivos
  - Grupos específicos
  - Dispositivos individuais

**Funcionalidades adicionais:**

- Registro de **logs detalhados** de todas as comunicações.
- Console integrado para envio manual de mensagens.
- Flexibilidade de comunicação:
  - **Serial** (incluindo criação de portas virtuais)
  - **TCP** (modo cliente e servidor)
  - **UDP**
- Validação de licenças com fallback offline (arquivo local encriptado pelo ID da máquina).
- Suporte a licenças trial de 30 dias e licenças completas.

---

## Requisitos

- Windows 10 ou superior
- .NET 6 ou .NET 7 Runtime
- Conexão com internet (para validação de licenças online)
- Permissões para criação de arquivos em `%AppData%` (para salvar licenças locais)

---

## Instalação

1. Baixe a versão mais recente na pasta **Releases**.
2. Execute o instalador e siga as instruções.
3. Ao abrir o software pela primeira vez:
   - Se não houver licença, será criada automaticamente uma **licença trial de 30 dias**.
   - Licença é validada no GitHub e armazenada localmente.
   - Caso a validação online falhe, o software usa a licença local.

---

## Como Usar

### Interface Principal

- Configure **sources** e **targets** no console.
- Mensagens podem ser enviadas manualmente ou automaticamente distribuídas.
- Visualize logs detalhados de comunicação.
- Envio de mensagens:
  - Para todos os dispositivos
  - Para grupos específicos
  - Para dispositivos individuais
- Formatos de mensagem suportados:
  - Texto
  - Hexadecimal
  - Byte array

### Licenças

- Trial: 30 dias, ativada automaticamente.
- Licença ativa: obtida via GitHub ou importada manualmente.
- Licença expirada ou inativa bloqueia acesso aos módulos.

**Exemplo de mensagem de licença inválida:**


Licença inválida ou expirada.
Machine ID: XXXX-XXXX
License ID: XXXXXXXX
Entre em contato: suporte@seudominio.com


---

## Atualizações

- O software possui um mecanismo de **verificação de updates** via GitHub.
- É possível validar atualizações automaticamente a cada 12 horas.
- Arquivo de validação está na pasta **Validation/**.

---

## Desenvolvedores

### Estrutura do Código-Fonte

- **LicenseManager**: gerencia licenças, validação online/offline.
- **GitHubService**: comunicação com o GitHub para licenças e updates.
- **Views**: janelas WPF (LicenseAdmin, LicenseEdit, Console Principal)
- **Models**: classes LicenseData, MachineIdHelper, etc.
- **Utils**: criptografia, logs, helpers.

## Licença do Software
Desenvolvido por Rafael Pinal
© 2026 Rafael Pinal. Todos os direitos reservados.
Uso de licenças é obrigatório para acesso completo ao software.
Contato e Suporte
Email: suporte@seudominio.com
Para dúvidas de licença, instalação ou bugs.
Tradução Inglês

BridgeMaster is a communication bridge software between devices:

Configurable sources and targets
Automatic message forwarding between devices
Logs all communications
Console for sending messages in text, hex or byte format
Supports Serial, TCP and UDP
License management: online validation and offline fallback

For more details, see the sections above.

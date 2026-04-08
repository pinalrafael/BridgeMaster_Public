# BridgeMaster

<p align="center">
  <img src="docs/images/banner.png" alt="BridgeMaster Banner" width="100%">
</p>

<p align="center">
  <b>Serial • TCP • UDP Integration Middleware</b><br>
  Bridge multiple communication endpoints with real-time routing and monitoring
</p>

<p align="center">
  <a href="../../releases">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" />
  </a>
</p>

---

## 🇧🇷 Português

### 🚀 Sobre o BridgeMaster

O **BridgeMaster** é uma plataforma de integração que cria uma ponte entre múltiplos endpoints de comunicação, permitindo o roteamento e encaminhamento de mensagens entre diferentes protocolos e interfaces.

---

### 🖼️ Interface

#### 🏠 Home

<img src="docs/images/home.png" width="100%">

#### 📝 Cadastro de Endpoints

<img src="docs/images/register.png" width="100%">

#### ⚙️ Configurações

<img src="docs/images/settings.png" width="100%">

#### 🧭 Gerenciamento de Endpoints

<img src="docs/images/management.png" width="100%">

#### 🌗 Tema Claro / Escuro

<img src="docs/images/themes.png" width="100%">

#### 📡 Comunicação em Tempo Real

<img src="docs/images/communication.png" width="100%">

> Exemplo: terminal serial e terminal TCP trocando mensagens em tempo real

---

### 🧩 Problema que resolve

Integrar diferentes tipos de comunicação (Serial, TCP, UDP) normalmente exige esforço elevado e pouca visibilidade.
O BridgeMaster centraliza tudo em uma única interface com monitoramento completo.

---

### ⚙️ Como funciona

* **Sources** → origem das mensagens
* **Targets** → destino das mensagens

Fluxo:

* Source → envia para todos Targets
* Target → responde para todos Sources

---

### 🔌 Endpoints suportados

* Serial físico (COM)
* Serial virtual
* TCP Server
* TCP Client
* UDP Client

---

### ✨ Funcionalidades

* Múltiplos endpoints simultâneos
* Encaminhamento automático
* Logs completos
* Envio manual (Texto / Hex / Byte)
* Servidor TCP integrado
* Porta serial virtual
* CLI e DLL gratuitos

---

### 💡 Casos de uso

* Dispositivo serial → múltiplos PCs via TCP
* Monitoramento remoto (LAN/VPN)
* Gateway entre protocolos
* Simulação de comunicação
* Integração hardware/software

---

### 🖥️ Plataforma

* Windows
* WPF (.NET 10)
* SQLite local

---

### 🔐 Licenciamento

* 7 dias grátis
* Após isso, requer licença

---

## 💰 Preço

<p align="center">
  <b>Comece gratuitamente. Evolua conforme sua necessidade.</b>
</p>

---

| Plano                 | Ideal para              | Recursos                                                                                                                | Preço                                            |
| --------------------- | ----------------------- | ----------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------ |
| 🟢 **Starter**        | Testes e uso básico     | 1 bridge ativa<br>Até 5 endpoints<br>Logs básicos                                                                       | **Gratuito (limitado)**                          |
| 🔵 **Professional ⭐** | Uso profissional        | Bridges múltiplas<br>Endpoints ilimitados<br>Logs completos<br>Serial virtual + TCP server<br>Envio manual de mensagens | **R$ 79–149 / mês**<br>ou **R$ 397–697 licença** |
| 🟣 **Enterprise**     | Empresas e alta demanda | Tudo do Professional<br>Suporte prioritário<br>Customizações<br>Acesso antecipado a novas features                      | **Sob consulta**                                 |

<p align="center">
  <a href="mailto:contato@cpsystems.com.br">
    <img src="https://img.shields.io/badge/Comprar%20Licen%C3%A7a-Entrar%20em%20Contato-success?style=for-the-badge&logo=gmail">
  </a>
</p>

---

### 🔐 Trial

* 7 dias de teste gratuito com acesso completo
* Após o período, algumas funcionalidades podem ser limitadas ou bloqueadas
* Licença necessária para uso contínuo

---

### 💡 Notas

* Licenças são vinculadas à máquina
* Descontos podem ser aplicados para uso corporativo
* Entre em contato para planos personalizados

---

---

## 🇺🇸 English

### 🚀 About BridgeMaster

**BridgeMaster** is an integration platform that bridges multiple communication endpoints, enabling real-time message routing across different protocols.

---

### 🖼️ Interface

#### 🏠 Home

<img src="docs/images/home.png" width="100%">

#### 📝 Endpoint Registration

<img src="docs/images/register.png" width="100%">

#### ⚙️ Settings

<img src="docs/images/settings.png" width="100%">

#### 🧭 Endpoint Management

<img src="docs/images/management.png" width="100%">

#### 🌗 Light / Dark Theme

<img src="docs/images/themes.png" width="100%">

#### 📡 Real-Time Communication

<img src="docs/images/communication.png" width="100%">

> Example: serial terminal communicating with a TCP terminal in real time

---

### 🧩 Problem it solves

Integrating Serial, TCP, and UDP communications is complex and fragmented.
BridgeMaster centralizes everything into a single, observable system.

---

### ⚙️ How it works

* **Sources** → message origin
* **Targets** → message destination

Flow:

* Source → forwarded to all Targets
* Target → forwarded to all Sources

---

### 🔌 Supported endpoints

* Physical Serial (COM)
* Virtual Serial
* TCP Server
* TCP Client
* UDP Client

---

### ✨ Features

* Multi-endpoint configuration
* Automatic routing
* Full logging
* Manual message sending
* Built-in TCP server
* Virtual serial ports
* Free CLI and DLL

---

### 💡 Use cases

* Serial device → multiple TCP clients
* Remote monitoring (LAN/VPN)
* Protocol gateway
* Communication simulation
* Hardware/software integration

---

### 🖥️ Platform

* Windows
* WPF (.NET 10)
* SQLite (local DB)

---

### 🔐 Licensing

* 7-day free trial
* License required after trial

---

## 💰 Pricing

<p align="center">
  <b>Start free. Upgrade when you need more power.</b>
</p>

---

| Plan                  | Best for                               | Features                                                                                                         | Price                                         |
| --------------------- | -------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | --------------------------------------------- |
| 🟢 **Starter**        | Testing and basic usage                | 1 active bridge<br>Up to 5 endpoints<br>Basic logs                                                               | **Free (limited)**                            |
| 🔵 **Professional ⭐** | Professional use                       | Multiple bridges<br>Unlimited endpoints<br>Full logging<br>Virtual serial + TCP server<br>Manual message sending | **$15–30 / month**<br>or **$80–140 lifetime** |
| 🟣 **Enterprise**     | Companies and high-demand environments | Everything in Professional<br>Priority support<br>Custom builds<br>Early access to new features                  | **Contact us**                                |

<p align="center">
  <a href="mailto:contato@cpsystems.com.br">
    <img src="https://img.shields.io/badge/Get%20License-Contact%20Now-success?style=for-the-badge&logo=gmail">
  </a>
</p>

---

### 🔐 Trial

* 7-day free trial with full access
* After the trial period, some features may be limited or blocked
* License required for continued use

---

### 💡 Notes

* Licenses are machine-bound
* Discounts may apply for corporate use
* Contact us for customized plans

---

### ℹ️ Note

This repository is used only for releases and licensing.
Source code is private.

---

### 📧 Contato
Desenvolvido por Rafael Pinal
© 2026 Rafael Pinal. Todos os direitos reservados.
Uso de licenças é obrigatório para acesso completo ao software.
Contato e Suporte
Email: helpdesk@cpsystems.com.br
Para dúvidas de licença, instalação ou bugs.

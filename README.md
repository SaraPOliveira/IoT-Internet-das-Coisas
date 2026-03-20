<img src="https://img.shields.io/badge/License-MIT-purple?style=for-the-badge">

# 📡 IoT com Arduino Ethernet - Controle Web

Projeto de Internet das Coisas (IoT) utilizando Arduino com Ethernet Shield para comunicação em rede local e controle de dispositivos via navegador.

---

**Alunos:** Sara Oliveira, Nicolas
**Professor:** José de Assis
**Disciplina:** Redes de Computadores
**Data:** 17/03/2026

---

## 🌐 Acesse o Projeto Online

👉 (https://github.com/SaraPOliveira/IoT-Internet-das-Coisas)

---

## 📌 Sobre o Projeto

Este projeto demonstra a aplicação prática de conceitos de redes e IoT, utilizando um Arduino como servidor web.

---

## 🎯 Objetivos

* Conectar Arduino à rede
* Configurar IP fixo
* Criar servidor HTTP
* Controlar LEDs remotamente
* Testar conectividade via Ping

---

## 🔧 Componentes Utilizados

* Arduino UNO
* Ethernet Shield (W5100)
* Roteador
* 2 Cabos Ethernet
* Smartphone com aplicativo de Ping

---

## 🌐 Configuração de Rede

| Parâmetro  | Valor         |
| ---------- | ------------- |
| IP Arduino | 192.168.0.122 |
| Gateway    | 192.168.0.1   |
| Máscara    | 255.255.255.0 |
| Porta      | 80            |

✔ Latência média: **3ms ~ 13ms**

---

## 📡 Testes Realizados

* Ping via smartphone
* Comunicação estável
* Acesso via navegador

---

## 💡 Funcionamento

| URL          | Ação          |
| ------------ | ------------- |
| `/?led1-on`  | Liga LED 1    |
| `/?led1-off` | Desliga LED 1 |
| `/?led2-on`  | Liga LED 2    |
| `/?led2-off` | Desliga LED 2 |

---

## 📷 Imagens do Projeto

### 🔹 Hardware

<p align="center">
<img src="/images/arduino2.jpg" width="600" height="800">
</p>

### 🔹 Montagem

<p align="center">
<img src="/images/modelo-arduino.jpg" width="600">
</p>

### 🔹 Código

<p align="center">
<img src="/images/codigo.jpg" width="600">
</p>

### 🔹 Teste de Ping

<p align="center">
<img src="/images/sharedimage.jpg" width="500">
</p>

---

## 🔐 Segurança

* Comunicação local
* Proteção via firewall
* Risco ao usar DMZ

---

## Conclusão

Projeto funcional de IoT com integração entre hardware e rede, permitindo controle via navegador.

---
